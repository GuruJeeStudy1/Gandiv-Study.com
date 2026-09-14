# Gandiv Study

Free JEE study material website — Physics, Chemistry, and Mathematics, organized by chapter.

## Files in this project

```
index.html       → Homepage
physics.html      → Physics chapters
chemistry.html    → Chemistry chapters
maths.html        → Mathematics chapters
style.css         → Shared styling for all pages
```

All five files must stay in the same folder — the pages link to each other using relative paths (e.g. `physics.html`), and every page loads its design from `style.css`.

## How to put this on GitHub Pages (free hosting)

1. **Create a GitHub account** at github.com if you don't have one.
2. **Create a new repository**
   - Click the `+` icon (top right) → *New repository*
   - Name it anything, e.g. `gurujee-study`
   - Keep it Public
   - Click *Create repository*
3. **Upload the files**
   - On the new repository page, click *uploading an existing file*
   - Drag in all 5 files from this project (`index.html`, `physics.html`, `chemistry.html`, `maths.html`, `style.css`)
   - Scroll down, click *Commit changes*
4. **Turn on GitHub Pages**
   - Go to the repository's *Settings* tab
   - Click *Pages* in the left sidebar
   - Under "Branch", select `main` and folder `/ (root)`, then click *Save*
5. **Get your live link**
   - Wait about a minute, then refresh the Pages settings screen
   - Your site will be live at:
     `https://YOUR-USERNAME.github.io/gurujee-study/`

## Updating the site later

Edit any file directly on GitHub (click the pencil icon on a file) or re-upload a changed file through *Add file → Upload files*. Changes go live within a minute or two of committing.

## Notes

- The **Download** buttons are placeholders — they don't yet link to real PDFs. Once you have study material files ready (e.g. hosted on Google Drive), share them and the buttons can be wired to the real links.
- Once your site has a real live URL, update the `<link rel="canonical">` and `og:url` tags in each HTML file's `<head>` to match it — this helps Google index the site correctly under that address.
