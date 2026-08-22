# Getting this live on GitHub Pages

1. **Edit the placeholders first.** Open `index.html` and search for:
   - `youremail@example.com` → your real email (appears twice)
   - `github.com/yourusername` → your GitHub profile (appears twice)
   - `linkedin.com/in/yourusername` → your LinkedIn
   - `resume.pdf` → put your resume PDF in the same folder, keep this filename, or rename to match
   - The `#` in "View writeup →" and "GitHub repo →" → link to your actual DAQ repo/writeup once you have one

2. **Create a GitHub repo.**
   - Go to github.com → New repository
   - Name it exactly `yourusername.github.io` (replace with your actual GitHub username) — this exact naming is what makes GitHub host it as your personal site
   - Keep it public, don't add a README (you already have one)

3. **Upload the files.**
   - On the new repo's page, click "uploading an existing file"
   - Drag in `index.html`, `README.md`, and your `resume.pdf`
   - Commit the changes

4. **Turn on Pages.**
   - Go to the repo's Settings → Pages (left sidebar)
   - Under "Build and deployment," set Source to "Deploy from a branch"
   - Branch: `main`, folder: `/ (root)` → Save

5. **Wait ~1 minute, then visit:**
   `https://yourusername.github.io`

That's it — no build step, no server, free forever. Any time you want to update the site, edit `index.html` in the repo (GitHub lets you edit directly in the browser) and it redeploys automatically within a minute or two.
