# COVID19-Global-Situation-Dashboard

This project provides a Power BI dashboard analyzing the global and regional impact of COVID-19. It highlights confirmed cases, deaths, recoveries, active cases, and regional trends with interactive visuals.

---

# 📊 Dashboard Overview

The dashboard provides a comprehensive and interactive analysis of the COVID-19 pandemic across countries and regions. It helps uncover:

* **Global Situation Overview** — Total confirmed cases, deaths, recoveries, and active cases with worldwide comparisons.
* **Country & Regional Insights** — Drilldown into countries and provinces/states to assess localized impact and trends.
* **Trend Analysis** — Daily new cases, deaths, recoveries, and growth curves to understand pandemic progression over time.
* **Comparative View** — Ranking of top affected countries, regions, and provinces to identify hotspots.
* **Fatality & Recovery Ratios** — Metrics showing survival vs. mortality rates across regions for deeper understanding of outcomes.

---

## 🚀 Key Features

* **Interactive Visuals** — Clickable charts, slicers, and filters for seamless exploration by country, date, and region.
* **Key Performance Indicators (KPIs)** — At-a-glance metrics including total confirmed cases, total deaths, total recoveries, and active cases.
* **Drilldown Analysis** — Ability to zoom into country-level and state-level details for targeted insights.
* **Trend Monitoring** — Line charts and bar visuals showing daily changes and long-term patterns.
* **Actionable Insights** — Each page highlights global patterns, country-specific challenges, and trends to support informed decision-making during the pandemic.

---

## 📈 Dashboard Pages

### 1. Global Snapshot

* **What it shows:** High-level KPIs with COVID-19 trends, daily case dynamics, and country-level distribution.
* **Key metrics:** Total Active Cases, Total Confirmed Cases, Total Deaths, Total Recovered, Death%, Recovery%, Daily New Cases, New Deaths, and New Recoveries
* **Visuals:** KPI cards for totals + ratios (Death %, Recovery %), Line chart of confirmed, deaths, recoveries over time, Pie chart of new cases vs deaths vs recoveries, Map showing confirmed cases by country & WHO region, Date range slicer for timeline analysis.
* **Insights:** Provides a global-level snapshot of the pandemic’s spread and impact. Helps identify worldwide growth patterns, daily dynamics, and regional hotspots, enabling a quick understanding of overall pandemic status.

![Global Snapshot](Previews/GlobalSnapshot.PNG)

---

### 2. Country Deep Dive

* **What it shows:** A detailed breakdown of the pandemic at the continental and country level, highlighting how cases, deaths, and recoveries vary across regions and which countries are most severely affected.
* **Key metrics:** Total Active Cases, Total Confirmed Cases, Total Deaths, Regional variations (WHO region / continent), Country-level proportions (Active vs Deaths).
* **Visuals:** KPI cards for global totals, Scatter plot comparing continent-wise cases, deaths & population, Bar chart for Top 10 countries (Active vs Deaths proportion), Trend line for confirmed, deaths, recoveries progression.
* **Insights:** This view emphasizes the uneven spread of COVID-19 across the world, showing both continental disparities and specific country hotspots. It helps quickly identify which countries are under the greatest strain and how their outcomes differ, supporting regional and international comparison.

![Country Deep Dive](Previews/CountryDeepDive.PNG)

---

### 3. Regional WHO Insights

* **What it shows:** A focused breakdown of COVID-19 activity across WHO regions and continents, covering active cases, new case trends, recoveries, and deaths. It highlights how the pandemic differs regionally, giving both a global snapshot and granular regional performance.
* **Key metrics:** Active Cases, New Cases, New Deaths, New Recoveries, Cumulative totals (cases, deaths, recoveries) by WHO region.
* **Visuals:** Interactive map plotting active cases by geography, Donut chart of new cases vs new deaths vs new recoveries, Bar chart of total cases across WHO regions, Comparative bar (Recoveries vs Deaths by region).
* **Insights:** This page uncovers how regions vary in both spread and recovery, illustrating where new infections are accelerating, where recovery efforts are strong, and which areas continue to struggle with high mortality. It enables comparisons across WHO regions, providing a balanced view of pandemic intensity and healthcare response effectiveness.

![Regional WHO Insights](Previews/RegionalWHOInsights.PNG)

---

### 4. Trends & Growth

