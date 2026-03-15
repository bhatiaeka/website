# About Me — Website Project

A personal multi-page website built with HTML and custom CSS for a web development assignment (DS4200 Homework 7).

## Contents

- **Home** (`index.html`) — About me: intro, photo, and link to fencing page
- **Fencing** (`learn-more.html`) — My hobby: fencing, with descriptive text, image, and list of the three weapons
- **Contact** — Footer on every page with email and social links
- **Styles** (`styles.css`) — Custom typography, color scheme, and layout

## Styling & Customization

- **Custom fonts:** Cormorant Garamond (headings) and Source Sans 3 (body) via Google Fonts
- **Color scheme:** Warm browns (#3d2e1a, #8b6914) and cream background (#faf6f1)
- **Layout:** Max-width containers, consistent padding and margins, responsive spacing

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `my-website` or `about-me-website`).

2. Initialize git in this folder and push your code:
   ```bash
   cd website-project
   git init
   git add .
   git commit -m "Initial commit: multi-page website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**.
   - Under **Source**, choose **Deploy from a branch**.
   - Branch: **main** (or **master**).
   - Folder: **/ (root)**.
   - Click **Save**.

4. After a minute or two, your site will be live at:
   `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

5. **Verify:** Open the URL and check that:
   - The Home and Fencing pages load.
   - Navigation links work between pages.
   - The contact links and image display correctly.

6. Submit the GitHub Pages URL (e.g. `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`) as required.

## Updating Contact Information

Edit the **Contact** section in both `index.html` and `learn-more.html`:

- Replace `your.email@example.com` with your real email.
- Replace `https://linkedin.com` and `https://github.com` with your actual profile URLs.
