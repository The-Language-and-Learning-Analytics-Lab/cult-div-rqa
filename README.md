# Exploring Cultural Diversity and Collaborative Team Communication using RQA

---

## Description
This repository provides the codebase and analysis for studying the impact of cultural diversity on collaborative team communication using Recurrence Quantification Analysis (RQA). The project focuses on quantifying communication patterns in time-series data and exploring their relationship with cultural diversity.

---

## Directory Structure

└── ./
├── RQA Analysis.ipynb         # Notebook for RQA computations
├── Stat_test.nb.html          # Statistical test results in HTML format
├── Stat_test.Rmd              # R Markdown file for statistical analysis
├── tables and graphs.ipynb    # Visualization of RQA results

---

## Features
- **RQA Analysis**: Computes recurrence metrics such as recurrence rate, determinism, and laminarity.
- **Statistical Testing**: Implements Kruskal-Wallis and pairwise Wilcoxon rank-sum tests to examine group-level differences.
- **Visualization**: Generates recurrence plots and other visual representations of communication dynamics.

---

## Methodology
The analysis employs Recurrence Quantification Analysis (RQA) to characterize communication patterns, leveraging metrics such as:
- **Recurrence Rate (RR)**: The proportion of recurrent states in the time series.
- **Determinism (DET)**: The predictability and regularity of state sequences.
- **Laminarity (LAM)**: The extent of system trapping behavior, indicative of prolonged state persistence.

Statistical tests compare these metrics across groups with varying levels of cultural diversity.

---

## Results
The findings reveal distinct patterns in communication based on group diversity:
- **Higher recurrence rates and determinism** were observed in culturally diverse groups, indicating structured and predictable communication patterns.
- **Groups with lower cultural diversity** exhibited reduced complexity in their communication dynamics, reflected in lower recurrence metrics.
- Statistical tests showed significant differences between diverse and homogeneous groups across all measured recurrence metrics.

These results suggest that cultural diversity influences the structure and dynamics of team communication, impacting collaborative processes.

---

## Citation
If referencing this repository or the associated research, please cite:

Samadi, A., et al. (2024). Exploring Cultural Diversity and Collaborative Team Communication through a Dynamical Systems Lens. Proceedings of the Educational Data Mining Conference.

---

## Acknowledgments
This research was conducted as part of a study on team dynamics and cultural diversity in collaborative settings. The methods and analyses were supported by open-source tools and frameworks.

---

## License
This repository is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0). For details, see the [LICENSE](LICENSE) file.

Let me know if further adjustments are needed!
