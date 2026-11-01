# Netflix Data Visualization with Microsoft Excel

Auspify Technologies – Data Visualization (Microsoft Excel) Internship
Author: Ahmed Amine Abdelli

All 6 tasks were completed on the Netflix titles dataset using Excel pivot tables, pivot charts, slicers and KPI formulas.

## Dataset

- Source file: `Dataset.csv` (8,790 rows, 10 columns)
- Cleaned workbook: `Netflix_Analyse.xlsx`

### Cleaning summary
- 4 duplicate records removed (same content, different `show_id`): 8,790 → **8,786** rows
- 2,588 "Not Given" directors and 287 "Not Given" countries replaced by "Unknown"
- `date_added` converted to a real date
- Columns added: `year_added`, `primary_country`, `duration_value`, `duration_unit`, `audience`

## Tasks

| Task | Level | Sheet | Content |
|---|---|---|---|
| 1 | Easy | `T1_Pivots` | Data cleaning, pivot tables (type, release year, rating), basic charts |
| 2 | Easy | `T2_Dashboard` | Movies vs TV Shows: pie chart, column chart, % share |
| 3 | Medium | `T3_Pays` | Top 10 countries ranking, slicer, top country highlighted |
| 4 | Medium | `T4_Tendances` | Release-year and year-added trends (line charts) |
| 5 | Advanced | `T5_Ratings` | Audience categories, KPIs, slicers (type, country) |
| 6 | Advanced | `T6_Dashboard` | Executive dashboard: KPIs, 4 charts, connected slicers, recommendations |

## Key findings

- **Catalogue mix:** 6,123 movies (69.7%) and 2,663 TV shows (30.3%).
- **Countries:** United States (3,240), India (1,056) and United Kingdom (638) account for about 56% of titles.
- **Release trend:** strong growth from 2015, with a peak of 1,144 titles released in 2018. TV shows grow longer than movies and outnumber them in 2021 releases (315 vs 277).
- **Additions to the catalogue:** from 82 titles in 2015 to a peak of 2,013 in 2019. 2021 data is incomplete.
- **Audience:** Adults 4,005 (45.6%), Teens/Family 3,793 (43.2%), Kids 906 (10.3%), Unclassified 82 (0.9%). Kids content is 17.4% of TV shows versus 7.2% of movies.

## Recommendations

1. Keep investing in TV shows, which keep growing and overtake movies in 2021 releases.
2. Reduce geographic dependence on the US, India and the UK; develop other countries.
3. Strengthen the kids offer (only about 10% of the catalogue).
4. Favour quality over volume: additions have plateaued since the 2019 peak.

## Repository structure

```
Auspify_Excel/
├── Netflix_Analyse.xlsx
├── Dataset.csv
├── Rapport_Auspify_Excel.pdf
├── Task1/   (screenshots)
├── Task2/
├── Task3/
├── Task4/
├── Task5/
├── Task6/
└── README.md
```

## Tools

Microsoft Excel (pivot tables, pivot charts, slicers, `GETPIVOTDATA`, table formulas).

#Auspify #AuspifyTechnologies #AuspifyInternship #AuspifyProjects
