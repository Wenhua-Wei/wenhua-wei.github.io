# Wenhua Wei — Classic Academic Homepage

This static homepage follows the layout of the supplied reference: white background, narrow top navigation, a circular portrait/profile column on the left, and About me / Interests / Education on the right. Publications, projects and experience continue below the fold.

## Website files

- `index.html` — all editable content and navigation
- `style.css` — layout, typography and responsive styling
- `assets/profile.jpg` — your supplied photo, displayed as a circular image using CSS (`object-fit: cover`)
- `assets/Wenhua_Wei_CV_Public.pdf` — phone-number-free public copy of the supplied CV
- `assets/favicon.svg` — browser tab icon

## Publish to GitHub Pages

1. Create a **public** repository named `Wenhua-Wei.github.io` under your GitHub account `Wenhua-Wei`.
2. Upload the **contents** of this folder to the repository root (the `index.html` file must be at the root, not within another subfolder).
3. In GitHub, open **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, and save.
4. Your website should appear at `https://wenhua-wei.github.io/` after GitHub Pages finishes deploying.

## Updating the website

- To edit the text, open `index.html` in VS Code or GitHub's editor.
- To replace the photo, overwrite `assets/profile.jpg` with a new image of the same filename.
- To change colors and spacing, edit the CSS variables and layout rules near the top of `style.css`.
- The original CV supplied by the user does not yet list the current Manchester PhD. Please update the public CV once it is ready.
- No phone number is shown on the site or public CV.
- All links and personal information should be checked before publishing.

This is plain HTML/CSS: no extra build tools, JavaScript, dependencies, analytics or cookie banners are required.
