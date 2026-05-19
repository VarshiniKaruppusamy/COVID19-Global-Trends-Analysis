# COVID19-Global-Trends-Analysis
# COVID-19 Global Trends Analysis
## Our World in Data — 200+ Countries | 2020–2024

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## Project Overview
A comprehensive time-series analysis of global COVID-19 trends
across 200+ countries using the Our World in Data dataset —
one of the most trusted public health databases available.
The analysis covers cases, deaths, vaccination progress, wave
patterns, and continental comparisons, producing 13
publication-quality visualizations and 6 actionable insights.

---

## Dataset
| Detail | Value |
|--------|-------|
| Source | Our World in Data (OWID) |
| Records | 300,000+ rows |
| Countries | 200+ |
| Period | January 2020 – 2024 |
| Key Fields | Cases, Deaths, Vaccinations, Population |
| Access | Auto-downloaded in notebook — no manual download needed |

**Direct URL:**

---

## Business Questions Answered
- Which countries had the highest total cases and deaths?
- How did COVID-19 waves develop globally over time?
- What is the case fatality rate (CFR) by country?
- How did vaccination rollout differ across countries?
- Is there a correlation between vaccination rates
  and deaths per million?
- Which continents were most and least impacted?

---

## Tools & Technologies
| Category | Tools |
|----------|-------|
| Language | Python 3.10 |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Analysis | Rolling averages, correlation, CFR |
| Environment | Jupyter Notebook |

---

## Project Structure

---

## Analysis Sections

### Day 1 — Data Acquisition
- Auto-download from Our World in Data GitHub
- Dataset shape, date range, country count
- Missing value profiling and visualization

### Day 2 — Data Cleaning & Feature Engineering
- Removed continental/global aggregates
- Parsed dates and extracted temporal features
- Engineered per-million metrics for fair comparison
- Calculated Case Fatality Rate (CFR) per country

### Day 3 — Cases & Deaths Analysis
- Top 10 countries by total cases
- Top 10 countries by total deaths
- Top 10 countries by cases per million population
- Top 10 countries by Case Fatality Rate

### Day 4 — Wave Pattern Analysis
- Global daily new cases with 7-day rolling average
- 4 major waves annotated: 1st Wave, 2nd Wave,
  Delta, Omicron
- Country-level wave comparison (USA, India, Brazil,
  UK, Germany)
- Monthly continental heatmap

### Day 5 — Vaccination Analysis
- Global vaccination rollout timeline
- % population with at least one dose vs fully vaccinated
- Top 15 most vaccinated countries
- Scatter plot: vaccination rate vs deaths per million

### Day 6 — Continental Comparison
- Total cases, deaths, and vaccination rate by continent
- Side-by-side 3-panel comparison chart

### Day 7 — Summary Dashboard
- 4-panel summary dashboard
- Final global metrics
- 6 key findings and public health insights

---

## Key Findings

1. **Four distinct global waves** identified using 7-day
   rolling averages — Omicron (Jan 2022) was the largest
   by case volume by a significant margin

2. **USA, India, and France** had the highest absolute
   case counts — per-million metrics reveal smaller
   European nations were proportionally more affected

3. **Case Fatality Rate declined** significantly after
   vaccine rollout began in early 2021, suggesting
   vaccines reduced severity even when infections
   continued

4. **Negative correlation** between vaccination rate and
   deaths per million — countries with higher vaccination
   coverage consistently showed lower mortality burden

5. **Africa had the lowest vaccination coverage**
   throughout the pandemic despite having significant
   case burdens in several countries

6. **Post-Omicron recovery** visible in global time-series
   as natural + vaccine immunity built up — cases declined
   across all continents from mid-2022 onward

---

## Visualizations

### Global COVID-19 Wave Patterns
![Global Waves](plots/fig06_global_waves.png)

### Vaccination Rate vs Deaths per Million
![Vaccination vs Deaths](plots/fig11_vacc_vs_deaths.png)

### Summary Dashboard
![Summary Dashboard](plots/fig13_summary_dashboard.png)

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/
COVID19-Global-Trends-Analysis.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn

# 3. Open the notebook
jupyter notebook COVID19_Global_Trends_Analysis.ipynb

# 4. Run all cells — dataset downloads automatically!
#    No manual download needed.
```

---

## Skills Demonstrated
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn`
`Time-Series Analysis` `Rolling Averages` `EDA`
`Public Health Analytics` `Data Cleaning`
`Feature Engineering` `Correlation Analysis`
`Data Storytelling` `Business Analysis`

---

## Data Source
Our World in Data — COVID-19 Dataset
- GitHub: https://github.com/owid/covid-19-data
- Citation: Mathieu, E., Ritchie, H., Ortiz-Ospina, E.
  et al. "A global database of COVID-19 vaccinations."
  Nat Hum Behav 5, 947–953 (2021)

---

## Author
**Varshini Karuppusamy**
MS Engineering Management — Northeastern University '26
📧 karuppusamy.v@northeastern.edu
💼 [LinkedIn](https://www.linkedin.com/in/kvarshini17/)
🐙 [GitHub](https://github.com/VarshiniKaruppusamy)

---

