# Netflix Data Analysis

This repository contains a data exploration project analyzing Netflix historical content from 1925 through mid 2021. The goal is to identify trends in content production, genre popularity, ratings, and country-level distributions to support data-driven decisions about future programming strategy.

## Project overview

- Explore Netflix content metadata to understand how production has changed over time.
- Compare movies and TV shows by release year, genre, and production region.
- Identify missing data, perform basic cleaning, and visualize key patterns.
- Highlight country-specific trends and genre/rating distributions.

## Files

- `Nf_BS.ipynb` - main analysis notebook with data loading, overview, missing-value checks, outlier inspection, and initial insights.
- `Netflix.csv` - expected dataset file containing Netflix title metadata (not included in the repository).

## How to use

1. Place the Netflix dataset file `Netflix.csv` in the repository root.
2. Open `Nf_BS.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook cells to inspect the dataset, visualize trends, and review findings.

## Insights

The notebook focuses on:

- Data structure and basic statistics.
- Missing values and dataset completeness.
- Release-year distributions for movies and TV shows.
- Outlier detection in release years.
- Separate analysis paths for movies versus TV shows to support more meaningful insights.

## Notes

This analysis is meant for exploratory research and business intelligence on Netflix content strategy. The notebook is organized around problem definition, data inspection, and early hypothesis testing rather than a finalized predictive model.
