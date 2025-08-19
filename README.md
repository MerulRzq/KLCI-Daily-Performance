# KLCI Public Listed Companies Analysis

## Project Overview
This project involves real-time monitoring and analysis of companies listed on the **FTSE Bursa Malaysia KLCI Index**. The analysis focuses on key financial metrics including:
- Market capitalization
- Revenue
- Daily percentage change in stock price

The goal is to track performance trends, identify market movers, and provide actionable insights for investment research.

## Key Features
- **Real-time data processing** of KLCI constituents
- **Market cap ranking** analysis
- **Revenue performance** tracking
- **Daily % change** monitoring for volatility assessment
- Visualization of trends and correlations between metrics

## Data Sources
- Stock Analysis market data feeds (https://stockanalysis.com/list/bursa-malaysia/)

## Methodology
1. Automated data collection (web scraping/API calls)
2. Data cleaning and normalization
3. Calculation of derived metrics
4. Visualization using (Python libraries: Pandas, Matplotlib, Plotly etc.)
5. (Add any ML/statistical analysis if applicable)

## Sample Output
![Sample Visualization](/Users/amirulraziq/Documents/GitHub/KLCI_StockAnalysis/Change%.png)

## How to Use
1. Clone repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run main script: `python analysis.py`
4. View generated reports in `/output` folder

## Future Enhancements
- Add sector-wise analysis
- Implement alert system for threshold breaches
- Predictive modeling for price movements
