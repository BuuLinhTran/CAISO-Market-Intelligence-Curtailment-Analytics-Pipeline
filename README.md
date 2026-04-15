# **CAISO Market Intelligence & Curtailment Analytics Pipeline**
Developed an end-to-end Python pipeline to monitor grid health and pricing dynamics within the CAISO market. By automating data extraction from CAISO OASIS, the project analyzes Locational Marginal Prices (LMP) and renewable curtailment trends to identify regional oversupply and transmission bottlenecks. Built localized trend models for ZP26, NP15, and SP15 hubs to visualize price divergence and basis risk
## Tools and packages: 
- Miniconda version 26.1.1
- Python version 3.11.15
- Pandas v2.3.3
- Numpy v2.2.5
- gridstatus v0.35.0
## Files and folder
- Cali_CAISO_V3.ipynb: Only web scrape, not download raw data locally.
- Cali_CAISO_V4_final.ipynb: Web scrape + download data locally.

## Analysis and visualization:
I. Local Marginal Price for Main Trading Hubs 2025 and 2026
   - 1. Negative Instances of Negative Locational Marginal Pricing per Month
   - 2. Daily Average Locational Marginal Pricing (LMP)

II. Energy Curtailment
    - 3. Cumalative Curtailment in 2025 and 2026
    - 4. Monthly Curtailment
 
