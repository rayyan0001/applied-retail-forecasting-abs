## Data source

This project uses monthly retail turnover data from the [Australian Bureau of Statistics (ABS).](https://www.abs.gov.au/statistics/industry/retail-and-wholesale-trade/retail-trade-australia/jun-2025)

- Catalogue: 8501.0 – Retail Trade
- Table: 11
- Measure: Turnover ($ millions)
- Region: Northern Territory
- Industry: Furniture, floor coverings, houseware and textile goods retailing
- Series ID: A3349526J
- Frequency: Monthly
- Coverage: April 1988 to December 2022

Note: Values are reported in nominal Australian dollars.

The data are publicly available from the ABS and are accessed programmatically in the analysis 
using the `readabs` R package.

A static snapshot of the ABS data is stored in this repository to **avoid repeated data 
pulls.** The source data are publicly available from the Australian Bureau of Statistics.
