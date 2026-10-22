# Darkroom Pocket: offline install guide

Files: index.html, sw.js, manifest.webmanifest, 3 icons. Keep them all in the same folder.

## Host it free on GitHub Pages
1. Make a free account at github.com and create a new public repository (any name).
2. Click "Add file" > "Upload files", drag in ALL the files from this zip (not the zip itself), then Commit.
3. Go to Settings > Pages. Under "Branch" choose main and folder / (root), then Save.
4. After a minute your app is live at https://YOUR-NAME.github.io/REPO-NAME/

## Put it on your iPhone (works offline)
1. Open that link in Safari (not Chrome) while online. Let it load fully.
2. Tap Share > Add to Home Screen > Add.
3. Open it once from the Home Screen icon while online, then try airplane mode.

## Notes
- Saving a finished picture: Export > Share / Save > Save Image.
- To update later, upload the new files over the old ones and change CACHE name in sw.js (v1 to v2).
- Netlify Drop (app.netlify.com/drop) also works: drag the folder in, no account setup needed for a quick test.
