# Netflix Content Analysis — Power BI Dashboard

An interactive Power BI dashboard exploring the Netflix catalogue, including content type, genre distribution, production countries and release-year trends.

## Dashboard Preview

<p align="center">
  <img src="Images/dashboard_preview.png" alt="Netflix content analysis Power BI dashboard" width="900">
</p>

## Business Questions

This dashboard is designed to help explore:

- What is the distribution of movies and TV shows?
- Which genres appear most frequently in the catalogue?
- Which countries are most represented?
- How does content volume vary by release year?
- How do catalogue patterns change when filtering by content type, country, genre or year?

## Dashboard Features

- Movie and TV show comparison.
- Country-level content distribution.
- Genre-level analysis.
- Release-year trend analysis.
- Interactive slicers for Type, Country, Genre and Release Year.

## Key Measures

The report uses DAX measures to calculate:

- Total Titles
- Total Movies
- Total TV Shows
- Movie and TV Show share of total titles

## Data Preparation

The source data was prepared before dashboard development. The documented preparation includes:

- Reviewing and cleaning the dataset.
- Handling missing values.
- Standardising country and genre fields.
- Creating calculated fields and measures for reporting.

**Dataset file:** `Data/Netflix_OneFile_Cleaned_Final.csv`

## Tools & Skills

| Tool | Use |
|---|---|
| Power BI | Interactive dashboard and reporting |
| DAX | KPI and calculation logic |
| Power Query | Data cleaning and transformation |
| CSV | Dataset storage |
| GitHub | Project documentation and version control |

## Repository Structure

```text
Netflix-PowerBI-Dashboard/
├── Data/
│   └── Netflix_OneFile_Cleaned_Final.csv
├── Images/
│   └── dashboard_preview.png
├── PowerBI/
└── README.md
```

## Interpretation Notes

This project describes patterns in the dataset used for the analysis. Catalogue counts and country or genre rankings should not be treated as a live representation of Netflix's current catalogue. Genre and country fields may contain multiple values per title, so category totals may overlap.

## Author

**Vaibhav Deshmukh**  
Aspiring Data Analyst | Power BI | SQL | Python

[GitHub Profile](https://github.com/vaibhavd8080)
