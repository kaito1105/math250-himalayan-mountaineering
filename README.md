# Math 250 – Data Project: Himalayan Mountaineering

This repository contains the data project for **Math 250**, exploring the Himalayan Mountaineering Expeditions dataset featured in the [January 21, 2025 Tidy Tuesday challenge](https://github.com/rfordatascience/tidytuesday/blob/main/data/2025/2025-01-21/readme.md).

## Project Overview

This is an **exploratory** (not inferential) data analysis project connecting quantitative findings from the Himalayan mountaineering dataset to a broader human perspective — historical, cultural, or economic. The goal is to generate insight and hypotheses about Himalayan expeditions, not to test them statistically.

## Repository Structure

```
math250-himalayan-mountaineering/
├── data-project.Rproj   # RStudio project file
├── data-project.qmd        # Main Quarto document (write-up, code, visualizations)
├── data-project.html        # Rendered output
├── github_setup.R
└── README.md
```

## Required Elements

- **Central question/theme** — A specific question addressed from both a data-driven and a human (historical/cultural/economic) angle.
- **~400 words of narrative text** — Focused on insights about Himalayan mountaineering, not the coding process.
- **At least 2 citations** (beyond the data source) — Included as footnotes, with source reliability considered where relevant.
- **At least 2 visualizations** — Meaningful, accessible (colorblind-friendly, with alt-text), each addressing a specific question.
- **At least 1 numerical summary** — Typically via `group_by()` and `summarize()`.
- **One area of personal excellence** — Beyond baseline course techniques (e.g., an advanced visualization, deeper contextual analysis, harder data wrangling, or a new statistical idea).

## Tools & Technologies

- R / RStudio (organized as an RStudio Project)
- Quarto (`.qmd`) for the final document
- tidyverse (dplyr, ggplot2, etc.)

## Data Handling Notes

- The dataset is downloaded and written to `data/` **once** using `write_csv()`, then imported in the Quarto document like any other local dataset — no download code is included in the `.qmd` file itself.
- All code used for wrangling, visualization, and summarization is included in the final document; superfluous output (raw printouts, rough plots, messages) is omitted for readability.
- All warnings and errors are resolved prior to submission.

## Academic Integrity

This work is original and independently completed in accordance with course academic integrity policies. No AI text-generation tools were used to produce the written analysis.