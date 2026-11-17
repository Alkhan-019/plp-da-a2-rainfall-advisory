# County Rainfall and Planting Advisory

## Project Overview

This project uses Python and NumPy to analyze monthly rainfall data for five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa, and Machakos. It identifies annual rainfall totals, monthly averages, wettest months, dry-month counts, and recommended two-month planting windows.

## Project Files

- `rainfall_analysis.ipynb` – Main notebook containing data cleaning, analysis, and planting recommendations.
- `rainfall_summary.csv` – Summary of rainfall statistics and planting windows for all five counties.
- `requirements.txt` – Python dependencies required to run the analysis.

## How to Run

1. Clone or download this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open `rainfall_analysis.ipynb` in Jupyter Notebook or VS Code.
4. Select the appropriate Python environment and run all cells.

## Planting Advisory

- Nairobi, Nakuru, Kisumu, and Mombasa have April–May as their highest combined two-month rainfall window.
- Machakos has November–December as its highest combined two-month rainfall window.
- Farmers should consider soil conditions, crop requirements, and current weather forecasts before making planting decisions.

## Data Quality Notes

Machakos had two missing or invalid readings in April and September. Both were replaced using the mean of the ten valid readings, approximately 68 mm. Consequently, Machakos's results should be interpreted with this data-quality limitation in mind.

## Technologies Used

- Python
- NumPy
- CSV module
- Jupyter Notebook