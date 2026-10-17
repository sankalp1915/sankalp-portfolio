# Sankalp — Portfolio

Static site (no build step). Files: `index.html`, `Sankalp_Resume.pdf`, `vercel.json`.

## Deploy on Vercel
**Option A — drag & drop:** vercel.com → Add New → Project → "Deploy" without Git isn't available on all plans, so easiest is:
1. `npm i -g vercel`
2. In this folder: `vercel` (accept defaults, Framework = Other) → then `vercel --prod`.

**Option B — GitHub:** push this folder to a repo → vercel.com → Add New → Project → import repo → Framework Preset "Other", no build command, output dir `.` → Deploy.

## After deploy
- Rename project to `sankalp-portfolio` (or your choice) and update the "Portfolio" link in the resume header to the live URL.
- To update the résumé, replace `Sankalp_Resume.pdf` and redeploy.
