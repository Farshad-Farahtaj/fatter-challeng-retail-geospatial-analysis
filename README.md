# Retail Geospatial Analytics — Fater S.p.A. Challenge

![Python](https://img.shields.io/badge/python-3.8%2B-yellow)
![GeoPandas](https://img.shields.io/badge/GeoPandas-0.14-green)
![Folium](https://img.shields.io/badge/Folium-0.15-blue)

Geospatial analysis of retail store performance and market expansion potential for Fater S.p.A. (Procter & Gamble – Angelini Industries joint venture). Store location data was combined with sociodemographic indicators to identify high-potential distribution areas across Italy.

## Team

- Parham Khosh Solat
- Shayan Ekramnia
- Farshad Farahtaj
- Sara Aboudarda

## Approach

Store performance doesn't depend only on the store itself — local demographics, population density, and competitor proximity all play a role. The analysis mapped these factors spatially and ran statistical correlations to rank locations by potential.

- Merged store location data with regional sociodemographic datasets
- Built interactive maps with Folium and GeoPandas to visualize performance patterns
- Extracted and preprocessed data from SQL databases
- Statistical correlation analysis between demographic indicators and store performance metrics

## Project Structure

```
├── Fatter_Public.ipynb    # Analysis notebook (synthetic data)
├── sample_data/           # Synthetic data matching original structure
├── visualizations/        # Output maps and charts
└── README.md
```

## Legal Note

The original dataset was provided by Fater S.p.A. for educational purposes only. This repository contains synthetic sample data that mirrors the structure of the original — no proprietary data is included. All intellectual property rights remain with Fater S.p.A.

## Course

Statistical Learning and Data Analysis — University of Naples Federico II
Supervisor: Prof. Roberta Siciliano

## License

MIT
