# Air Pollution Analysis & Visualization Project

## About the Project
This project analyzes real-time air quality data across India to identify pollution hotspots, compare pollutant levels across states and cities, and present the findings through visualizations and an interactive dashboard.

**Course:** Data Analytics and Visualization (DAV)

## Dataset
- **Records:** 3,563 monitoring readings
- **Coverage:** 271 cities across 31 Indian states
- **Pollutants tracked:** PM2.5, PM10, NO2, SO2, CO, NH3, Ozone
- **Fields:** state, city, station, latitude, longitude, pollutant ID, min/max/avg concentration, last updated timestamp

## Objectives
- Identify the most polluted states and cities
- Compare pollutant levels across regions
- Study relationships between different pollutants
- Classify air quality into AQI categories
- Visualize patterns through charts and an interactive dashboard

## Project Workflow
| Step | Description | Status |
|------|-------------|--------|
| 1. Project Proposal | Problem statement, objectives, scope, tech stack | ⬜ |
| 2. Data Collection | Source documentation, data dictionary | ⬜ |
| 3. Data Cleaning | Handle missing values, fix data types, remove duplicates | ⬜ |
| 4. Data Analysis | EDA, statistics, correlation, AQI classification | ⬜ |
| 5. Data Visualization | Bar charts, heatmaps, box plots, pie charts, maps | ⬜ |
| 6. Interactive Dashboard | Streamlit/Power BI dashboard with filters | ⬜ |

## Tech Stack
- **Language:** Python
- **Data handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Dashboard:** Streamlit
- **Version control:** Git & GitHub

## Repository Structure
```
├── data/
│   ├── raw/              # Original unedited dataset
│   └── cleaned/          # Cleaned dataset ready for analysis
├── notebooks/            # Jupyter notebooks for cleaning & analysis
├── visualizations/        # Saved chart images
├── dashboard/             # Dashboard app files
├── proposal.md             # Project proposal document
└── README.md
```

## Team Members & Task Assignment
| Step | Task | Assigned To |
|------|------|-------------|
| 1 | Project Proposal | Reethika |
| 2 | Data Collection | Jonan |
| 3 | Data Cleaning | Varshitha |
| 4 | Data Analysis | Varshitha |
| 5 | Data Visualization | Jonan |
| 6 | Interactive Dashboard | Reethika |

## How to Run
```bash
# Clone the repository
git clone <repo-url>

# Install dependencies
pip install pandas numpy matplotlib seaborn plotly streamlit

# Run the dashboard
streamlit run dashboard/app.py
```
