# Exoplanets: Data Analysis

Exploratory data analysis of an exoplanets dataset (1013 planets with
planetary and stellar properties): cleaning, visualising and drawing
insights, followed by a short presentation of the findings.

## Context

Completed as a **timed, one-hour exam**, closed-book, with no internet,
documentation or external help, then presented live. The goal was to go from
raw dataset to clear findings quickly and independently.

## What the notebook covers

- Summary statistics and distributions of planet mass, radius, orbital
  period, orbital radius and stellar properties.
- Correlations between planetary and stellar features.
- A linear regression of star luminosity from the other features.
- A first look at classifying potentially habitable planets, with
  oversampling for the very rare positive class.

## Dataset

`exoplanets.csv` was provided by the course for the exam and is not public,
so it is not included in this repository. The notebook keeps the outputs of
the original run.

## Run it

```bash
pip install -r requirements.txt
jupyter notebook Data_analysis_report.ipynb
```

With the course file, set the path in the first cell (the notebook was run in
Google Colab, where it lived at `/content/exoplanets.csv`).

## Files

- `Data_analysis_report.ipynb`: the full analysis, with outputs.
- `Exoplanets Dataset Analysis Report.pdf`: written report.
- `requirements.txt`: Python packages.
