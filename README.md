# Blinkit Sales Analysis — Python & SQL-Driven Business Intelligence

Welcome to my project!

This analysis dives into Blinkit's grocery retail data to explore sales performance from product types and fat content to outlet sizes and store locations, every dimension is explored to surface actionable insights. The project blends SQL for precise data cleaning and metric generation, Python for robust data preprocessing, exploratory analysis, and insightful visualizations and Power BI for building an interactive dashboard that delivers findings in an interactive and decision-ready format.

---

## Why This Project?

As a certified accounting technician and aspiring data analyst, I embarked on this project to strengthen my analytical thinking and technical fluency using real-world data. My goal was to:
- Sharpen SQL skills through business-specific metrics
- Apply Python for storytelling with data
- Build a clear and interactive dashboard for non-technical audiences
- Improve my fluency with combining multiple tools (SQL + Python + Power BI) in one workflow and in overall,
- Showcase my ability to bridge accounting knowledge with analytics to uncover business value

---

## Tech Stack

- **SQL Server Management Studio (SSMS)** – Mainly For Data cleaning & and business metric extraction
- **Python (Pandas, Matplotlib, Seaborn)** – For Exploratory analysis and visualization
- **Microsoft Power BI** – For data transformation and creating an interactive dashboard
- **Microsoft Excel** – Preliminary data inspection

---

## Dataset Snapshot

The dataset includes details such as:
- `Item Identifier` — Unique product ID  
- `Item Type` — Type/category of item  
- `Item Fat Content` — Fat content (e.g., Low Fat, Regular)  
- `Item Visibility` — Shelf visibility measure  
- `Outlet Identifier` — Unique store ID  
- `Outlet Size` — Store size (Small, Medium, High)  
- `Outlet Type` — Store category (Supermarket Type1, Grocery Store, etc.)  
- `Outlet Location Type` — Tier 1/2/3 city classification  
- `Outlet Establishment Year` — Year the outlet began operation  
- `Sales` — Total sales for each product  
- `Rating` — Customer feedback score (out of 5)

> Dataset contains **8,523** observations and **12** fields

---

## Project Breakdown

### Phase 1: Data Cleaning

Performed in both SQL and Python:
- Standardized fat content categories (`LF`, `low fat`, `reg` → `Low Fat`, `Regular`)
- Verified column data types and renamed for clarity
- Removed any invalid or inconsistent entries

Final clean data enabled consistent aggregation and grouping in subsequent analysis.

---

### Phase 2: KPI & Business Metrics

Using SQL and Python, the following KPIs were calculated:
- **Total Sales:** `$1,201,681`
- **Average Sales:** `$141`
- **Number of Items Sold:** `8,523`
- **Average Rating:** `4.0`

These KPIs provided a strong foundation to assess performance across outlets, product types, and customer segments.

---

### Phase 3: Exploratory Data Analysis (EDA)

#### A. Sales by Product Attributes
- Pie chart of **Sales by Fat Content**
- Bar chart of **Sales by Item Type**

#### B. Sales by Outlet Characteristics
- Bar plot of **Fat Content by Outlet Location Type**
- Line chart of **Total Sales by Outlet Establishment Year**
- Pie chart of **Sales by Outlet Size**
- Bar chart of **Sales by Outlet Location Type**

Each visualization helps business stakeholders identify which items perform best, which locations are most profitable, and how outlet characteristics relate to revenue.

---

## Key Highlights

- Real-world business scenario involving multiple factors
- Full data pipeline: from cleaning → metrics → visual storytelling
- Combines **SQL logic** with **Python plotting**
- Visuals designed for future integration into a **Power BI** dashboard

---

## Known Limitations

- No cost/profit data, so analysis is limited to sales volume
- Dataset is static and not updated in real-time
- Fat content may not be the strongest sales predictor in isolation
- Ratings may be subjective and not validated

---

## File Structure

| File | Description |
|------|-------------|
| `BlinkIT_Grocery_Data.csv` | Raw dataset (to be added) |
| `blinkit_sql_analysis.sql` | SQL queries for data cleaning & KPI generation |
| `blinkit_python_analysis.ipynb` | Python notebook for EDA and plots |
| `blinkit_dashboard.pbix` | Power BI dashboard (coming soon) |
| `README.md` | This documentation file |

---

## Final Thoughts

This project combines my passion for numbers with practical business storytelling. It bridges technical tools (SQL/Python) with decision-ready outputs and will serve as a foundational piece in my transition into full-stack business analytics.

Prepared by:  
**Otun Oluwapelumi Ayodele (AAT)**  
Certified Accounting Technician  
Data Enthusiast | Data Analyst

---

## Let’s Connect

Have feedback, collaboration ideas, or project opportunities?  
I’d love to hear from you:

- Twitter: [@FiscalMindAcct](https://twitter.com/FiscalMindAcct)  
- LinkedIn: [oluwapelumiotun](https://www.linkedin.com/in/oluwapelumiotun)  
- Email: oluwapelumiotun@gmail.com

---

> If this project inspired or helped you, please give it a star!

