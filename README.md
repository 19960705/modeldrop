# Modeldrop

Four English static pages tracking reported model availability as of October 6, 2026. Open `index.html` directly in a browser. All navigation and the shared `style.css` use relative paths, so the site works from local files and under `/modeldrop/`. No JavaScript, framework, backend, images, external fonts, dependencies, installation or build command is required.

## GitHub Pages

Create a public repository named `modeldrop` under your GitHub username and put `index.html`, `mistral-large-4.html`, `reflection-beam.html`, `gemini-4-argon.html`, `style.css` `sitemap.xml` and this README at the root of its `main` branch. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then save. Leave the custom domain empty. GitHub publishes the files at `https://USERNAME.github.io/modeldrop/`; for the selected account, the address is `https://19960705.github.io/modeldrop/`. There is no local build step or custom workflow to configure. GitHub's own Pages publishing job may take a few minutes.

## Editorial status and updates

The model claims and requested footer wording follow the supplied October 6 editorial brief. Google's official September 30 Argon announcement was retrieved through the research tool and confirms a phased rollout to trusted cyber defenders. It also publishes pricing and benchmark figures; those numbers are deliberately omitted as requested, and the comparison section does not falsely label them unpublished. The current public API status has not been independently checked against the live model catalog. The Mistral news URL and both X source URLs timed out; Mistral and Reflection details remain attributed to the supplied brief, with a verification note on each page. The requested “Facts checked 2026-10-06” footer records the brief's stated date and does not establish that every claim has been independently verified.

Updates are manual. Edit the affected page and homepage card, add a dated changelog entry, and update the footer only after checking the facts. Keep planned releases distinct from releases that have happened. Preserve `Not published` for unknown information; do not infer specifications or benchmark scores. Push the edited files to `main` to republish. There is no automatic polling, signup form or notification system.


## Search setup and measurement

This is an English model-availability content site. Its job is to answer whether each model is usable today and where to check access or release details. The existing four-page scope stays unchanged. Analytics JavaScript is intentionally absent; use Search Console for Google Search impressions, clicks, queries and indexing status. Search Console does not measure all visits or outbound clicks.

| Page | Query focus | Reader question |
| --- | --- | --- |
| Home | new model status | Which of these three models can I use? |
| Mistral Large 4 | mistral large 4 api; le chonk model; mistral large 4 open weights | Is the API open, what is the reported price, and when are weights planned? |
| Reflection Beam | reflection beam; reflection beam weights | Have the weights been released? |
| Gemini 4 Argon | gemini 4 argon; gemini 4 argon access | Is access limited or generally available? |

These are query hypotheses based on page intent, not measured search volumes or proven low-competition keywords. No ranking, traffic or Google Trends growth is claimed.

Use the Search Console **URL-prefix** property `https://19960705.github.io/modeldrop/`. Verify with the public HTML meta tag in `index.html`; keep that tag after verification. Submit `https://19960705.github.io/modeldrop/sitemap.xml` in **Sitemaps**. The sitemap contains only the four canonical page URLs. Every page has a canonical URL; the home page canonical is the trailing-slash URL, so `/index.html` and `/` are not intentionally targeted as separate pages. Canonical tags are hints, not guarantees.

Do not put a `robots.txt` inside `/modeldrop/`: Google reads it at the host root `/robots.txt`. This project does not modify the host-level site or other repositories. A missing robots file does not itself block crawling.

After publishing, inspect the four canonical URLs in Search Console. An ownership verification, successful sitemap submission or successful live test does not mean a page is indexed. Request indexing only after the live URL is accessible, then check Google's reported index status. Google decides when and whether to index.

Review Search Console after sufficient data has accumulated, initially after about 7 days and then weekly. Filter to this property and compare page/query impressions and clicks. If Google cannot fetch a page, fix that first. If pages are indexed but impressions remain sparse, inspect actual query results and demand before expanding. If impressions appear without clicks, check whether titles and status summaries match those queries. Keep facts current. Do not add languages, functions or more model pages without evidence and a scope decision. No automatic monitoring is configured.

For promotion, first verify the model claims and prepare a useful, accurate description for a relevant community. Posting destinations and messages require separate selection and authorization; no backlinks or social posts are created by this repository.
