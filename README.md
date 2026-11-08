# Rainfall Advisory Analysis

## Project Summary

This project analyses monthly rainfall data from five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa and Machakos. Using Python and NumPy, it cleans invalid rainfall readings, calculates rainfall statistics, identifies dry months and recommends two-month planting windows.

## How to Run

1. Clone or download this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the project folder in your terminal.
4. Run `jupyter notebook` and open `rainfall_analysis.ipynb`.
5. Select **Kernel → Restart Kernel and Run All Cells** to reproduce the analysis and generate the CSV summary.

## Planting Advisory

- Nairobi, Nakuru, Kisumu and Mombasa have April–May as their recommended rainfall-based planting window.
- Machakos has November–December as its recommended planting window and requires additional attention to water conservation because it records six dry months.
- Farmers should combine these recommendations with local weather forecasts and soil conditions, noting that two Machakos readings were estimated using the average of valid rainfall values.

## Files

- `rainfall_analysis.ipynb` – Data cleaning, NumPy analysis and planting advisory.
- `rainfall_summary.csv` – Summary of rainfall statistics for the five counties.
- `requirements.txt` – Required Python packages.