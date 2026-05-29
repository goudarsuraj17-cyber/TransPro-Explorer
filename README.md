# TransPro-Explorer
Interactive transcriptome–proteome correlation analysis dashboard for multi-omics data exploration and visualization.

# TransPro Explorer

Interactive Transcriptome–Proteome Correlation Analysis Dashboard

## Overview

TransPro Explorer is a lightweight web-based bioinformatics dashboard designed for transcriptome–proteome integration and exploratory multi-omics analysis.

The platform enables researchers to investigate RNA–protein relationships through Pearson correlation analysis, quadrant classification, interactive visualization, and gene-level exploration.

---

## Features

### Transcriptome–Proteome Integration

* RNA vs Protein abundance visualization
* Interactive scatter plot exploration
* Gene-level inspection

### Quadrant Classification

* Q1: High RNA / High Protein
* Q2: Low RNA / High Protein
* Q3: High RNA / Low Protein
* Q4: Low RNA / Low Protein

### Correlation Analysis

* Pearson correlation coefficient distribution
* Median correlation reporting
* Positive and negative concordance assessment

### Interactive Dashboard

* Dynamic filtering
* Gene search
* Hover tooltips
* Summary statistics
* Responsive visualization

---

## Technologies

* HTML5
* CSS3
* JavaScript
* Canvas API
* PapaParse

---

## Screenshots

### Dashboard Home

![Home](screenshots/dashboard_home.png)

### Dashboard Overview

![Dashboard](screenshots/dashboard_overview.png)

### Quadrant Analysis

![Quadrant](screenshots/quadrant_analysis.png)

### Correlation Distribution

![Histogram](screenshots/pearson_distribution.png)

---

## Input Format

Required columns:

```csv
GeneSymbol
mean_log2_TPM
mean_log2_RFU
pearson_r
pvalue
Quadrant
```

---

## Usage

Open the dashboard in any modern browser.

```bash
firefox transpro-explorer.html
```

or

```bash
google-chrome transpro-explorer.html
```

No installation required.

---

## Author

Suraj Manjunath Goudar

Bioinformatics Research Intern
