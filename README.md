# Spectral Analysis of Time Series in R

Final project for the course **Spectral Analysis in Economics and Finance**.

## Project Description

Spectral analysis of the **Monthly Industrial Production Index in Poland** (2000–2024) 
to identify hidden cycles and seasonality in economic data.

## Methods Applied

- Discrete Fourier Transform (DFT)
- Naive periodogram with confidence intervals
- Spectrum smoothing (Daniell window, Welch's method, averaging subperiods)
- Analysis of incomplete data (Lomb-Scargle periodogram)

## Contents

- `Projekt_zaliczeniowy_*.Rmd` – R Markdown source code

## Required Packages

```r
library(quantmod)
library(lomb)
```
