# Analysis of Transjakarta Service Usage Patterns (April 2023)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)


## Executive Summary
This project analyzes user behavior across three service categories of Transjakarta – **Core Service**, **Premium Service**, and **Tourism Service** – based on simulated transaction data from April 2023.

**Key Findings**
1. Commuter-Dominated System
    - The majority of users are of working age, indicating that Transjakarta primarily serves daily commuting needs.
    - Female users represent 53% of total riders, suggesting slightly higher reliance on public transport among women.

2. Strong Peak Hour Demand
    - Clear demand spikes at **07:00 (morning)** and **18:00 (evening)**.
    - Evening peak is higher than the morning peak, indicating heavier return-trip congestion.
    - Core services carry the majority of peak-hour traffic.

3. Payment Concentration
    - Bank DKI accounts for ~49% of total transactions, making it the dominant payment channel across the system.
    - The dependency on Bank DKI is even more pronounced in Tourism services, where over 70% of transactions are processed through it.

4. Weekday-Oriented Usage
    - Significant drop in ridership during weekends. This suggests limited adoption for leisure or non-work travel.

5. High Occasional & One-Time Users
    - 33.2% of overall Transjakarta users are occasional users.
    - Core services show 36% occasional users, indicating strong conversion potential to frequent users.
    - Premium (71.6%) and Tourism (60%) are primarily composed of one-time users.

---
## Dataset Source

- **Source:** [Transjakarta - Public Transportation Transaction](https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction) (Kaggle)
- **Author:** dikisahkan
- **License:** Publicly available for analysis purposes

> **Disclaimer:** This dataset is simulated and does not represent real Transjakarta data.

---
## Repository Structure
```
├── data/
│ ├── Transjakarta.csv
│ └── transjakarta_cleaned.csv
├── notebooks/
│ └── transjakarta_analysis.ipynb
├── dashboard/
│ └── TransJakarta User Profile Dashboard.twbx
├── README.md
└── LICENSE
```