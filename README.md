#  Patient Waitlist Analysis Dashboard - Power BI Project

##  Objective
- Track the current status of the patient waiting list.
- Analyze historical trends in monthly waitlist volumes for Outpatient, Day Case, and Inpatient categories.
- Provide drill-down insights by medical specialty and patient age profiles to support better healthcare planning and resource allocation.


## Questions
- 📊 How many patients are currently on the waitlist, and how does this compare to the previous year?
- 📈 What are the trends in waitlist volumes across case types (Outpatient, Day Case, Inpatient) over time?
- 👶🧓 How do age groups and time bands affect waitlist duration?
- 🩺 Which specialties have the highest average or median waiting times?
- 🕒 What is the distribution of wait times by archive date and how does it vary by case type?

## Process
- Data Source: Patient waitlist data including Archive Date, Case Type, Specialty, Age Profile, and Wait Time metrics.
- Steps:

    - Data Cleaning: Handled missing and inconsistent entries, ensured date format compatibility.

    - Data Modeling: Created relationships between archive date, patient categories, and specialty tables.

    - Visualizations:
      - KPIs for current vs previous month waitlist.
      - Pie chart for case type distribution.
      - Bar charts for waitlist by time bands and age profiles.
      - Line graphs for time series analysis.
      - Drill-down table for detailed breakdowns by specialty and age.

## Project Insights
- Outpatient cases dominate the waitlist, forming over 70% of the total, with the remainder split between day cases and inpatient care.
- The longest wait times were observed in older age bands (65+) and for certain specialties like Cardiology.
- Historical data shows a gradual increase in outpatient waitlists starting mid-2019, peaking around 2021.
- Certain specialties (e.g., Clinical Immunology, Cardio-Thoracic Surgery) experience relatively higher average wait times, indicating potential bottlenecks or under-resourced departments.
- The dashboard’s filters enable dynamic exploration of the waitlist by date range, specialty, case type, age group, and time bands.

## Final Conclusion
This dashboard delivers a comprehensive and interactive overview of patient waiting lists across multiple dimensions. It helps healthcare administrators and policymakers:

- Monitor capacity and backlog.
- Allocate resources to high-wait areas.
- Identify trends in specific specialties or age groups for strategic decision-making.

