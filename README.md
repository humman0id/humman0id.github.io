# Astro Blog Starter (GitHub Pages + KaTeX)

A complete, zero-cost, plug-and-play Astro blog template configured with KaTeX math rendering, RSS feed, dark/light mode support, and automatic GitHub Actions deployment.

## Quick Start

1. **Unzip and install dependencies:**
   ```bash
   cd astro-blog-starter
   npm install
   npm run dev
   ```
   Open `http://localhost:4321` to preview locally.

2. **Customize your info:**
   - Open `astro.config.mjs` and replace `<your-github-username>` with your GitHub username.
   - Open `src/consts.ts` to change `SITE_TITLE` and `SITE_DESCRIPTION`.
   - Edit `src/pages/about.astro` with your bio.

3. **Deploy to GitHub Pages (Free):**
   - Create a **public** repository on GitHub named `<your-github-username>.github.io`.
   - Go to your repo **Settings -> Pages -> Build and deployment -> Source** and select **GitHub Actions**.
   - Push this folder to GitHub:
     ```bash
     git init
     git add .
     git commit -m "Initial blog setup"
     git branch -M main
     git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
     git push -u origin main
     ```

4. **Write Posts:**
   - Add `.md` or `.mdx` files inside `src/content/blog/`.
   - Open `src/content/blog/` directly in Obsidian if you want to write your posts there.
