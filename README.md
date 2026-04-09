# A-Share Consumer Sector Profitability Analysis 2018–2023

## 1. Problem & User
This project analyses the profitability trends of three leading A-share consumer companies 
(Kweichow Moutai, Wuliangye, Haitian Flavouring) from 2018 to 2023, 
targeting individual investors interested in the Chinese consumer sector.

## 2. Data
- Source: WRDS Compustat Global (comp_global_daily.g_funda)
- Access date: 9 April 2026
- Key fields: sale (revenue), nicon (net income), ceq (shareholders' equity), at (total assets)

## 3. Methods
- Data retrieval via WRDS Python API
- Data cleaning and fiscal year assignment using pandas
- Calculated metrics: Net Profit Margin, ROE, Revenue Growth Rate
- Visualisation using matplotlib

## 4. Key Findings
- Kweichow Moutai maintains the highest net profit margin (~48–50%), steadily increasing
- Wuliangye shows stable growth (~33–36% margin)
- Haitian Flavouring experienced a significant decline after 2020, with margin dropping to ~25% by 2023
- Haitian's ROE fell from 32% to 20%, the sharpest drop among the three

## 5. How to Run
1. Install dependencies: `pip install wrds pandas matplotlib`
2. Ensure you have a valid WRDS account
3. Run `ACC102.ipynb` in Jupyter Notebook

## 6. Notebook
See [ACC102.ipynb](./ACC102.ipynb) for the full analysis workflow.

## 7. Limitations & Next Steps
- Data limited to Compustat coverage; some fields may differ from official A-share filings
- Future work could include more companies or quarterly data
