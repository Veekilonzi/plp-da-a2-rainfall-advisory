
# Rainfall Analysis and Planting Advisory

## Project Summary

This project analyses monthly rainfall data from five Kenyan counties using Python and NumPy. It cleans invalid Machakos readings, calculates annual rainfall totals, monthly averages, wettest months, dry-month counts, and recommended planting windows.

## How to Run

1. Install the required library using `pip install -r requirements.txt`.
2. Open `rainfall_analysis.ipynb` using Jupyter Notebook or Google Colab.
3. Run all cells from top to bottom to reproduce the analysis and generate `rainfall_summary.csv`.

## Planting Advisory

- Nairobi, Nakuru, Kisumu and Mombasa have April-May as their recommended planting window.
- Machakos has November-December as its recommended planting window.
- Farmers should consult local weather forecasts because historical rainfall patterns do not guarantee future rainfall.

## Data Quality

The Machakos dataset contained two invalid readings, which were replaced using the rounded average of valid readings (68 mm).
