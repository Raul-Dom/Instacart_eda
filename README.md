# Instacart — EDA & Data Cleaning (Portfolio Version)

This repository contains a cleaned, portfolio-friendly version of an exploratory data analysis (EDA) project using the Instacart dataset (multiple related tables). The goal is to showcase my end-to-end workflow: data validation, cleaning decisions, exploratory analysis, and clear conclusions.

> Note: This project was completed as part of the **TripleTen Data Science program**.  
> This version removes reviewer/mentor feedback blocks to keep the narrative focused on the work.

## What’s inside
- `notebooks/instacart_eda_clean.ipynb` — the main notebook (EDA + cleaning + conclusions)
- `requirements.txt` — lightweight dependencies to run the notebook locally

## Highlights (high level)
In this notebook I explore:
- Ordering patterns by day of week and hour of day
- Time between orders (`days_since_prior_order`)
- Basket behavior (e.g., items added to cart / order)
- Reorder behavior (`reordered`) and how it varies across products/categories

## How to run (optional)
1. Create a virtual environment
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook with Jupyter/VS Code.

## Links
- Portfolio project page: (add your GitHub Pages link here)
- Notebook: `notebooks/instacart_eda_clean.ipynb`

## Next improvements
- Add a short “insight → recommendation” section per question
- Export 2–4 key charts as PNGs and reference them in this README
- Tighten figure titles and conclusions for faster scanning
