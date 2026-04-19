GitHub repository: [cbt_data_analysis](https://github.com/JINWEIZHANGG/cbt_data_analysis)

# Temporal structure in weekly K time series

## Project overview

This project analyses weekly K time series from six participants in order to examine whether the observed dynamics are more structured than expected by chance.

The main question is whether participant-level K series show non-random temporal persistence across weeks. To address this question, the project combines visualisation, lag-1 autocorrelation, shuffled surrogate testing, and detrended fluctuation analysis (DFA).

The report was developed for the course **Python-R-Git** in the Master program at the Université de Montpellier.

## Main analyses

The project includes:

- visual inspection of weekly K trajectories
- lag-1 autocorrelation by participant
- shuffled surrogate comparison for lag-1 autocorrelation
- exploratory autocorrelation across multiple lags
- DFA and surrogate comparison for temporal scaling structure

## Repository structure

```text
.
├── readme.md
├── LICENCE
├── zhang.jinwei.html
├── main.Rmd
├── main.ipynb
├── main.Rproj
├── data/
│   └── cbtdata.xlsx
├── results/
│   ├── k_trajectories.png
│   ├── lag1_surrogate_plot.png
│   ├── lag1_surrogate_table.csv
│   ├── dfa_surrogate_plot.png
│   └── dfa_surrogate_table.csv
└── sources/