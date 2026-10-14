# Biomedical Science & Computational Biology Portfolio

Repository accompanying the academic portfolio of Haider Ali Iqbal: **[https://haiderali-iqbal.github.io/portfolio/](https://haiderali-iqbal.github.io/portfolio/)**

---

## Flagship Research Project
### Biological Sex Differences and the Limits of Human Endurance: A Bioinformatics Approach to Ultramarathon Data
* **Academic Context:** BSc (Hons) Biomedical Science Undergraduate Research Project (First-Class mark).
* **Supervisor:** Dr. Richard Bingham.
* **Techniques Involved:** Bioinformatics, R, Database mining.

#### Project Overview & Outline
This project aimed to enhance our understanding of the performance difference between the sexes when approaching the limits of human endurance. Utilising a publicly available dataset of individual finishing times of ultramarathon runners (exceeding 7 million rows, requiring R/RStudio rather than Excel), the analysis extracted data on sex, age, distance, and finishing time, with results discussed in the context of biochemical, hormonal, and physiological differences between males and females.

#### Data Sources & Provenance
1. **Ultramarathon Race Dataset:** Global race results exceeding 7 million rows. Records filtered for events >= 200 km with complete athlete average speed metrics.
2. **NHANES Reference Benchmarks:** Population health benchmark datasets examined for general lipid profile distributions (HDL, LDL, triglycerides, total cholesterol). *Note: Individual ultramarathon runners' biological samples were not linked or matched to race performance metrics.*

#### Analysis Workflow & Methods
* **Data Wrangling:** Ingestion, cleaning, column standardisation, and missing-value filtering performed in **R** using `tidyverse` and `dplyr`.
* **Statistical Testing:** Execution of Welch's t-tests and Principal Component Analysis (PCA) using `rstatix` and base R statistics.
* **Visualisation:** Publication-ready exploratory plots generated using `ggplot2`.

---

## Repository Structure
```text
portfolio/
├── index.html              # Main portfolio web page (HTML5 / Tailwind CSS)
├── Figure_2_PCA.png        # Principal Component Analysis visualisation graphic
└── README.md               # Project documentation and reproducibility guide
