# Earnings Dashboard

A simple Streamlit dashboard for tracking daily earnings from Excel data.

## Features
- View earnings, net profit, and passenger trends
- Track conductor performance
- Analyze location-based earnings
- Filter data by date range
- Weekly performance breakdown

## Quick Start

1. **Install requirements**
```bash
pip install streamlit pandas openpyxl plotly
```

2. **Add your data**
   - Create a `data` folder
   - Add `Data.App.xlsx` file with your earnings data

3. **Run the app**
```bash
streamlit run app.py
```

## Data Format
- Each sheet = one day
- Cell E1: Date
- Cell B1: Passenger count
- Cell G13: Total earnings
- Cell H13: Parking costs
- Rows 5-14: Conductor details (name, location, earnings)

## Built With
- Streamlit
- Pandas
- Plotly
- Openpyxl

##SCHOOL PROJECT applied to a real world problem faced in a public transport comapny
