# Olympics Data Analysis Web App

## Overview

This project is an interactive web application for exploring and analyzing historical Olympics data. Built with Python, Streamlit, Pandas, Plotly, and Seaborn, it enables users to visualize medal tallies, athlete statistics, country-wise performance, and trends across different sports and years.

## Features

- **Medal Tally:**  
  View medal counts by country and year, with options to filter for specific countries or Olympic editions.

- **Overall Analysis:**  
  Explore top-level statistics such as the number of editions, host cities, sports, events, athletes, and participating nations.

- **Country-wise Analysis:**  
  Analyze the performance of individual countries over time, including medal trends and strengths in specific sports.

- **Athlete-wise Analysis:**  
  Dive into athlete demographics, including age distributions of medal winners, gender participation trends, and physical attributes (height, weight) by sport and medal type.

- **Visualizations:**  
  - Interactive line plots, distribution plots, and heatmaps.
  - Custom color palettes for medal types (gold, silver, bronze).
  - Dynamic filtering and selection via sidebar controls.

## Data Sources

- `athlete_events.csv`: Contains detailed records of athletes, events, medals, and demographics from past Olympic Games.
- `noc_regions.csv`: Maps National Olympic Committee (NOC) codes to country/region names.
- Dataset Link: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results


## Technologies Used

- **Python** (data processing and backend logic)
- **Streamlit** (web app framework)
- **Pandas** (data manipulation)
- **Plotly** (interactive plots)
- **Seaborn & Matplotlib** (statistical visualizations)

## How to Run

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
2. **Start the app:**
   ```bash
   streamlit run app.py
   ```
3. **Interact:**  
   Use the sidebar to select analysis options and filters.

## Project Structure

- `app.py` — Main Streamlit application.
- `helper.py` — Utility functions for data processing and analysis.
- `preprocessor.py` — Data cleaning and merging logic.
- `Olympics-analysis.ipynb` — Jupyter notebook for exploratory analysis and prototyping.
- `athlete_events.csv`, `noc_regions.csv` — Data files.

## Example Visualizations

- Medal tally tables and plots
- Age distribution of medal winners
- Gender participation trends over time
- Sport-wise heatmaps for country strengths
- Scatter plots of athlete height vs. weight, colored by medal

## Customization

- Easily add new analysis modules or visualizations.
- Update data files for the latest Olympics editions.

## License

This project is for educational and research purposes.

---

**Explore the Olympics like never before !!!**






Live Demo: https://medalytics.onrender.com/
