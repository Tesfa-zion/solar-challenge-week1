Solar Challenge Week 1
This repository contains the foundational setup for the 10 Academy Week 1 Solar Data Challenge. The focus of this task was to establish a clean, professional, and automated project environment using Git, GitHub, and GitHub Actions.

🚀 Project Overview
The goal of this initial setup is to ensure:

A reproducible Python development environment
Proper version control and branching strategy
Automated checks using GitHub Actions
A scalable project folder structure for future work
🔧 Environment Setup
This project uses a virtual environment to isolate dependencies.

Steps to reproduce:
git clone https://github.com/<your-username>/solar-challenge-week1.git
cd solar-challenge-week1

# Option A: Using venv
python3 -m venv venv
source venv/bin/activate

# Option B: Using conda
conda create --name solar_challenge python=3.10
conda activate solar_challenge

# Install project dependencies
pip install -r requirements.txt

#workflow
.github/workflows/ci.yml

#structure
solar-challenge-week1/
├── .github/
│   └── workflows/
│       └── ci.yml             # GitHub Actions workflow
├── .gitignore                 # Ignores data files, CSVs, etc.
├── requirements.txt           # Dependency list
├── README.md                  # Project description