* **What it shows:** This page highlights how the pandemic evolved over time, with a focus on new cases, new deaths, and overall growth patterns. It captures the trajectory of the virus month by month and tracks how confirmed, active, recovered, and death counts shifted across WHO regions.
* **Key metrics:** Monthly totals (New Cases, New Deaths), Regional totals (Confirmed, Active, Recovered, Deaths), Weekly mean case growth rate per country, Quarterly trends (Cases, Death %, Recovery %) by WHO region.
* **Visuals:** Line charts tracking new cases & deaths over time, Trend curves (Confirmed vs Recovered vs Deaths by WHO region), Bar charts of weekly growth rate leaders by country, Quarterly plots for Recovery %, Case growth %, Death %.
* **Insights:** This page reveals where surges happened, which countries faced the fastest weekly growth, and how recovery rates evolved relative to death and case growth. It highlights hotspots with alarming acceleration, such as Papua New Guinea and Gambia, while also underscoring strong recovery patterns in certain regions. The quarter-wise perspective shows whether regions are stabilizing, improving, or facing repeated waves, making it critical for identifying both risks and areas of resilience.

![Trends & Growth](Previews/Trends&Growth.PNG)

---

### 5. US Focus (County/State)

* **What it shows:** This page dives deep into the US pandemic situation, highlighting confirmed cases and death counts across states and counties. It spotlights where the outbreak has been most severe and which regions have recorded the highest loss of life.
* **Key metrics:** Total confirmed cases by province, Total deaths by province/state, Top 5 states by death count, County-level confirmed cases and deaths.
* **Visuals:** An interactive US map displays confirmed cases by province/state, a trend chart highlights the top five states with the highest death counts over time, and a detailed table lists county-level breakdowns of confirmed cases and deaths with totals aggregated.
* **Insights:** The page reveals that New York leads both in confirmed cases and deaths, with counties like New York, Nassau, and Suffolk dominating the list of hardest-hit regions. States such as New Jersey and Michigan also emerge with significant death tolls, while populous counties like Los Angeles and Cook further highlight urban vulnerability. This breakdown underscores the geographic concentration of the crisis in major metropolitan areas and the regional disparities in impact across the country.

![US Focus](Previews/USFocus.PNG)

---

### 6. Latest Worldometer Snapshot

* **What it shows:** A global snapshot of the pandemic situation, capturing recoveries, total cases, critical cases, and country-wise intensity. It compares nations and regions based on testing, cases per million, and deaths per million to reveal where the impact has been most concentrated.
* **Key metrics:** Total recoveries, total cases, total critical cases, cases per million, tests per million, deaths per million.
* **Visuals:** KPI cards, table of cases/tests/deaths per million by country, world map with country hotspots, regional chart of cases per million and deaths per million by WHO region and continent.
* **Insights:** The snapshot highlights strong disparities across regions, with Europe and the Americas leading in cases per million while the Eastern Mediterranean shows high concentration relative to population. Countries like Qatar, Bahrain, and San Marino display extreme cases-per-million values, but with widely varying mortality rates. Meanwhile, nations such as the USA, Brazil, and Peru reveal both heavy caseloads and high death-per-million ratios, underscoring the uneven global burden. This snapshot allows decision-makers to quickly assess the world’s critical hotspots and regional differences in testing, spread, and mortality.

![Latest Worldometer Snapshot](Previews/LatestWorldometerSnapshot.PNG)

---

## 📂 File Structure

```
.
├── COVID19-Global-Situation.pbix    (Power BI report file)
├── Country-Wise-Latest.csv          (Raw dataset)
├── Covid-19-Clean-Complete.csv      (Raw dataset)
├── Day-Wise.csv                     (Raw dataset)
├── Full-Grouped.csv                 (Raw dataset)
├── USA-County-Wise.csv              (Raw dataset)
├── Worldometer-Data.csv             (Raw dataset)
├── README.md                        (Project documentation)
└── Previews/                        (Dashboard screenshot images)
    ├── CountryDeepDive.PNG
    ├── GlobalSnapshot.PNG
    ├── LatestWorldometerSnapshot.PNG
    ├── RegionalWHOInsights.PNG 
    ├── Trends&Growth.PNG
    └── USFocus.PNG
```

---

## ⚙️ Technologies Used

* Microsoft Power BI Desktop

---

## 🚀 How to Use This Project

1. Clone or download the repository:

   ```bash
   git clone https://github.com/teesta57/COVID19-Global-Situation.git
   ```
2. Open the `COVID19-Global-Situation.pbix` file in Power BI Desktop.
3. Explore the dashboard and apply filters to interact with the data.

---

## 🤝 Contributing

You're welcome to fork the project, explore the dataset, enhance visualizations, or suggest improvements.

---



