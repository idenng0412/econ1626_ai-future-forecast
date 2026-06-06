# econ1626-ai-future-forecast

**AI and the Future of Global Logistics: Economic Transformation by 2030**

An interactive web essay for ECON1626 Assessment 3 by Thien Nhan Nguyen (S3972179).

This project presents a scenario-based forecast of how artificial intelligence may reshape global logistics by 2030. The central argument is that AI will generate significant productivity gains by improving forecasting, automation, and coordination, but that those gains will be distributed unevenly across firms, workers, and economies. Whether AI-driven logistics becomes broadly inclusive or increasingly concentrated will therefore depend on policy choices rather than on technology alone.

## Live site

Published with GitHub Pages: https://idenng0412.github.io/econ1626-ai-future-forecast/

## Repository contents

| File | Description |
| --- | --- |
| `forecast.html` | The interactive web essay. Open this file in a browser to view the project. |
| `styles.css` | Site layout and visual styling: navigation, hero, content cards, and sections. |
| `main-chart.js` | Supporting JavaScript loaded by the essay. |
| `README.md` | This file: project overview, navigation, publishing notes, and AI-tooling disclosure. |


## Essay structure

1. **Thesis** — the central claim: AI creates large productivity gains, but those gains are unevenly shared.
2. **Capabilities and economic channels** — three causal mechanisms:
   - predictive analytics and firm-level concentration;
   - warehouse automation and the productivity–wage gap;
   - AI coordination and the geography of trade.
3. **Interactive scenario simulator** — three sliders model diffusion, worker reabsorption, and policy strength; four outcome metrics update live and the pathway is classified as baseline, upside, or downside.
4. **Scenario forecasts** — baseline, upside, and downside futures for global logistics by 2030.
5. **Policy playbook** — three policy levers and their economic rationale.
6. **Methods, data and limitations** — sources, assumptions, uncertainty, and AI-tooling disclosure.
7. **Conclusion and references** — closing synthesis and source attribution.

## Interactive and visual features

- **Scenario simulator** built with vanilla JavaScript: adjust diffusion, reabsorption, and policy strength to see how the outcomes change.
- **Live outcome metrics:** productivity, market concentration, labour income share, and developing-economy participation update dynamically.
- **Hand-coded SVG charts:** the data flywheel, the productivity–wage decoupling, and the reshoring trend. These are schematic and labelled as illustrative.
- **Scroll-reveal animation** as the reader moves through the essay.
- **Sticky navigation** between major sections.

## Technical notes

- No build step is required.
- No external JavaScript libraries are used.
- The site loads three files: `forecast.html`, `styles.css`, and `main-chart.js`. All three must be present in the repository for the site to render correctly.
- The site is designed to deploy directly through GitHub Pages.

## Running locally

No build step is needed. Either open `forecast.html` directly, or serve the folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000/forecast.html`.

## Publishing on GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Open the published GitHub Pages link.

## AI-tooling disclosure

Generative AI tools were used to support project planning, structure, drafting, coding assistance, editing, and visual design. The final argument, evidence selection, economic reasoning, policy judgement, and written submission were reviewed, revised, and approved by the author.

The full disclosure also appears in the **Methods, Data and Limitations** section of the web essay, in accordance with RMIT academic integrity and generative-AI guidance.

## Assessment context

Created for ECON1626 Assessment 3. The project demonstrates economic analysis of AI adoption, scenario-based forecasting, policy and governance evaluation, interactive web communication, and reproducible deployment on GitHub Pages.
