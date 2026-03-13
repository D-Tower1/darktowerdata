# Dark Tower Data

Dark Tower Data is an independent U.S.-based market data publisher.

We publish **audit-ready OHLCV datasets for Forex, Crypto, and Stocks**, delivered as immutable daily ZIP bundles with **SHA-256 manifests for verification**.

All datasets are versioned, transparent, and built for deterministic reproducibility.

Primary site  
https://darktowerdata.com/

Download data packs  
https://darktowerdata.com/data.html


---

# Dataset Format

All datasets follow a consistent OHLCV schema designed for quantitative research, backtesting, and machine learning pipelines.

Example row:

timestamp_utc,symbol,timeframe,open,high,low,close,volume  
2026-03-13T00:00:00Z,BTC/USD,M5,70532.685,70532.685,70424.361,70449.3,0.0

Fields

timestamp_utc — ISO8601 UTC timestamp  
symbol — trading pair or ticker  
timeframe — candle interval (M1, M5, M15, H1, etc)  
open — opening price  
high — high price  
low — low price  
close — closing price  
volume — traded volume when available


---

# Design Principles

Dark Tower Data datasets are built with the following principles:

• UTC-normalized timestamps  
• deterministic candle boundaries  
• immutable daily dataset releases  
• SHA-256 verification manifests  
• reproducible research workflows  
• no survivorship bias  
• audit-ready structure


---

# Data Delivery

Datasets are delivered as **daily ZIP bundles** containing:

CSV dataset files  
SHA-256 manifest files  
dataset metadata

Example structure

Each bundle can be verified using standard SHA-256 tools.


---

# Available Markets

Current datasets include:

Forex  
Crypto  
Stocks

Additional markets and timeframes may be added as the dataset expands.


---

# Download Sample Data

Developers and researchers can download evaluation datasets here:

https://darktowerdata.com/data.html


---

# About Dark Tower Data

Dark Tower Data focuses on **clean, deterministic financial datasets** designed for:

quantitative research  
algorithmic trading  
backtesting systems  
data integrity validation  
market microstructure analysis

All releases emphasize **transparency, auditability, and reproducibility**.


---

# License

Dataset usage terms are described at:

https://darktowerdata.com/terms.html
