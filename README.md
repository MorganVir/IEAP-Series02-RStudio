# IEAP-Series02-Rstudio — Correlations & Statistical Tests

**Author:** Morgan VIROLAN  
**Course:** MASTER IEAP - Series 02 (RStudio)  
**Last knit:** 02 Oct 2025  
**Report:** `IEAP-Series02-Rstudio.Rmd` → `IEAP-Series02-Rstudio.html`

## Overview
This assignment covers three main parts:
1. **Correlations & simple linear regression** on `NonUse.csv` (PANU, SANU, EENU).
2. **Paired pre/post analysis** on `PrePost.csv` with spaghetti plots and Wilcoxon signed-rank.
3. **Statistical tests (non-parametric)** on `snore.txt` (alcohol score 0–15, smoking, snoring, sex, anthropometrics).

The HTML report contains all code, outputs, figures, and short write-ups per section.

## Repository structure

├─ .gitattributes
├─ .gitignore
├─ IEAP-Series02-RStudio.Rproj
├─ IEAP-Series02-Rstudio.Rmd
├─ LICENSE
└─ README.md

## Data sources
- **NonUse.csv** - course-supplied upper-extremity non-use variables: PANU, SANU, EENU 
- **PrePost.csv** - course-supplied paired measurements (Before/After).
- **snore.txt** - course-supplied clinical/behavioral dataset

> If publishing publicly, clarify original sources (the university course and/or professor, see below) or remove raw data if redistribution is restricted.

**Packages:** `ggplot2`, `dplyr`, `tidyr`, `knitr`, `moments`, `scales` (plus base `stats`).

## Reproducibility
1. Open `IEAP-Series02-Rstudio.Rmd` in RStudio at the project root.  
2. Ensure working directory so `data/test_data/` resolves.  
3. Knit to produce `IEAP-Series02-Rstudio.html`. 

## Main references 

- Amrhein, V., Greenland, S., & McShane, B. (2019). Retire statistical significance. *Nature, 567*(7748), 305–307.
- Bruce, P., Bruce, A., & Gedeck, P. (2020). *Practical Statistics for Data Scientists: 50 Essential Concepts* (2nd ed.). O’Reilly Media.
- Dorey, F. (2011). Statistics in brief: Interpretation and use of p values: All p values are not equal. *Clinical Orthopaedics and Related Research, 469*(6), 1819–1821.
- Ghasemi, A., & Zahediasl, S. (2012). Normality tests for statistical analysis: A guide for non-parametric methods. *International Journal of Endocrinology and Metabolism, 10*(2), 486–489. https://doi.org/10.5812/ijem.3505
- Hambrecht, R., Walther, C., Möbius-Winkler, S., Gielen, S., Linke, A., Sabri, O., et al. (2004). Percutaneous coronary angioplasty compared with exercise training in patients with stable coronary artery disease: A randomized trial. *Circulation, 109*(11), 1374–1380. https://doi.org/10.1161/01.CIR.0000121360.31954.1F
- McDonald, J. H. (2014). *Handbook of Biological Statistics* (3rd ed., p. 32). Sparky House Publishing. http://www.biostathandbook.com
- McNemar, Q. (1947). Note on the sampling error of the difference between correlated proportions or percentages. *Psychometrika, 12*(2), 153–157.
- Nahm, F. S. (2016). Nonparametric statistical tests for the continuous data: The basic concept and the practical use. *Korean Journal of Anesthesiology, 69*(1), 8–14. https://doi.org/10.4097/kjae.2016.69.1.8
- Razali, N. M., & Wah, Y. B. (2011). Power comparisons of Shapiro–Wilk, Kolmogorov–Smirnov, Lilliefors and Anderson–Darling tests. *Journal of Statistical Modeling and Analytics, 2*(1), 21–33.
- Shreffler, J., & Huecker, M. R. (2023). Type I and Type II errors and statistical power. In *StatPearls*. StatPearls Publishing. https://www.ncbi.nlm.nih.gov/books/NBK557530/
- UCLA: Statistical Consulting Group. (2024). FAQ: What are the differences between one-tailed and two-tailed tests? UCLA Institute for Digital Research and Education. Retrieved from https://stats.oarc.ucla.edu/other/mult-pkg/faq/general/faq-what-are-the-differences-between-one-tailed-and-two-tailed-tests/
- Weissgerber, T. L., Milic, N. M., Winham, S. J., & Garovic, V. D. (2016). Beyond bar and line graphs: Time for a new data presentation paradigm. *PLOS Biology, 14*(4). https://doi.org/10.1371/journal.pbio.1002128


**Original data:**  Denis Mottet for STAPS IEAP Montpellier (available at https://github.com/DenisMot).

**Template credit:** formatting ideas and license straight from **RStudio-for-HMS-Template** by Denis Mottet (available at https://github.com/DenisMot).
