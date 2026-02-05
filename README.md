


# 🌍 Mapping Global Power Through UN Voting

**An Interactive Analysis of United Nations General Assembly Voting (1946–2024)**

**Live report:** https://kchivukulagrid.github.io/Internship_project1/  · **Main entry point:** `index.html`

---

## 📖 Project Overview

This project analyzes United Nations General Assembly voting behavior over time to understand global power dynamics, ideological polarization, and alignment among major world powers. Rather than relying on static figures, the analysis is presented primarily through interactive HTML visualizations, enabling clearer interpretation and more effective presentation.

The work culminates in a web-based narrative dashboard; `index.html` is the central entry point for exploring all results.


## ❓ Research Questions

### Main Research Question

- How have global voting alignments and ideological divisions in the UN evolved from 1946 to the present?

### Sub-Questions

- How polarized has UN voting been across different historical periods?
- How closely do major powers align with the United States over time?
- How do major powers align with one another across decades?
- How has global voting cohesion changed in the post–Cold War era?


## 📂 Repository Structure

```
/ (project root)
├── data/                      
│   ├── AgreementScores.csv
│   ├── AgreementScoresAll_Jun2024.csv
│   └── IdealpointestimatesAll_Jun2024.csv
│
├── plots/                     
│   ├── ideological_composition_interactive.html
│   ├── modern_3d_surface.html
│   ├── modern_animated_scatter.html
│   ├── modern_globe_2023.html
│   ├── modern_parallel_coords.html
│   ├── modern_polar_heatmap.html
│   ├── modern_racing_bars.html
│   ├── modern_sankey.html
│   ├── modern_sunburst.html
│   ├── modern_violins.html
│   ├── persistence_extremeness_interactive.html
│   ├── UN_voting_2023_interactive.html
│   ├── voting_alignment_heatmap_interactive.html
│   ├── voting_alignment_with_US_interactive.html
│   └── voting_Polarization_interactive.html
│
├── notebooks/
│   └── Chaitu_project.ipynb
│
├── index.html                 
└── README.md                  
```


## 📊 Data Source

**United Nations General Assembly Voting Data (1946–2024)**

The dataset contains country-level voting decisions (Yes, No, Abstain) across thousands of resolutions, enabling long-run analysis of ideological alignment, polarization, and geopolitical trends within the UN.


## 🔬 Methodology

- Data cleaning and preprocessing using Python
- Construction of voting alignment, dispersion, and polarization metrics
- Generation of interactive visualizations using Plotly and Bokeh
- Export of plots as standalone HTML files
- Integration of all visuals into a single narrative webpage (`index.html`)


## 📈 Key Insights

- UN voting behavior exhibits distinct historical phases, including the Cold War, post–Cold War transition, and a contemporary multipolar era.
- Major power alignments are dynamic and context-dependent rather than fixed.
- Interactive visualizations uncover patterns that are difficult to detect using raw data or static plots.
- Web-based storytelling significantly improves interpretability and analytical clarity.


## 🚀 How to View the Project

- Clone the repository
- Open `index.html` in any modern web browser
- Explore the interactive visualizations in the `plots/` folder

> **Note:** No Python execution is required to view the final results.


## 📋 Requirements (for Reproducibility)

To reproduce the analysis and regenerate the visualizations:

- Python 3.8+
- pandas, numpy
- matplotlib, seaborn
- plotly, bokeh
- Jupyter Notebook


## 🧾 Summary

This project demonstrates how interactive, web-based data visualization can be used to analyze long-term international political behavior. By combining rigorous data preprocessing with modern visualization techniques, it provides a clear, engaging, and presentation-ready view of evolving global power structures within the United Nations.






