# Jigyashu Bisht – HR Professional Portfolio

A static portfolio website (plain HTML and CSS, no build step).

## Files
- `index.html` – the whole website
- `images/` – project screenshots

## Publish with GitHub Pages
1. Upload everything in this folder to a GitHub repository (keep `images/` as a folder).
2. Go to **Settings → Pages**.
3. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Add a new project
1. Upload the screenshot to `images/` (for example `images/my-new-project.webp`; `.png` or `.jpg` also work).
2. Open `index.html` on GitHub and click the pencil icon (or edit it on your computer).
3. Find the Projects section and copy one whole block from `<article class="pr">` to `</article>`.
4. Paste it after the last project and change the title, description, tools, learning outcomes and image path.
   For each screenshot, update both `data-full="images/..."` and `src="images/..."` to the same file name.
5. Commit the change. The site updates in a minute or two.

## Update other text
Search `index.html` for the words you want to change (for example your email or a skill) and edit them.

## Edit on your computer
```
git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
# edit index.html, open it in a browser to preview
git add .
git commit -m "Describe your change"
git push
```
