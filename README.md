# Data Analysis Project: The Effect of Government and Informal Tax on Roadside Traders and Businesses

**Prepared by:** Francis Esther Ozioma  
**Date:** June 12, 2025  
**Tools Used:** Excel (Power Query), Power BI, DAX  
**Dataset Source:** Self-administered survey via Google Forms (500+ respondents across Nigeria)

---

##  Project Overview

This capstone project explores the realities faced by roadside traders and small business owners in Nigeria regarding taxation both formal and informal. The study spans multiple states including Niger, Anambra, Lagos, Kwara, and FCT-Abuja.

Despite only **34.2%** of businesses being officially registered, over **91.60%** still pay taxes — indicating high compliance, but a fragile relationship with government services and enforcement.

The goal was to clean and structure raw survey data, then build two Power BI dashboards tailored to:
- **Government officials** — to understand tax compliance and policy gaps
- **Business owners** — to reflect daily struggles and opportunities for support

---

##  Data Transformation Process

The raw data presented several real-world issues such as:
- Multi-select responses in single cells
- Inconsistent binary formats (Y, yes, YES)
- Currency formatting issues (₦, commas)
- Inconsistent text entries and capitalization

Using **Power Query** and **M language**, the data was:
- Cleaned and standardized
- Split into binary indicator columns for multi-select responses
- Converted to numeric midpoints (e.g., “₦1,000–₦2,000” → 1500)

---

##  Analytical Measures (DAX Examples)

Custom measures in Power BI included:
- **Avg. Daily Profit**: ₦5,907
- **Avg. Daily Tax Paid**: ₦1,900
- **% Registered Businesses**: 34.2%
- **% Tax Payers**: 91.60%
- **Avg. Tax Rate**: ~31.9%
- **Potential Profit If Registered**: ₦6,270

These measures powered dashboards showing compliance levels, economic contribution, and gaps in government service delivery.

---

##  Dashboard Design

Two interactive Power BI dashboards were created:

### 1️⃣ For Government & Policymakers:
- Visualizes business registration, income, tax paid
- Maps tax burden by state and business type
- Highlights informal levies and harassment data
- Recommends focus areas for service improvement and trust-building

### 2️⃣ For Business Owners:
- Allows traders to filter by gender, location, and business type
- Reveals average tax burden vs. income
- Compares registered vs. unregistered outcomes
- Encourages formalization with real data

>  **[Insert Screenshot Here if Available]**

---

##  Key Insights

- Many traders comply with taxes even without formal registration.
- Registered businesses tend to earn more and experience fewer tax issues.
- Over 376 traders reported informal tax harassment.
- Traders want visible returns: cleaner markets, simplified taxes, and respectful engagement.
- Real change requires trust, not just enforcement.

---

##  Files in This Repository
- `survey_dashboard.pbix` – Power BI dashboard file
- `cleaned_data.xlsx` – Excel file with data transformation
- `project_documentation.docx` – Full report detailing methods and findings
- `dashboard_screenshot.png` – Visual of final Power BI output

---

## Recommendations

1. Simplify and promote business registration through mobile awareness campaigns.
2. Link taxes to visible services like sanitation, waste removal, and fumigation.
3. Train tax agents as **supporters**, not enforcers.
4. Develop a **mobile tax diary app** that lets traders:
   - Record payments
   - Track receipts
   - Learn about their rights
   - Register their businesses directly

---

##  Key Learnings

- Real-world data is messy — transformation takes time and context.
- Power Query + M Language are powerful tools for standardizing responses.
- Tailoring dashboards to different audiences makes insights more actionable.
- Building trust is the foundation of compliance and policy success.

---

##  Author

**Francis Esther Ozioma**  
[GitHub Profile](https://github.com/OziomaEsther)  
[LinkedIn Profile](www.linkedin.com/in/francis-esther-ozioma-611ba6230) **

---

> _“To fix tax trust, we must offer visible services, simplified processes, and a voice to the people who pay.”_
