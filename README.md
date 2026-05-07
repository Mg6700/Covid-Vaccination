# Covid-19 Vaccination Data Insights

**Tools:** Power BI, DAX  
**Domain:** Public Health Analytics | Geographic Analysis | Vaccination Trends  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes global Covid-19 vaccination data across all participating countries, tracking total vaccinations, full vaccination rates, monthly rollout trends, and country-level acceptance rates. The dashboard enables both high-level global summaries and granular country-specific analysis through an interactive country selector and geographic map visualization.

---

## Dashboard Preview

<img width="978" height="555" alt="image" src="https://github.com/user-attachments/assets/067118ca-68dd-4c06-bdf6-02c297939502" />


---

## Dataset

| Field | Description |
|---|---|
| Countries | All participating nations (scrollable country list) |
| Metrics | Vaccinated people, fully vaccinated people, vaccination rate, coverage % |
| Time | Monthly vaccination rate trend (January–December) |
| Geographic | Country-level map with bubble sizing by vaccination volume |

---

## Key Metrics

| Metric | Value |
|---|---|
| Total Vaccinated People | 660 Billion doses |
| Fully Vaccinated People | 485 Billion doses |

---

## Dashboard Features

- **Country selector** (left sidebar) — scrollable list of all countries for individual analysis
- **Vaccination Rate Trend** — monthly line chart showing vaccination rate from January to December
- **Top Countries by Highest Vaccination Rate** — ranked bar chart by % population vaccinated
- **Top Countries by Vaccination Coverage** — ranked bar chart by coverage metric
- **Vaccine Acceptance Country-Wise** — Bing Maps bubble chart showing global acceptance distribution

---

## Top Countries by Vaccination Rate (%)

| Country Code | Country | Vaccination Rate |
|---|---|---|
| ARE | UAE | 95% |
| PRT | Portugal | 93% |
| BRN | Brunei | 92% |
| SGP | Singapore | 90% |
| MLT | Malta | 90% |
| CHL | Chile | 90% |
| CYM | Cayman Islands | 90% |
| CUB | Cuba | 87% |

---

## Top Countries by Vaccination Coverage

| Country Code | Coverage |
|---|---|
| MLT (Malta) | 55 |
| CHL (Chile) | 53 |
| SGP (Singapore) | 51 |
| GIB (Gibraltar) | 50 |
| CUB (Cuba) | 48 |
| PRT (Portugal) | 36 |
| ARE (UAE) | 35 |
| BRN (Brunei) | 17 |

---

## Monthly Vaccination Rate Trend

| Month | Rate |
|---|---|
| January | 20 |
| February | 19 |
| March | 5 |
| April | 3 |
| May | 6 |
| June | 9 |
| July | 12 |
| August | 16 |
| September | 19 |
| October | 20 |
| November | 23 |
| December | 22 |

---

## Key Findings

**1. UAE achieved the highest vaccination rate globally at 95%**
The UAE's combination of centralized healthcare infrastructure, mandatory vaccination policies for public sector workers, and strong government communication drove the highest uptake of any nation.

**2. Small nations dominate the top vaccination rate rankings**
Malta, Singapore, Brunei, Gibraltar, and Cayman Islands — all small, highly organized nations — appear repeatedly in the top rankings. Smaller populations enable faster, more coordinated rollout logistics.

**3. Monthly trend shows a sharp dip in March–May before recovering**
Vaccination rates dropped from 19–20 in Jan/Feb to just 3 in April before recovering steadily through to a November peak of 23. This V-shape likely reflects initial supply constraints followed by expanded production and distribution.

**4. Coverage and rate are not perfectly correlated**
Malta has the highest coverage (55) but only 90% vaccination rate, while UAE has the highest rate (95%) but lower coverage (35). Rate measures speed/uptake; coverage measures population reach — a country can have high uptake among willing recipients while still missing large unvaccinated segments.

**5. Geographic map shows Europe and Southeast Asia as highest acceptance clusters**
The bubble map reveals dense vaccination acceptance clusters in Western Europe, Southeast Asia (Singapore, Malaysia, Philippines), and parts of Latin America — while large geographic areas in Africa and Central Asia show sparse coverage.

**6. 485 billion fully vaccinated vs 660 billion total doses — 26% single-dose or incomplete**
The gap between total vaccinated (660B) and fully vaccinated (485B) indicates approximately 175 billion doses represent partial vaccination — people who received first doses but didn't complete the full course.

---

## Technical Highlights

- Interactive country selector updating all visuals simultaneously
- Bing Maps bubble visualization scaled by vaccination volume per country
- Monthly trend line chart for temporal rollout pattern analysis
- Dual ranking charts (rate vs coverage) enabling metric comparison
- DAX measures for vaccination rate, coverage %, and fully vaccinated ratio

---

## Data Source

Our World in Data — COVID-19 Vaccination Dataset. WHO Vaccination Tracker.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
