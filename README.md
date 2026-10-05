# ✈️ Airport Analysis Dashboard – Power BI

An interactive **Power BI** dashboard that analyzes flight activity, cancellations and delays across U.S. airports, helping airline and airport teams spot patterns and improve operational performance.

![Airport Analysis Dashboard](images/overview.png)

## 📌 Overview

This project is an interactive **Power BI** dashboard built to monitor key **airline performance metrics**: flight volume, cancellations and delays. It helps airline and airport teams spot patterns, understand where operations slow down and make data-driven decisions to improve punctuality and customer experience.

**Objectives**
- Track flight volume and cancellations by month, day, origin and destination
- Measure average departure and arrival delays and how they relate to distance
- Identify the routes and destinations most affected by cancellations
- Give stakeholders a clear, interactive view of operational performance

## 📊 Dashboard Pages

### 1. Airport Analysis Dashboard
High-level view of flight volume and cancellations.
- **KPIs:** total flights (33K) and cancelled flights (393)
- **Total Flights by Month** and **Cancelled Flights by Day**
- **Slicers:** month, day, origin and destination

![Overview](images/overview.png)

### 2. Delays and Time Analysis
Punctuality analysis of departures and arrivals.
- **KPIs:** average arrival delay (60.72) and average departure delay (34.99)
- **Scatter charts:** average departure and arrival delay by distance
- **Map:** delays by origin and destination airport
- **Slicers:** month, year, origin and destination

![Delays](images/delays.png)

### 3. Detailed Flight Analysis
Drill-down into individual flights.
- **Detailed table:** flight date, origin, destination, expected vs. actual departure and arrival times, cancellation flag and distance
- **Treemap:** cancellations by destination

![Details](images/details.png)

## 🔎 Key Observations

- Monthly flight volume is steady at about 2.7K–2.8K, with **February the lowest (2.5K)**.
- Cancellations are irregular, with **peaks of about 20 flights** on certain days of the month.
- **Arrival delays (60.72) are noticeably higher than departure delays (34.99)** in the data shown.
- In the treemap, **Jackson (Mississippi)** accounts for the largest block of cancellations by destination, followed by Atlanta, Los Angeles and Denver.

*Figures reflect the dashboard as filtered in the screenshots; they change with the slicers.*

## 🧰 Tools & Skills

| Area | Details |
|---|---|
| Tool | Microsoft Power BI Desktop |
| Data preparation | Power Query (cleaning and transformation) |
| Calculations | DAX measures (e.g. average delays, totals) |
| Data modeling | Relationships between tables for filtering across pages |
| Visuals | KPI cards, bar chart, area chart, scatter plots, map, treemap, detailed table |
| Interactivity | Slicers (month, day, year, origin, destination) and page navigation buttons |

## ▶️ How to Open

1. Download or clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   ```
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. Open the `.pbix` file and use the slicers and the arrow button to move between pages.

## 📁 Project Files

```
.
├── airport-analysis-dashboard.pbix   # Power BI file
├── images/                           # Dashboard screenshots
└── README.md
```

## 🔭 Possible Improvements

- Analyze delays and cancellations by airline and by cause
- Add year-over-year comparisons
- Publish the report to Power BI Service for online sharing

## 👤 Author

**Your Name** · [LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
