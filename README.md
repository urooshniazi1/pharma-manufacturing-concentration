1. U.S. Pharmaceutical Manufacturing Geographic Concentration

Analysis of FDA-registered drug manufacturing establishments using the 
Drug Establishments Current Registration Site (DECRS) database.

2. Key Findings

- **45.9%** of all registered drug manufacturing establishments are located outside the United States
- **78.8%** of API (active pharmaceutical ingredient) manufacturing facilities are foreign-registered
- India (563) and China (532) together account for **55.4%** of all foreign API manufacturers
- Total facilities analyzed: **10,460** (source: drls_reg.xls, September 2026)

3. Interactive Dashboard

[View on Tableau Public](https://public.tableau.com/app/profile/uroosh.niazi2790/viz/U_S_PharmaceuticalManufacturingGeographicConcentrationFDADECRS2026/Dashboard1)

4. Data Source

FDA Drug Establishments Current Registration Site (DECRS)  
Downloaded: September 2026  
URL: https://www.fda.gov/drugs/drug-approvals-and-databases/drug-establishments-current-registration-site

5. Methodology

Country of registration was extracted from the 3-letter ISO code embedded 
in each facility's ADDRESS field (e.g., "France (FRA)"). Operation types 
were parsed from the semicolon-delimited OPERATIONS field. See 
`decrs_analysis.ipynb` for full code.

6. Files

| File | Description |
|------|-------------|
| `decrs_analysis.ipynb` | Full analysis notebook (Google Colab) |
| `decrs_country_summary.csv` | Facility counts by country |
| `decrs_api_country.csv` | API manufacture facilities by country |
| `decrs_ops_by_country.csv` | Operation types by country |
| `decrs_headline.csv` | Headline summary statistics |
