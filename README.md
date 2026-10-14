# Academic website

A responsive, accessible static academic website for GitHub Pages. No installation or build step is required.

## Content and editing

Personalized from James Chirombo’s supplied CV. `index.html` contains the biography, research interests, selected publications, supervision, funded projects, and contact links. `publications.html` contains the full publication list supplied in the CV; `cv.html` is a public academic CV that excludes phone numbers and referee contact details. Dates and appointments reflect the supplied document.

One citation (Kalonde et al., Communications Medicine 5, 227, 2025) has no title in the source CV; its supplied citation and DOI are retained without inventing a title. Review citations before publication.

Edit these HTML files to update content. Styles are in `styles.css`. The JC monogram can be replaced with a portrait when one is available. All files use relative paths and work without a build step.

## Preview locally

Run `python3 -m http.server 8000` in this folder, then open http://localhost:8000. Press Ctrl+C to stop the server. You can also open `index.html` directly.

## Publish on GitHub Pages

1. Create a repository named `jchirombo.github.io` in the `jchirombo` GitHub account (or use your own `<username>.github.io`). Public repositories support Pages on GitHub Free.
2. Upload `index.html`, `publications.html`, `cv.html`, `styles.css`, and `.nojekyll` into the repository root. Include any assets you added.
3. In **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/ (root)**, then save.
4. Once deployment completes, visit `https://jchirombo.github.io/`.

If using the GitHub CLI, authenticate with `gh auth login`, then initialize this folder and push to your newly created repository. Review the academic content before publishing.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
