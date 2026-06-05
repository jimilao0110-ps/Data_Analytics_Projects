# Hospital Admission Dashboard – Patient & Admission Analytics
## Project Objective
This project aims to analyze and visualize hospital admission data to understand patient trends, demographics, admission patterns, outcomes, and origins. The goal is to provide clear, data-driven insights that support operational planning, resource allocation, healthcare service improvement, and decision-making for hospital management and healthcare administrators.
## Dataset Used
[Hospital_Admission Dataset](https://github.com/jimilao0110-ps/Data_Analytics_Projects/blob/main/Hospital_Admission_Dashboard-Power%20BI/Hospital_Admission_data.xlsx)
## Questions / Key Performance Indicators (KPIs)
1. How has the number of admissions changed year-over-year and month-over-month?
2. What is the split between emergency and OPD admissions?
3. What is the age and gender distribution of patients?
4. Where do patients come from — urban or rural areas?
5. What are the patient outcomes after treatment?
6. Key KPIs tracked:
    - Total patients: 15,756
    - Average length of stay: 6.42 days
    - Average patient age: 61.43 years
    - Percentage and volume breakdowns for all categories
## Process
1. **Data Collection**: Compile admission records including dates, patient details, admission type, origin, and outcomes.
2. **Data Preparation**: Clean and categorize data; group into time periods, age brackets, geographic areas, and outcome types.
3. **Aggregation**: Calculate totals, averages, percentages, and monthly/yearly volumes.
4. **Visualization Design**: Build dashboard with appropriate visuals:
    - Bar charts: Admissions per year, patient origin
    - Line chart: Admissions per month
    - Pie/donut charts: Admission type, outcome, gender
    - Key metric cards: Total patients, average stay, average age
    - Bar lists: Age range distribution
5. **Analysis & Interpretation**: Identify patterns, trends, and key findings from the visualizations.

## Dashboard
![Hospital Admission Dashboard](https://github.com/jimilao0110-ps/Data_Analytics_Projects/blob/main/Hospital_Admission_Dashboard-Power%20BI/Hosptal_Admission_Dashboard_rev.PNG)
## Project Insights
1. **Admission Trends**:
    - Admissions peaked in 2018 then dropped sharply in 2019 — requires investigation (e.g., service changes, relocation, data scope change).
    - Strong seasonal pattern: highest in January and December, lowest in April; staffing and capacity should align with this cycle.
2. **Admission Type**:
    - Emergency cases dominate (~70%), meaning the hospital functions largely as acute care facility; resource planning must prioritize emergency preparedness.
3. **Patient Profile**:
    - Average age ~61 years — core population is elderly/adult, so services should focus on age-related conditions, chronic care, and geriatric support.
    - Very few young patients — pediatric services may be low-demand or not a focus area.
    - Strong gender imbalance: more male patients, possibly reflecting health-seeking behavior, occupational risks, or demographic factors in the area.
4. **Geography**:
    - Majority from urban areas; rural patients are fewer — outreach or satellite services could improve access for rural populations.
5. **Treatment Outcomes**:
    - Very high discharge rate (87.3%) shows effective care delivery.
    - Mortality ~7% is within typical ranges for adult/senior care; can be used as baseline for quality improvement.
    - DAMA cases are low, indicating good patient engagement and care acceptance.
## Final Conclusion
This dashboard provides a clear picture of hospital operations and patient characteristics:
- The hospital primarily serves **adult and senior patients**, mostly male, from **urban areas**, with **emergency admissions** as the main entry point.
- Admissions follow a **strong seasonal cycle** and saw a major change between 2017–2019.
- Clinical outcomes are **largely positive**, with high discharge rates.

For action:

- Plan staffing and supplies around peak months (Jan, Nov, Dec) and reduce during low months (Apr, Sep).
- Focus services and training on geriatric, chronic, and emergency care.
- Explore why rural utilization is lower and how to improve access.
- Investigate the 2018–2019 drop in admissions to understand root causes.
This data-driven view supports better planning, resource use, and patient care strategies.
