# ✈️ Airport Analysis Dashboard

> An interactive **Power BI** dashboard to monitor flight volume, cancellations and delays across U.S. airports.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Overview

This project is an interactive Power BI dashboard built to monitor key airline performance metrics: **flight volume, cancellations and delays**. It helps airline and airport teams spot patterns, understand where operations slow down and make data-driven decisions to improve punctuality and customer experience.

**Scope:** 3 dashboard pages · 5 slicers · KPI cards, maps, treemap and a detailed table.

## 🎯 Objectives

- Track flight volume and cancellations by month, day, origin and destination.
- Measure average departure and arrival delays and how they relate to distance.
- Identify the routes and destinations most affected by cancellations.
- Give stakeholders a clear, interactive view of operational performance.

## 📊 Key KPIs

| Total flights | Cancelled flights | Avg arrival delay | Avg departure delay |
|:---:|:---:|:---:|:---:|
| **33K** | **393** | **60.72** | **34.99** |

> Figures are read from the dashboard as filtered in the screenshots. They change when slicers are applied.

## 🗂️ Dashboard Structure

| Page | Purpose | Main visuals |
|------|---------|--------------|
| **1. Airport Analysis Dashboard** | Flight volume and cancellations | KPI cards, bar chart by month, area chart by day |
| **2. Delays and Time Analysis** | Punctuality of departures and arrivals | KPI cards, scatter plots by distance, map |
| **3. Detailed Flight Analysis** | Drill-down into individual flights | Detailed table, treemap of cancellations |

### Page 1 – Airport Analysis Dashboard
![Page 1](images/page1_airport_analysis.png)

- **Total Flights by Month:** volume is steady at roughly 2.7K–2.8K flights per month, with February the lowest at 2.5K.
- **Cancelled Flights by Day:** cancellations are irregular across the month, with peaks of about 20 flights on certain days.

### Page 2 – Delays and Time Analysis
![Page 2](images/page2_delays_time_analysis.png)

- **Avg Dep Delay / Avg Arr Delay by Distance:** scatter plots showing how delays vary with flight distance.
- **Map:** departure and arrival delays by origin and destination airport across North America.

### Page 3 – Detailed Flight Analysis
![Page 3](images/page3_detailed_flight_analysis.png)

- **Detailed table:** flight date, origin, destination, expected vs. actual departure and arrival times, cancellation flag and distance.
- **Treemap:** cancellations by destination. In the view shown, **Jackson (Mississippi)** has the largest block, followed by Atlanta, Los Angeles and Denver.

## 🔍 Key Observations

- Monthly flight volume is stable, with February the lowest (2.5K vs. about 2.7K–2.8K).
- Cancellations peak on certain days of the month rather than following a steady pattern.
- Arrival delays are higher than departure delays, suggesting delay is added in flight or on arrival.
- Cancellations are concentrated in a few destinations, led by Jackson (Mississippi) in the view shown.

### Questions worth investigating

| Observation | Follow-up question |
|-------------|--------------------|
| Cancellation peaks on specific days | Do the peaks match weather events, holidays or particular airlines? |
| Arrival delay above departure delay | Is the gap linked to distance, congestion at destination or specific routes? |
| Jackson (Mississippi) leads cancellations | Is this driven by flight volume at that airport or by a higher cancellation rate? |

## 🛠️ Tools & Skills

This dashboard was built with **Microsoft Power BI Desktop**. The data was cleaned and transformed with **Power Query**, and the calculations (totals, average departure and arrival delays) were written as **DAX measures**. Relationships between tables were set up in the data model so that filters work across all pages.

The report uses KPI cards, a bar chart, an area chart, scatter plots, a map, a treemap and a detailed table. Interactivity comes from slicers (month, day, year, origin, destination) and page navigation buttons.

### Skills demonstrated by the author

- **Data preparation:** cleaning and transforming raw flight data with Power Query.
- **DAX:** writing measures for totals and average departure/arrival delays.
- **Data modeling:** building table relationships so slicers filter every page.
- **Data visualization:** designing KPI cards, charts, maps, a treemap and a drill-down table.
- **Analytical thinking:** turning patterns (cancellation peaks, delay gaps) into follow-up business questions.
- **Version control:** documenting and publishing the project with Git and GitHub.

## 📁 Repository Structure

```
Airport-Analysis-Dashboard/
├── Airport_Analysis_Dashboard.pbix                  # Power BI report file
├── Airport_Analysis_Dashboard_Report_Purple.pdf     # Project report
├── images/                                          # Dashboard screenshots
│   ├── page1_airport_analysis.png
│   ├── page2_delays_time_analysis.png
│   └── page3_detailed_flight_analysis.png
└── README.md
```

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Airport-Analysis-Dashboard.git
   ```
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows).
3. Open the `.pbix` file.
4. Use the slicers (month, day, year, origin, destination) and the navigation buttons to explore the three pages.

## 🔮 Possible Improvements

- Analyze delays and cancellations by airline and by cause.
- Add year-over-year comparisons.
- Publish the report to Power BI Service for online sharing.

## 👩‍💻 Author

**Oumaima B.** — Data & AI Engineer | Data Scientist | Data Analyst
🔗 [LinkedIn](https://www.linkedin.com/in/oumaimabendjaj)

---

⭐ If you find this project useful, feel free to give it a star!
