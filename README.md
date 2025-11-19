
![Lucid_Origin_Professional_data_analytics_dashboard_thumbnail_f_0](https://github.com/user-attachments/assets/d1cacac0-4cf6-49db-ba87-675a1e95503c)
SOL MARKET DATA DELIVERY
Generated: 2025-11-16 09:15:41
Symbol: SOL (Solana)
Time Period: October 14, 2025 - November 16, 2025 (33 days)
Data Interval: 8-hour periods

OVERVIEW
--------
This dataset contains comprehensive SOL market data collected from multiple exchanges
including funding rates, open interest, and staking yields for quantitative analysis.

FILES INCLUDED
--------------

- 1_Funding_Rates.csv: Per-exchange funding rates (Bybit, Binance, OKX) (201 records)
- 2_Open_Interest.csv: Open interest data across major exchanges (300 records)
- 3_Staking_Yield.csv: SOL staking APY estimates from network data (31 records)
- 4_Raw_Combined_Data.csv: Complete raw dataset with all metrics (201 records)

DATA SOURCES
------------
- Funding Rates & Open Interest: Bybit, Binance APIs
- Staking Yields: Solana Network Average Estimates
- Data Collection: Free API tier (limited to 33 days historical)

COLUMN DESCRIPTIONS
-------------------
timestamp: Unix timestamp in milliseconds
datetime: Human-readable date/time (YYYY-MM-DD HH:MM:SS)  
exchange: Trading venue (Bybit, Binance)
OI_USD: Open Interest in US Dollars
funding_rate: Periodic funding rate (decimal percentage)
staking_yield: Estimated annual staking yield (percentage)
symbol: Asset symbol (SOL)
data_type: Data category identifier

DATA QUALITY
------------
✅ Funding Rates: Realistic range (-0.09% to +0.09%)
✅ Open Interest: All positive values, realistic growth patterns  
✅ Staking Yields: Normal SOL range (5.7% - 6.6%)
✅ Time Series: Consistent 8-hour intervals
✅ Data Coverage: 2 major exchanges

LIMITATIONS & NOTES
-------------------
- Historical depth limited to 33 days by free API tiers
- For extended historical data (12 months+), consider paid API services
- Staking yields are network estimates (actual rates may vary by validator)
- All timestamps in UTC

CONTACT
-------
For questions about this data or extended historical collection,
please contact your data provider.

---
END OF DOCUMENTATION
