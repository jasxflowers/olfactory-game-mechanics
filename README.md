# Mechanics of Scent: Mapping Olfactory Play

This repository contains the data analysis code and supporting materials for the paper:

**Brooks, J., & Niedenthal, S. (2025). _Mechanics of Scent: Mapping Olfactory Play_.**

The project explores olfactory interaction in olfactory and non-olfactory games through the lens of game mechanics. It includes a structured dataset of over 500 games, statistical and cluster analyses, and visualizations of how scent-based mechanics differ across olfactory and non-olfactory games.

---

## 📁 Repository Structure

```bash
├── Cleaned_Olfactory_Analysis.ipynb  # Cleaned, publication-aligned analysis notebook
├── Data/
│   ├── olfactory_games.csv       # Dataset of olfactory games
│   ├── non_olfactory_games.csv   # Dataset of non-olfactory games
│   └── mechanics_matrix.csv      # Binary matrix of game-mechanic mappings
├── Plots/
│   ├── figure4_players_smells.png
│   ├── figure5_specificity_flexibility.png
│   ├── figure6_shannon_diversity.png
│   ├── figure7_per_game_diversity.png
│   └── pca_clusters.png
├── Tables/
│   ├── table1_top_smells.csv
│   ├── table2_mechanic_chisquare.csv
│   └── table3_cluster_summary.csv
└── README.md
```

---

## 🧪 Getting Started

To replicate the analysis:

1. Clone this repo.
2. Open `Cleaned_Olfactory_Analysis.ipynb` in Jupyter or VSCode.
3. Install required packages listed in the notebook header (e.g., `pandas`, `scikit-learn`, `matplotlib`, `scipy`).
4. Run the notebook to generate all figures and statistics used in the paper.

---

## 📊 Figures and Tables

All figures (e.g., violin plots, PCA cluster maps) and summary tables (e.g., top smells, chi-square tests) are saved under the `Plots/` and `Tables/` directories for easy reuse in slides, papers, and supplementary material.

---

## 📄 Citation

If you use this code, data, or figures, please cite the paper:

> Brooks, J., & Niedenthal, S. (2025). *Mechanics of Scent: Mapping Olfactory Play*.
> [not published yet]

---

## 📬 Contact

Questions, feedback, or interested in collaboration?

- Jas Brooks (jasbrooks@uchicago.edu)  
- Simon Niedenthal (simon.niedenthal@mau.se)

---

## 🧠 Acknowledgments

Acknowledgments here.