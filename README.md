# 2024 Paris Olympics Data Analysis and Interactive Dashboard

An exploratory analysis of athlete and medal data from the 2024 Paris Olympics, combining three datasets to examine athlete demographics, country participation, and the relationship between national GDP and Olympic performance.

The combined dataset includes athlete demographics, medallist records, and World Bank GDP data for the 2024 Paris Olympics, representing 11,000+ athletes across 200+ countries.

## Dashboard

An interactive dashboard was built to explore high-level athlete and medal data by country.

[View the interactive dashboard on Tableau Public](https://public.tableau.com/views/2024ParisOlympicsDashboard_17897907200160/ParisOlympic2024DataDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

> Statistical visuals (Python/seaborn/matplotlib) and GDP-related data are included in the notebook and presentation. The interactive dashboard, built separately in Tableau, focuses on athlete demographics and country-level breakdowns.

## Tools and Libraries

Python, pandas, numpy, matplotlib, seaborn, scipy, Tableau

## Analyses

- Descriptive statistics on athlete age, height, weight, and gender across all competing nations
- Comparisons between American and non-American athletes across demographic measures
- Country-level analysis of athlete participation and medal counts relative to GDP
- Sport-level breakdowns including gender distribution and age ranges by discipline
- A two-sample t-test comparing the ages of medalists and non-medalists

## Repository Contents

| File | Description |
|------|-------------|
| `2024_olympics_data.ipynb` | Jupyter Notebook with full analysis |
| `2024_olympics_data_cleaned.csv` | Merged and cleaned dataset |
| `2024_olympics_presentation.pdf` | Summary presentation of key findings |
