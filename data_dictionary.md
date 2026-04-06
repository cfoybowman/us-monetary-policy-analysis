# 📘 Data Dictionary

## Dataset: macro_dashboard_clean.csv

| Column Name | Description |
|------------|------------|
| Date | Observation date |
| Fed Rate | Federal Funds Rate (%) |
| CPI | Consumer Price Index |
| Unemployment | U.S. unemployment rate (%) |
| Inflation YoY | Year-over-year inflation rate (%) |

## Engineered Features

| Column Name | Description |
|------------|------------|
| Fed Rate Change | Month-over-month change in Federal Funds Rate |
| Fed Rate Rolling | 12-month rolling average of Federal Funds Rate |
| Inflation Rolling | 12-month rolling average of inflation |
| Unemployment Rolling | 12-month rolling average of unemployment |

## Analytical Use

- **Fed Rate** is the primary measure of monetary policy stance  
- **Inflation YoY** is used to assess price pressure and policy response  
- **Unemployment** is used to represent labor market conditions  
- **Rolling features** help smooth volatility and reveal broader macroeconomic trends  