# Modeldrop

Four English static pages tracking reported model availability as of October 6, 2026. Open `index.html` directly in a browser. All navigation and the shared `style.css` use relative paths, so the site works from local files and under `/modeldrop/`. No JavaScript, framework, backend, images, external fonts, dependencies, installation or build command is required.

## GitHub Pages

Create a public repository named `modeldrop` under your GitHub username and put `index.html`, `mistral-large-4.html`, `reflection-beam.html`, `gemini-4-argon.html`, `style.css` and this README at the root of its `main` branch. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then save. Leave the custom domain empty. GitHub publishes the files at `https://USERNAME.github.io/modeldrop/`; for the selected account, the address is `https://19960705.github.io/modeldrop/`. There is no local build step or custom workflow to configure. GitHub's own Pages publishing job may take a few minutes.

## Editorial status and updates

The model claims and requested footer wording follow the supplied October 6 editorial brief. Google's official September 30 Argon announcement was retrieved through the research tool and confirms a phased rollout to trusted cyber defenders. It also publishes pricing and benchmark figures; those numbers are deliberately omitted as requested, and the comparison section does not falsely label them unpublished. The current public API status has not been independently checked against the live model catalog. The Mistral news URL and both X source URLs timed out; Mistral and Reflection details remain attributed to the supplied brief, with a verification note on each page. The requested “Facts checked 2026-10-06” footer records the brief's stated date and does not establish that every claim has been independently verified.

Updates are manual. Edit the affected page and homepage card, add a dated changelog entry, and update the footer only after checking the facts. Keep planned releases distinct from releases that have happened. Preserve `Not published` for unknown information; do not infer specifications or benchmark scores. Push the edited files to `main` to republish. There is no automatic polling, signup form or notification system.
