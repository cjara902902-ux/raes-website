# Psych 2 Exam 1 Study Site

A static, single-file site (flashcards, notes, plain-English explanations, study guide).
No build step, no dependencies. `index.html` is the whole site.

## Deploy on Vercel

Option A: GitHub
1. Create a new GitHub repository and upload these files (index.html, vercel.json, README.md).
2. In Vercel, choose Add New > Project and import the repository.
3. Leave Framework Preset as "Other". Leave Build Command and Output Directory empty. Click Deploy.

Option B: Vercel CLI
1. Install Node.js, then run: npm i -g vercel
2. In this folder, run: vercel
3. Accept the defaults. Run `vercel --prod` to publish to your production URL.

## Notes
- Typed notes and checked-off topics are saved in each visitor's own browser (localStorage), so they are private to that browser and device.
- To edit content, change index.html and redeploy.
