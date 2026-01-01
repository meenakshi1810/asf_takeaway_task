# Household Survey Analysis

This repository contains the analysis of household survey data, including normalization of responses, composite index calculation, and insights generation.

---

## 📂 Contents
- **`code.ipynb`** – Jupyter Notebook with all code for data preprocessing, normalization, indicator calculation, and composite index calculation.  
- **`household_dataset.xlsx`** – Raw dataset containing household survey responses.  
- **`survey_results.xlsx`** – Processed dataset with normalized scores, indicators, and composite index.  
- **`report.pdf`** – Final report summarizing methodology, results, and insights.  

---

## ⚙️ Requirements
To run the notebook, you’ll need:
- Python 3.9+  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`
---

## 🚀 Usage
1. Download the files: `code.ipynb` and `household_dataset.xlsx`.  
2. Open the notebook and run all cells to reproduce the analysis.  
3. The notebook generates:  
   - **`survey_results.xlsx`** containing normalized scores, indicators, and composite index for each household.  
   - Descriptive statistics, correlation matrix, and identification of top/bottom households.  

---

## 📊 Key Insights
- Household conditions vary widely: some score near 1.0, others near 0.0.
- Education (school attendance) is consistently high, showing strong community value for schooling.
- Sanitation and clean cooking fuel are critical gaps — median scores are 0, meaning half of households lack access.
- The Composite Index highlights inequality, with a clear gap between top and bottom households.
- See report.pdf for full statistical summary and methodology.

---

## 📋 Quick Results Preview
| Household | Composite Index |
|-----------|-----------------|
| 3         | 1.000           |
| 6         | 1.000           |
| 15        | 1.000           |
| 24        | 1.000           |
| 21        | 1.000           |
| …         | …               |
| 8         | 0.025           |
| 17        | 0.025           |
| 14        | 0.050           |
| 5         | 0.050           |
| 23        | 0.050           |

---

## 📜 License
MIT

---
