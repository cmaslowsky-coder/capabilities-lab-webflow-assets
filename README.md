The Capabilities Lab Website Package
This package contains a static, production-oriented single-page website for The Capabilities Lab. It is designed to be hosted through GitHub Pages and referenced from Webflow, or deployed as a standalone HTML/CSS/JS site.
The design uses the provided logo/brand texture and includes procedural placeholder jungle imagery. For final launch, replace the placeholder jungle assets with final photorealistic images generated from the prompts in `assets/image-prompts.md`.
File Structure
```text
/index.html
/styles.css
/script.js
/README.md
/assets/
  logo.png
  logo-white.png
  logo-mark.png
  favicon.png
  texture-shape.png
  jungle-hero.webp
  jungle-canopy-layer.webp
  jungle-midground-layer.webp
  jungle-foreground-ferns.webp
  jungle-mist-layer.png
  gorilla-silhouette.webp
  section-clearing.webp
  botanical-pattern-overlay.png
  image-prompts.md
```
1. Upload This Project to GitHub
Create a new GitHub repository. A good name would be `capabilities-lab-site` or `capabilities-lab-webflow-assets`.
Download and unzip this package.
Upload all files and folders to the repository root. Do not place the files inside an extra nested folder unless you intentionally want that in the URL.
Confirm the repository root contains:
`index.html`
`styles.css`
`script.js`
`assets/`
Commit the changes to the main branch.
2. Enable GitHub Pages
Open the GitHub repository.
Go to Settings.
In the left menu, select Pages.
Under Build and deployment, choose:
Source: Deploy from a branch
Branch: main
Folder: /root
Click Save.
Wait one to three minutes for the site to publish.
GitHub will show a URL similar to:
```text
https://YOUR-USERNAME.github.io/capabilities-lab-site/
```
Open that URL and confirm the site loads.
3. Reference Hosted CSS and JS Inside Webflow
After GitHub Pages is active, your hosted files will be available at URLs like:
```text
https://YOUR-USERNAME.github.io/capabilities-lab-site/styles.css
https://YOUR-USERNAME.github.io/capabilities-lab-site/script.js
```
In Webflow:
Open your Webflow project.
Go to Site settings or Page settings, depending on whether you want this code globally or only on one page.
In the Custom Code head area, paste:
```html
<link rel="stylesheet" href="https://YOUR-USERNAME.github.io/capabilities-lab-site/styles.css">
```
In the Before `</body>` tag area, paste:
```html
<script src="https://YOUR-USERNAME.github.io/capabilities-lab-site/script.js"></script>
```
Publish the Webflow site.
Test the page in an incognito/private browser window.
4. Webflow Integration Option
You have two practical options.
Option A: Embed the Whole Static Page
Use this option if you want the fastest path.
Host the full project on GitHub Pages.
In Webflow, add an Embed element to a blank page.
Paste the relevant body HTML from `index.html`, starting after the `<body>` tag and ending before the script tag.
Add the CSS link in the Webflow custom code head:
```html
<link rel="stylesheet" href="YOUR_GITHUB_PAGES_URL/styles.css">
```
Add the JS file before body close:
```html
<script src="YOUR_GITHUB_PAGES_URL/script.js"></script>
```
Publish Webflow and test.
Option B: Rebuild Sections Natively in Webflow
Use this option if you want full Webflow editing control.
Recreate each section in Webflow using the same class names from `index.html`.
Preserve the main class names such as:
`hero-section`
`section-heading`
`problem-card`
`engagement-card`
`outcomes-grid`
`contact-panel`
Reference the hosted CSS and JS files from GitHub Pages.
Replace static form behavior with Webflow Forms or HubSpot embed code.
Publish and test.
5. Replace Placeholder Assets with Final Exported Images
The current package includes usable placeholder assets so the site renders immediately. For the final site, generate or create final imagery using the prompts in:
```text
assets/image-prompts.md
```
Replace the files in `/assets/` using the exact same filenames:
```text
jungle-hero.webp
jungle-canopy-layer.webp
jungle-midground-layer.webp
jungle-foreground-ferns.webp
jungle-mist-layer.png
gorilla-silhouette.webp
section-clearing.webp
botanical-pattern-overlay.png
```
Recommended export settings:
Use `.webp` for full-background images.
Use transparent `.png` for mist and overlay assets.
Keep background assets under roughly 500 KB to 1.5 MB when possible.
Compress images before uploading to GitHub.
Preserve transparency for foreground foliage, mist, and overlays.
6. Troubleshoot 404 Errors from GitHub Pages
A 404 usually means one of these is true:
GitHub Pages has not finished publishing yet. Wait a few minutes and refresh.
The repository name is wrong in the URL. Use the exact URL shown under Settings → Pages.
The file is not in the root. `styles.css`, `script.js`, and `index.html` should be in the repository root.
The asset path is wrong. The project expects files inside `/assets/` with exact filenames.
Case sensitivity matters. `Logo.png` and `logo.png` are different paths on GitHub Pages.
The branch or folder setting is wrong. GitHub Pages should point to `main` and `/root`.
The repository is private on an account that does not support Pages for private repos. Make the repository public or verify your GitHub plan supports private Pages.
A quick test is to open these URLs directly:
```text
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/styles.css
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/script.js
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/assets/logo.png
```
If a direct file URL returns 404, fix the GitHub file location or URL before troubleshooting Webflow.
7. Update Links and Contact Information
Before publishing publicly, update these placeholders in `index.html`:
`hello@yourdomain.com`
LinkedIn URL
Newsletter signup path or form integration
Open Graph image path, if you create a custom social sharing image
Also verify the statistic in the Premise section before final launch. A code comment has been included in `index.html` as a reminder.
Production Notes
The site uses semantic HTML5, CSS variables, responsive layouts, accessible contrast, keyboard-accessible navigation, and reduced-motion support.
No heavy framework or external CDN dependency is required.
The newsletter form is a front-end placeholder. Connect it to Webflow Forms, HubSpot, Mailchimp, or another CRM before launch.
The visual system is intentionally cinematic and image-rich. Final image quality will determine the full premium effect.
The logo assets were derived from the provided brand images and exported into the required asset names.
Local Preview
You can open `index.html` directly in a browser, but a local server is better because it behaves more like GitHub Pages.
From the project folder, run:
```bash
python -m http.server 8000
```
Then open:
```text
http://localhost:8000
```
