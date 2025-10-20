![david-rotimi-LxENUKJXh_k-unsplash](https://github.com/user-attachments/assets/f773aa45-4bae-4e1b-b7df-a81ff26958ac)

Photo by <a href="https://unsplash.com/@davidrotimi?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">David Rotimi</a> on <a href="https://unsplash.com/photos/white-arc-LxENUKJXh_k?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

---

#  Tracking the Pulse of a Nation  
### A Data-Driven Study of Nigeria’s Population and Health Indicators

## Project Overview
This project analyzes key demographic and health indicators in **Nigeria** using a data-driven approach.  
It explores how birth, death, and fertility trends shape national development and public-health outcomes.  
The study integrates data scraping, cleaning, transformation, and dashboard visualization to illustrate the country’s population transition and health dynamics.

---

## Objectives
- Examine long-term trends in Nigeria’s **fertility, mortality, and population growth**.  
- Quantify demographic transition patterns and their policy implications.  
- Build an automated, reproducible workflow for collecting and visualizing population and health indicators.  
- Communicate insights through interactive dashboards for evidence-based decision-making.

---

## Data & Methodology

### Data Sources
- **Primary source:** Wikipedia tables on *Demographics of Nigeria*, *Population*, and *Health Indicators*.  
- **Supplementary references:** World Bank, IMF, and UNDP datasets for contextual interpretation.

### Data Workflow
| Step | Tool | Description |
|------|------|-------------|
| **Extraction** | Python (`requests`, `BeautifulSoup`, `pandas.read_html`) | Scraped population and health tables from Wikipedia. |
| **Transformation & Cleaning** | Microsoft Excel | Standardized missing values, aligned years, converted all rates to per-1,000 basis, and derived calculated metrics. |
| **Loading & Visualization** | Power BI | Created four interactive dashboards to visualize population growth, mortality, fertility, and forecast trends. |

### Derived Metrics
- **Natural Growth Rate** = CBR − CDR  
- **Year-on-Year Growth (%)** for population  

---

## Dashboards
1. **Population Growth Trends** – Total population, growth rate (%), and year-on-year comparison.  
2. **Mortality & Life Expectancy Indicators** – Death rate, infant mortality, and proxy life expectancy.  
3. **Fertility & Birth Metrics** – Total fertility rate, crude birth rate, and annual births.  
4. **Comparative & Forecast Analysis** – Relationship between fertility and growth; projections for next decade.

---

## Key Insights
- Nigeria’s population is still **growing steadily**, but the **growth rate is slowing** a sign of demographic transition.  
- **Infant mortality** has declined, and **life expectancy** is improving, reflecting better healthcare access.  
- **Fertility rates** continue to fall, yet the absolute number of births remains high due to population momentum.  
- Projections indicate Nigeria may reach **zero natural growth** or below-replacement fertility within the next decade.  

---

## Policy Implications
1. **Strengthen Health Systems** – Expand preventive and maternal healthcare.  
2. **Promote Family Planning** – Improve access to reproductive education and contraception.  
3. **Invest in Education** – Especially for girls and young women to sustain fertility decline.  
4. **Prepare for Ageing Population** – Reform pensions and geriatric healthcare.  
5. **Align Economy with Demographics** – Match job creation and infrastructure to population trends.  
6. **Improve Data Infrastructure** – Support consistent demographic data collection for policy planning.  

---

## Tools & Technologies
- **Python:** `requests`, `BeautifulSoup`, `pandas`  
- **Excel:** Data cleaning and transformation  
- **Power BI:** Dashboard design and visualization  
- **ETL Framework:** Extract → Transform → Load  

---

## Limitations
- Source data (Wikipedia) may not reflect the most recent official statistics.  
- National-level analysis only; excludes sub-national variations.  
- Forecasts assume linear continuation of past trends.  

---

## Conclusion
Nigeria’s demographic story reveals a nation in transition high but slowing population growth, declining fertility, improving life expectancy, and emerging health challenges.  
This analysis underscores the power of **open data** and **visual analytics** in understanding population health and supporting data-driven policy decisions.

