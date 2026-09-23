# DATA301/DATA471 — Assignment IV

Estimators for the Exponential rate (Monte Carlo comparison) and a time-series
analysis of the `ausbeer` data.

## Contents
- `assignment4.Rmd` — the full write-up and code (knit to PDF).
- `2026-Assignment-4.pdf` — the assignment brief.

## How to reproduce
1. Install R and the required package:
   ```r
   install.packages("fpp2")
   ```
2. Knit the document (needs a LaTeX engine for PDF; `tinytex::install_tinytex()`
   if you don't have one):
   ```r
   rmarkdown::render("assignment4.Rmd")
   ```

The analysis is reproducible: a fixed seed (`set.seed(301)`) is set at the top.
