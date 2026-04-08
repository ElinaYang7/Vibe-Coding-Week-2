# The Slang Compiler

A browser-based language experiment that seeds a word, builds a semantic field around it, and periodically injects unrelated interruptions — then distills the resulting 100-word stream into a short phrase and an explanation of what shaped it.

The artifact tests whether controlled randomness produces more interesting language or simply breaks it. Users can adjust the intrusion rate (1 in 10 / 1 in 5 / 1 in 3) and a style target (Slang, Proverb, Meme, Mixed) to compare outcomes across runs.

## Run locally

No build step required. Open `index.html` directly in any modern browser:

```
open index.html
```

Or drag the file into a browser tab.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (public).
2. Push this folder's contents to the `main` branch:

```bash
cd providence-compiler
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/YOUR_USERNAME/providence-compiler.git
git push -u origin main
```

3. Go to **Settings → Pages** in your repository.
4. Under *Source*, select **Deploy from a branch** → `main` → `/ (root)`.
5. Save. GitHub will publish the site at `https://YOUR_USERNAME.github.io/providence-compiler/`.

## On Babbage and lawful interruptions

Charles Babbage's Ninth Bridgewater Treatise proposed that the laws of nature could accommodate miracles — not as violations of the system, but as exceptions built into it from the start. The Providence Compiler borrows that logic: the machine runs a lawful semantic process, but the interruptions are not accidents. They are pre-scheduled singular points. The question is whether those intrusions corrupt the output or complete it.
