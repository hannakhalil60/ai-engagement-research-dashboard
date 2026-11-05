# AI Engagement & Measurement Reliability — Interactive Research Dashboard

**[Open the live interactive dashboard](https://hannakhalil60.github.io/ai-engagement-research-dashboard/)**  


## Overview

An interactive research presentation exploring a measurement pitfall: **a declining returning-user share does not necessarily mean fewer returning users**. The dashboard walks through the original case-study findings, competing explanations, a validation narrative, and an interactive *illustrative* denominator simulator.

## Explore

- **Research question and hypotheses:** What does a decline in returning-user share actually establish?
- **Evidence:** Four original case-study charts, with click-to-enlarge views.
- **Interactive simulator:** Adjust fictional new and returning user counts to see how a changing denominator affects the share.
- **Methods and limitations:** Distinguishes monthly aggregate returning-user share from user-level cohort retention; avoids causal claims.

## Data provenance and limitations

The project originated from an Arizona State University MBA group assignment using course-provided data for a fictional company. **The original CSV datasets are not included**, as redistribution permissions have not been confirmed. The original charts and summary statistics are derived from that coursework; verify permission before publicly publishing them. The interactive simulator uses **illustrative values**, not reconstructed original records. The original findings cannot be independently reproduced from this dashboard alone.

This is a research communication artifact, **not** a model-training or production ML system. The broader coursework included collaborative analysis; do not interpret this dashboard as evidence that every source finding was independently produced by one contributor.

## Run locally

Download `index.html` and open it in a modern browser. The HTML contains its chart images and does not need a Python server or external data files.

## Publish with GitHub Pages

1. Upload `index.html` and this `README.md` to the **root** of a public GitHub repository.
2. Go to **Settings → Pages → Build and deployment**.
3. Select **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
4. After deployment, open `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

**Publication reminder:** Confirm that public display of the original course-derived charts and summary findings is permitted before enabling GitHub Pages.
