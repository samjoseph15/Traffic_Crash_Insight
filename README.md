# Traffic Crash Analysis and Safety Intelligence Platform

A Streamlit-based web application for analyzing traffic crash data and generating safety intelligence insights.

## Features

- Interactive dashboard with dynamic visualizations
- Geospatial analysis to identify crash hotspots
- Trend analysis (hourly, daily, monthly, yearly)
- Safety intelligence with actionable insights
- Data filtering by date, location, and severity

## Installation

**Prerequisites:**
- Python 3.8+
- pip

**Steps:**
```bash
pip install -r requirements.txt
streamlit run str_app.py
```

## Usage

The steeamlit app opens at `http://localhost:8501`. Use the sidebar to navigate between analysis sections.

## Data Requirements

CSV file:

It contains 

- Crash date/time
- Location (lat/lon or address)
- Severity level
- Crash type/causes

## Project Structure

traffic-crash-analysis/
├── str_app.py
├── requirements.txt
├── README.md
├── data/
├── notebooks/
└── utils/


## Key Insights

1. **70.5%** crashes have no injury
2. **78%** occur in CLEAR weather (driver behavior > weather)
3. **63%** happen in DAYLIGHT (exposure > visibility)
4. **37%** causes "UNABLE TO DETERMINE" (data quality issue)
5. **22%** of crashes at 3-5 PM (commute peak)
6. **Sunday** has highest crashes (16%)
7. **August** is peak month (8.7%)

## Dependencies

```txt
streamlit
pandas
numpy
plotly
folium
sqlalchemy
mysql-connector-python
```

## Analysis Sections

- Crash Type | Weather | Light Condition | Primary Cause | Road Surface
- Crash by Hour | Day | Month | Year
- Top Streets | Hotspots | Time Slots | Injury Rates

## Contact

Email: [samjoseph15.inbox@gmail.com]

