# 🌞 Solar Challenge - Week 1

This repository contains the foundational setup for the **10 Academy Week 1 Solar Data Challenge**.  
The focus of this task was to establish a clean, professional, and automated project environment using **Git**, **GitHub**, and **GitHub Actions**.

---

## 🚀 Project Overview


## 📊 Exploratory Data Analysis (EDA)

Each country has a dedicated notebook with profiling, outlier detection, time-series trends, and correlation analysis.

- [Benin EDA](notebooks/1_Benin_eda.ipynb)
- [Sierra Leone EDA](notebooks/2_Sierra-Leone_eda.ipynb)
- [Togo EDA](notebooks/3_Togo_eda.ipynb)

Each cleaned dataset is exported to `data/<country>_clean.csv` (local only, not pushed).

## 🌍 Cross-Country Comparison

- [Cross Country Comparison](notebooks/Cross_Country_Comparison.ipynb)

Includes boxplots, summary statistics, and an optional ANOVA to compare solar potential across countries.


## 🔧 Environment Setup

This project uses a Python virtual environment to isolate dependencies.

### Steps to Reproduce:

```bash
git clone https://github.com/YOUR_USERNAME/solar-challenge-week1.git
cd solar-challenge-week1

# Create and activate virtual environment (Linux/macOS)
python -m venv venv
source venv/bin/activate

# OR on Windows (Command Prompt)
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
