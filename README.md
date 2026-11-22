# Orbia project page

An English-language introduction to [Orbia](https://github.com/Ranitzky/orbia), a self-hosted keyboard launcher and bookmark library. The page uses static HTML and CSS, with no JavaScript, build step, external fonts, or login. The dashboard screenshot loads lazily. The JetBrains Mono license is included in `assets/OFL.txt`.

## Preview locally

Open `index.html` in a browser or run `python3 -m http.server 8000` from the repository root and visit `http://localhost:8000`.

## Publish on GitHub Pages

Replace the contact email placeholder in `privacy-notice.html` before publishing. The privacy notice links to the legal notice for the operator's name and postal address.

Push the files to your GitHub repository. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select the branch containing this page and **/ (root)**, then save. GitHub displays the site URL after deployment. Local asset paths are relative so the page also works under a repository subpath.
