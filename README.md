# econ1626-ai-future-forecast

## AI and the Future of Global Logistics: Economic Transformation by 2030

An interactive web essay for **ECON1626 Assessment 3** by **Thien Nhan Nguyen (S3972179)**.

This project presents a scenario-based forecast of how artificial intelligence may reshape global logistics by 2030. The central argument is that AI will generate significant productivity gains by improving forecasting, automation, and coordination, but those gains will be distributed unevenly across firms, workers, and economies. The forecast therefore argues that policy choices, rather than technology alone, will determine whether AI-driven logistics becomes broadly inclusive or increasingly concentrated.

## Live Site

Published with GitHub Pages:

https://idenng0412.github.io/econ1626-ai-future-forecast/

## Repository Navigation

| File | Description |
| --- | --- |
| `forecast.html` | The main interactive web essay. Open this file in a browser to view the project locally. |
| `styles.css` | External stylesheet for layout, typography, and component styling used by `forecast.html`. |
| `main-chart.js` | External JavaScript file loaded by `forecast.html` for supplementary chart animation logic. |
| `index.html` | Redirect shim (`<meta http-equiv="refresh">`) that forwards GitHub Pages visitors to `forecast.html`. |
| `README.md` | Project overview, repository guide, publishing notes, and AI-tooling disclosure. |

## Essay Structure

1. **Thesis** — introduces the central claim: AI creates large productivity gains, but those gains are unevenly shared.
2. **Capabilities → Economic Channels** — explains three causal mechanisms:
   - predictive analytics and firm-level concentration;
   - warehouse automation and the productivity–wage gap;
   - AI coordination and the geography of trade.
3. **Interactive Scenario Simulator** — uses three sliders to model diffusion, worker reabsorption, and policy strength. The simulator updates four outcome metrics and classifies the pathway as baseline, upside, or downside.
4. **Scenario Forecasts** — develops baseline, upside, and downside futures for global logistics by 2030.
5. **Policy Playbook** — presents three policy levers in a summary table, then lets readers toggle each policy on and off to see how the combination affects a radar chart (concentration mitigation, displacement mitigation, global integration) and three live outcome indicators (concentration risk, displacement rate, developing economy inclusion).
6. **Methods, Data and Limitations** — outlines sources, assumptions, uncertainty, and AI-tooling disclosure.
7. **Conclusion and References** — summarises the forecast and provides source attribution.

## Interactive and Visual Features

- **Scenario simulator:** built with vanilla JavaScript. Users can adjust diffusion, worker reabsorption, and policy strength to see how outcomes change.
- **Live outcome metrics:** productivity, market concentration, labour income share, and developing-economy participation update dynamically.
- **Fig. 1 — Firm efficiency and market capture:** interactive SVG with a Data Scale slider. Two diverging curves show enterprise and small-firm efficiency over 2026–2030; a live pie chart shows how market capture shifts as data scale grows.
- **Fig. 2 — Productivity–wage decoupling:** interactive SVG with Warehouse Automation and Labour Displacement sliders that reshape the output-per-worker and labour-income curves in real time.
- **Fig. 3 — Reshoring and global supply chain geography:** a canvas-based pixel world map (90 × 45 grid, 4° per cell). A Logistics Optimisation slider progressively highlights developing economies in red — starting from the weakest economies and ending with the largest — as rising efficiency reduces their labour-cost advantage.
- **Policy radar and outcome bars:** three toggle buttons (one per policy lever) update a spider chart showing combined policy coverage across three axes, alongside live outcome bars for concentration risk, displacement rate, and developing economy inclusion.
- **Scroll-reveal animation:** sections appear dynamically as the reader moves through the essay.
- **Sticky navigation:** allows readers to move easily between major sections.

## Technical Notes

This project uses a single-file website design.

- No build step is required.
- No external JavaScript libraries are used.
- CSS, JavaScript, charts, and interactive elements are contained inside `forecast.html`.
- The website is designed to render directly through GitHub Pages.

## Publishing on GitHub Pages

To publish the site:

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/root` folder.
5. Open the published GitHub Pages link.

## AI-Tooling Disclosure

Generative AI tools were used to support project planning, structure, drafting, coding assistance, editing, and visual design. The final argument, evidence selection, economic reasoning, policy judgement, and written submission were reviewed, revised, and approved by the author.

The full AI-use disclosure is also included in the **Methods, Data and Limitations** section of the web essay, in accordance with RMIT academic integrity and generative-AI guidance.

## Assessment Context

This repository was created for **ECON1626 Assessment 3**. The project demonstrates:

- economic analysis of AI adoption;
- scenario-based forecasting;
- policy and governance evaluation;
- interactive web communication;
- GitHub Pages deployment and reproducible project structure.