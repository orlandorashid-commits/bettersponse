Bettersponse Static Site Deployment

This folder is ready to deploy as a simple static website.

Files included:
- index.html: the full Bettersponse app
- README_DEPLOY.txt: these instructions

Fastest testing option, Netlify Drop:
1. Go to https://app.netlify.com/drop
2. Drag the entire bettersponse_static_site folder into the drop zone
3. Netlify will give you a temporary public URL ending in netlify.app
4. Share that URL with testers
5. To update later, edit index.html and drag the folder again to the same site's Deploys area

Vercel option:
1. Create a new GitHub repo named bettersponse-test or similar
2. Upload index.html to the root of the repo
3. In Vercel, choose Add New Project
4. Import the GitHub repo
5. Framework Preset: Other
6. Build Command: leave blank or None
7. Output Directory: .
8. Deploy

Important:
- This version does not use an API.
- No API key is needed.
- User progress is stored locally in each user's browser.
- If someone clears browser data or changes devices, their progress will not follow them.
- Because everything is inside index.html, edits can be made directly in that file for testing.

Suggested first-test checklist:
1. Open the site on desktop and phone.
2. Start a practice session.
3. Test Guided Response mode.
4. Test Write Your Own Response mode.
5. Test Pattern Library and Technique Library.
6. Check if progress and XP save after refresh.
7. Ask testers whether feedback feels too long, too harsh, too easy, or actually useful.
