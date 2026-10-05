# Recommendation Atlas

[Open the website](https://amanjaurhi97.github.io/recommendation-atlas/)

An interactive field guide to recommendation systems, created for product thinking about personalization and merchant offers.

- Netflix, Spotify, Meta, Google/YouTube, and Chase deep dives
- Fundamentals through advanced recommendation techniques
- Side-by-side system comparisons
- Synthetic eligibility, suppression, ranking, diversity, and exploration lab
- Six proposed Chase opportunity briefs, browser-local shortlisting, and Markdown export
- Fifteen primary-source links

Independent learning resource; not affiliated with or endorsed by JPMorgan Chase. No confidential information or customer data is included. Documented public systems are separated from educational examples and proposed applications. Research snapshot: 6 October 2026.

## Development

This site uses plain HTML, CSS, and JavaScript. No build or installation is required.

```sh
python -m http.server 8000 --directory dist
node --check dist/app.js
node --check dist/data.js
```

Source content is in `dist/data.js`; interactions are in `dist/app.js`. The decision lab uses invented, deterministic inputs, not a trained production model. Shortlists stay in browser local storage.

## Hosting

GitHub Pages deploys `dist/` automatically when changes reach `main`, through `.github/workflows/pages.yml`. In repository Settings → Pages, the build source is GitHub Actions.

For future research updates, review relevant primary sources, update dates, and preserve the distinction between documented systems and hypotheses. Do not assert an undisclosed internal Chase architecture.
