# Statistical Inference — Coursework

Homework, the course project, lecture slides and exams from **Statistical
Inference** (Dr. Behnam Bahrak, Spring 2024 / 1402-2). Each homework folder has
the assignment, my solution notebook and any course-provided data.

## Homework and project

| Folder | Topic |
|---|---|
| [`HW1`](HW1) | Study design, confounding, sampling methods; exploring `diamonds` |
| [`HW2`](HW2) | Probability, conditional probability and independence; distributions (`heart`) |
| [`HW3`](HW3) | Confidence intervals for means (Galton's heights) |
| [`HW4`](HW4) | Bootstrapping, paired tests, comparing two means and ANOVA (`diet`) |
| [`HW5`](HW5) | Inference for proportions, two-way tables |
| [`HW6`](HW6) | Linear regression and its diagnostics (`prostate`, `uswages`) |
| [`Project`](Project) | Two-phase project on the FiveThirtyEight *non-voters* survey: EDA, confidence intervals, hypothesis tests (theoretical and simulation-based) and regression |

## Lecture slides

[`slides/`](slides) — 22 decks, numbered by session:

| | | |
|---|---|---|
| 01 Introduction to data | 14 Comparing two means | 21 Introduction to linear regression |
| 02 Probability | 15 ANOVA | 22 Conditions for linear regression |
| 09 Central limit theorem | 16 Multiple comparisons and bootstrapping | 23 Hypothesis testing for linear regression |
| 10 Confidence intervals | 17 Inference for a proportion | 24 Multiple linear regression |
| 11 Hypothesis testing | 18 Comparing two proportions | 25–26 Collinearity and model selection |
| 12 Types of error | 19 Small-sample proportions | 27 Logistic regression |
| 13 The t-distribution | 20 Goodness-of-fit and independence tests | 28–29 Hypothesis testing for logistic regression |
| | | 30 Nonparametric tests |

[`exams/`](exams) — a sample final and the 2024 final with solutions.

## Datasets

The public datasets used in the homework are not stored here. Download them and
place each file, under the name shown, in the folder of the notebook that uses it.

| File expected | Used in | Source |
|---|---|---|
| `diamonds.csv` | HW1 | `diamonds` from ggplot2 — [docs](https://ggplot2.tidyverse.org/reference/diamonds.html) |
| `heart.csv` | HW2 | Heart Disease (Cleveland), UCI — [link](https://archive.ics.uci.edu/dataset/45/heart+disease) |
| `Galton.txt` | HW3 | Galton's family heights — [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/T0HSJ1), also `HistData::GaltonFamilies` ([docs](https://vincentarelbundock.github.io/Rdatasets/doc/HistData/GaltonFamilies.html)) |
| `diet.csv` | HW4 | Diet and weight loss (University of Sheffield) — `WRS2::diet` ([docs](https://search.r-project.org/CRAN/refmans/WRS2/html/diet.html)) |
| `prostate.csv` | HW6 | Prostate cancer data from *The Elements of Statistical Learning* — [data](https://hastie.su.domains/ElemStatLearn/datasets/prostate.data) |
| `uswages.csv` | HW6 | `uswages` from the R package [faraway](https://cran.r-project.org/package=faraway) |
| `nonvoters_data.csv`, `nonvoters_codebook.pdf` | Project | FiveThirtyEight *non-voters* — [data and codebook](https://github.com/fivethirtyeight/data/tree/master/non-voters) |

`Project/modified_nonvoters_data.csv` is my cleaned version and is kept here.

## Textbooks

- D. Diez, M. Çetinkaya-Rundel, C. Barr — *OpenIntro Statistics*, 4th ed., 2019 — free at [openintro.org](https://www.openintro.org/book/os/)
- R. L. Ott, M. Longnecker — *An Introduction to Statistical Methods and Data Analysis*, Cengage
