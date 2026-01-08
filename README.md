# aggregated_connexin43

## Connexin43 Aggregation Analysis in Traumatic Brain Injury

This repository contains an analysis pipeline for quantifying **aggregated Connexin43 (Cx43)** gap junction proteins in a traumatic brain injury (TBI) mouse model.

Cx43 aggregation is analyzed across hemispheres and post-injury timepoints to characterize injury-induced pathological changes.

---

## Experimental Groups

- **Contralateral control hemisphere**
- **Ipsilateral control hemisphere**
- **Ipsilateral TBI — 1 day post-injury**
- **Ipsilateral TBI — 7 days post-injury**

---

## Key Findings

- **No baseline hemispheric difference**  
  Contralateral and ipsilateral control hemispheres show no significant difference in Cx43 aggregation  
  *(p = 0.21)*

- **Acute TBI-induced aggregation**  
  Significant increase in aggregated Cx43 at **1 day post-TBI** compared to controls  
  *(median ≈ 3.5 vs. 1–2, p < 0.01)*

- **Progressive accumulation over time**  
  Cx43 aggregation increases further by **7 days post-TBI**  
  *(median ≈ 18.0, p < 0.001)*

- **Large biological effect size**  
  Non-parametric effect sizes are large  
  *(Cliff’s δ ≈ −0.50 to −0.70)*, indicating a robust injury-associated phenotype

---

## Statistical Summary

- **Overall group effect:**  
  Kruskal–Wallis test  
  *H(3) = 61.54, p < 0.000001, η² = 0.30*

- **Pairwise comparisons:**  
  Mann–Whitney U tests with Holm correction

- **Rationale:**  
  All groups violated normality and homogeneity assumptions, justifying non-parametric analysis

---

## Repository Structure

- `cx43_analysis.ipynb` — full analysis pipeline  
- `detection_analysis.csv` — processed detection data  
- `statistical_output.txt` — statistical results  
- `aggregated_cx43_count.png` — publication-ready figure  

---

## Requirements

- Python ≥ 3.8  
- numpy  
- pandas  
- scipy  
- matplotlib  
- statsmodels  

---

## Usage

Run all cells in `cx43_analysis.ipynb`.  
The notebook reproduces all statistics and figures reported above.

---

## Citation

will be added later

If you use this analysis or code, please cite appropriately or contact the authors.
