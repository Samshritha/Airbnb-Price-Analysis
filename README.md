# 🏡 Airbnb Superhost Pricing Analysis — London

This project analyzes how Airbnb prices vary across London based on neighborhood, host status, and hosting experience. The goal is to identify which factors have the strongest influence on nightly pricing and to provide clear, data-driven insights for hosts, guests, and investors.

---

## 📌 Project Overview

The analysis uses two datasets:

- **Listings:** Airbnb properties in London with detailed information on price, host status, review scores, and neighborhood  
- **Reviews:** User feedback and ratings for properties

The notebook was built and run in Google Colab, and includes full data cleaning, exploratory analysis, visualizations, and summary findings.

---

## 🧹 Data Preparation

- Converted price values from strings (e.g., `$150`) to numeric floats  
- Removed zero-price entries and capped extreme outliers  
- Selected relevant columns for pricing, host type, neighborhood, and review scores  

This ensures reliable median and correlation calculations.

---

## 📊 Key Analysis Areas

- Neighborhood pricing differences  
- Superhost vs. regular host price comparison  
- Professional vs. non-professional host pricing  
- Review score correlations with price  
- Top neighborhoods by median price

Visualizations include boxplots, bar charts, and pivot tables to show pricing patterns clearly.

---

## 🧠 Main Findings

- Airbnb prices vary strongly by neighborhood  
- Superhosts typically charge higher prices, especially in high-demand areas  
- Hosting across multiple neighborhoods is associated with higher pricing  
- Review scores show almost no relationship with price  

---

## 🪄 Who This Helps

- **Hosts:** Understand how to price competitively  
- **Guests:** Identify where regular hosts may offer better value  
- **Investors:** Spot high-demand neighborhoods for potential returns  

---

## ⚙️ How to Run

1. Open the notebook (`Airbnb_superhost_pricing_analysis.ipynb`) in Google Colab or Jupyter Notebook
2. Install required libraries and run the file 




