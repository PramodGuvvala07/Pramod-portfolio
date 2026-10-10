# Guvvala Pramod — Portfolio Website

A responsive, single-page portfolio made with plain HTML, CSS, and JavaScript. No framework or build step is required.

## Files
- `index.html` — page content and sections
- `style.css` — colours, layout, responsive styling
- `script.js` — mobile menu and current year in the footer

## Run it in VS Code (step by step)
1. Download and unzip `Pramod_Portfolio_Website.zip` to a folder you can find easily.
2. Install **Visual Studio Code** from https://code.visualstudio.com/ if you do not already have it.
3. Open VS Code. Choose **File → Open Folder…** and select the unzipped `pramod_portfolio` folder.
4. In the Explorer panel, check that `index.html`, `style.css`, and `script.js` are visible.
5. Install the **Live Server** extension:
   - Click the Extensions icon on the left (four squares), or press `Ctrl+Shift+X`.
   - Search for `Live Server` by Ritwick Dey and click **Install**.
6. Open `index.html`. Right-click inside the editor and choose **Open with Live Server**. Your browser should open the local website.
7. Edit text in `index.html`, save with `Ctrl+S`, and Live Server will refresh the page. Change colours and spacing in `style.css`; change interactions in `script.js`.
8. Test responsiveness: resize the browser or open developer tools with `F12` and enable a phone-sized viewport.
9. Before publishing, verify your contact details, correct any dates, and add links to GitHub repositories or live project demos if you have them.

## Personalise before publishing
- The resume lists the Vinsweb Solutions dates as `November 2025 - present`, which appears inconsistent. The portfolio therefore labels the period “2025 · Dates to confirm”. Please confirm the correct start and end dates.
- Your resume does not specify a job title for Vinsweb Solutions, so the site describes the work rather than inventing a title.
- The project cards currently link to an email asking about the project. Replace those links with actual GitHub/demo URLs when available.
- The site uses Google Fonts from the internet; if offline, it falls back to generic fonts.
- The phone and email are displayed publicly. Consider whether you want both visible before publishing.

## Publish it free with GitHub Pages
1. Create/sign in to a GitHub account at https://github.com/.
2. Create a new **public** repository, for example `pramod-portfolio`.
3. In VS Code, open the portfolio folder. Initialise Git and push the files using VS Code's Source Control panel, or follow GitHub's instructions for uploading files.
4. On GitHub, open the repository → **Settings** → **Pages**.
5. Under the build/deployment section, choose **Deploy from a branch**, select `main` and `/ (root)`, then click **Save**.
6. Wait for the deployment to finish. GitHub Pages will show the public website URL in the Pages section.
7. Open that URL on desktop and mobile to test it. If you update files later, commit and push the changes.

## Quick troubleshooting
- **CSS not showing:** make sure `style.css` is in the same folder as `index.html` and the filename matches exactly.
- **Menu not working:** check that `script.js` is in the same folder and the script tag is present near the end of the HTML.
- **Live Server option missing:** make sure the Live Server extension is installed, then reload VS Code.
- **Fonts look different:** Google Fonts requires an internet connection; the site still works offline with fallback fonts.
