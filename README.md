# PM2.5 and Dementia Risk: Interactive Flexdashboard

This interactive dashboard was developed for **Data 555** to examine the relationship between long-term PM2.5 exposure and cognitive decline in older adults. It visualizes results from a large longitudinal study, highlighting how air pollution may impact different cognitive domains.

## 🌐 Live Dashboard

🔗 [View Dashboard on GitHub Pages](https://its-kei.github.io/Data-555-PM2.5-Dementia-Dashboard/)

---

## 📊 Features

- **Age Distribution Explorer**  
  Filter participant age using an interactive slider and view real-time summary statistics and histograms.

- **Forest Plots for 5 Cognitive Tests**  
  Explore effect sizes (and 95% CIs) for PM2.5 exposure across:
  - Delay Recall
  - Recognition
  - Number Span
  - Multilingual Naming
  - Animal Fluency

- **Interactivity**  
  Built with `flexdashboard`, `plotly`, `DT`, and `crosstalk` to support exploratory data analysis through tooltips, sliders, and sortable tables.

---

## 📁 Project Files

```text
├── Index.Rmd            # Source code for dashboard
├── index.html           # Rendered dashboard (for GitHub Pages)
├── README.md            # Project description
└── data/
    └── Plots Final_LMM_results_all_exposures.xlsx
