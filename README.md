# -climate-shock-food-inflation-ghana-bibliometrics
Bibliometric analysis of climate shocks and food inflation in Ghana
# Climate Shock and Food Inflation in Ghana: A Bibliometric Analysis
## Overview
This repository contains the full bibliometric analysis of the relationship 
between climate shocks and food inflation in Ghana, replicating and extending 
the methodology of Verma & Gustafsson (2020).

## Database
**Scopus** (primary database)
Search period: 2015–2026
Documents retrieved: 457 journal articles

## Search String
```
TITLE-ABS-KEY (
  ( "climate shock*" OR "climate variab*" OR "rainfall variab*" 
    OR "precipitation anomal*" OR "drought" OR "flood*" 
    OR "temperature shock*" OR "weather shock*" )
  AND
  ( "food inflation" OR "food price*" OR "food price volatility" 
    OR "agricultural price*" OR "crop price*" OR "food cost*"
    OR "food security" OR "food insecurity" )
  AND
  ( "Ghana" OR "West Africa" OR "Sub-Saharan Africa" )
)
AND PUBYEAR > 2014
AND DOCTYPE ( ar )
AND SRCTYPE ( j )
```

## Repository Structure
```
├── data/         # Raw .bib export files from Scopus
├── scripts/      # R Markdown analysis files
├── output/       # Figures, tables, and results
└── README.md
```

## Tools
- **R** with `bibliometrix` package
- **VOSviewer** for network visualization
- **R Markdown** for reproducible reporting

## Reference
Verma, S., & Gustafsson, A. (2020). Investigating the emerging COVID-19 research 
trends in the field of business and management: A bibliometric analysis approach. 
*Journal of Business Research*, 118, 253–261.
