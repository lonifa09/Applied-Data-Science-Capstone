# 🚀 Applied Data Science Capstone

This repository contains the **Applied Data Science Capstone Project** completed as part of the IBM Data Science Professional Certificate. The project focuses on predicting the success of **SpaceX Falcon 9 launches** using historical data, performing exploratory data analysis, and building an **interactive dashboard** to visualize launch outcomes.

---

## 📑 Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)
- [Results & Insights](#results--insights)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🌍 Overview

The commercial space race is booming, with SpaceX leading the market by drastically lowering launch costs through reusability.  
The main goal of this project is to:
- **Collect and wrangle launch data** from APIs and web sources.
- **Analyze and visualize** trends in launch outcomes.
- **Build predictive models** to estimate the likelihood of launch success.
- **Develop a dashboard app** for interactive data exploration.

---

## 📂 Project Structure

```bash
Applied-Data-Science-Capstone/
│
├── notebooks/
│   ├── spacex-data-collection-api.ipynb   # Collect data from SpaceX API
│   ├── webscraping.ipynb                  # Extract launch data from web sources
│   ├── edadataviz.ipynb                   # Exploratory data analysis and visualization
│   ├── spacex-data-wrangling.ipynb        # Clean and preprocess collected data
│   ├── spacex-launch-site-location.ipynb  # Geospatial analysis of launch sites
│   ├── SpaceX_Machine Learning Prediction_Part_5.ipynb  # ML modeling for launch success
│
├── spacex-dash-app.py     # Interactive dashboard built with Plotly Dash
├── spacex_launch_dash.csv # Processed dataset for dashboard
├── requirements.txt       # Project dependencies
└── README.md              # You are here 🚀
