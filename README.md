# Dipanjan Bera — Academic Website

A responsive, static academic website built with HTML, CSS, and a small amount of JavaScript. It is designed for free hosting with GitHub Pages.

## Files
- `index.html` — page content
- `style.css` — styling and responsive layout
- `script.js` — mobile menu and small navigation interactions

## Before publishing
1. Open `index.html`.
2. Replace the Google Scholar, GitHub, and LinkedIn `href="#"` values with your actual public profile URLs.
3. Add a preferred public email address if you want one shown.
4. Check all dates, titles, author roles, publication statuses, and links.
5. The resume you uploaded lists an IIT Hyderabad email and phone number. They are intentionally not published here; only add contact details you want visible to everyone.
6. The profile circle currently shows “DB”. To use a photo, put a file such as `assets/profile.jpg` in the project and replace the `portrait-placeholder` div with:
   `<img class="portrait-photo" src="assets/profile.jpg" alt="Dipanjan Bera">`
   Then add `.portrait-photo { width:190px; height:190px; object-fit:cover; border-radius:50%; }` to `style.css` (use `width/height:150px` in the mobile media query if desired).
7. Check that the conference acceptance and submitted-paper details are still accurate before publishing. Add public paper links only when you are sure they are accessible.

## Publish on GitHub Pages
1. Sign in to https://github.com/ or create an account.
2. Click **New repository**.
3. Repository name: `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
4. Choose **Public**, then create the repository.
5. Upload `index.html`, `style.css`, `script.js`, and this README to the repository root. Do not upload only the ZIP file.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Select branch `main` and folder `/ (root)`, then click **Save**.
9. Wait a few minutes and open `https://YOUR-USERNAME.github.io/`.
10. To update the site later, edit `index.html` or `style.css` on GitHub and commit the changes. Pages will rebuild automatically.

## Local preview (optional)
Double-click `index.html` to preview in your browser, or use the VS Code Live Server extension. The website does not need a backend or database.
