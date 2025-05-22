# 🌞 Solar Challenge - Week 1

This repository contains the foundational setup for the **10 Academy Week 1 Solar Data Challenge**.  
The focus of this task was to establish a clean, professional, and automated project environment using **Git**, **GitHub**, and **GitHub Actions**.

---

## 🚀 Project Overview

The goal of this initial setup is to ensure:

- ✅ A reproducible Python development environment  
- ✅ Proper version control and branching strategy  
- ✅ Automated checks using GitHub Actions  
- ✅ A scalable project folder structure for future work  
## 📓 Notebooks

- [Benin EDA](notebooks/1_Benin_eda.ipynb)
- [Sierra Leone EDA](notebooks/2_Sierra-Leone_eda.ipynb)
- [Togo EDA](notebooks/3_Togo_eda.ipynb)
- [Cross Country Comparison](notebooks/Cross_Country_Comparison.ipynb)


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
