# Bike Store Sales & Inventory Dashboard

## Overview

This project analyzes sales and inventory data for a bike store using SQLite, Python (Pandas), and Tableau. The goal is to extract insights through key performance indicators (KPIs), filters, and visualizations presented in a Tableau dashboard.

## Dashboard Preview

View the interactive Tableau dashboard here: [Bike Store Dashboard](https://bit.ly/bikes_tableau)

## Workflow

1. **Extract Data:** Use Python and Pandas to read and join relevant tables from the SQLite database.
2. **Transform Data:** Perform necessary cleaning and transformations in a Jupyter Notebook.
3. **Save to Excel:** Export the processed sales and inventory data to Excel for Tableau.
4. **Build Tableau Dashboard:** Create interactive dashboards with KPIs, filters, and visualizations.

## Features

- **Sales and Inventory Analysis:** Sales, Quantity, Units Per Transaction, and Inventory Data.
- **Interactive Filters:** Dynamic selection of stores, brands, categories, and employees.

## Files & Structure

```
📂 Bikes_Tableau
├── 📜 Bike Store Dashboard.twb  # Tableau workbook
├── 📜 Bikestore.db              # SQLite database
├── 📜 README.md                # Project documentation
├── 📜 connect.sh               # Connection script
├── 📜 order_items.xlsx         # Processed sales data for Tableau
├── 📜 stocks.xlsx              # Processed inventory data for Tableau
├── 📜 transformations.ipynb     # Jupyter Notebook for data transformation
```
