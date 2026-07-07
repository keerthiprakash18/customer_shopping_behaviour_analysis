# customer_shopping_behaviour_analysis

# Data Analytics Project

A complete end-to-end data analytics project covering data loading, cleaning, exploratory data analysis (EDA), SQL querying, dashboarding, and reporting — built to demonstrate a practical, real-world analytics workflow.

## Overview

This project walks through the full analytics lifecycle: starting from a raw dataset, cleaning and exploring it in Python, querying it with SQL, visualizing insights in Power BI, and packaging the findings into a report and presentation. It's designed to showcase core data analyst skills in a clear, structured, and reproducible way.

## Dataset

- **Source:** *(add dataset name/source/link here)*
- **Format:** CSV / Excel *(update as applicable)*
- **Description:** *(briefly describe what the dataset contains — e.g., number of rows, columns, domain/topic)*
- **Location:** `data/raw/` (raw data) and `data/processed/` (cleaned data)

## Tools & Technologies

| Category            | Tools Used                          |
|---------------------|--------------------------------------|
| Programming          | Python (Pandas, NumPy, Matplotlib/Seaborn) |
| Database             | PostgreSQL / MySQL / SQL Server      |
| Dashboarding         | Power BI                             |
| Reporting            | Word / PDF                           |
| Presentation         | Gamma                                |
| Version Control      | Git & GitHub                         |

## Project Steps

1. **Data Loading**
   - Imported the raw dataset into Python using Pandas.
   - Performed an initial inspection of structure, data types, and missing values.

2. **Data Cleaning**
   - Handled missing values, duplicates, and inconsistent formatting.
   - Standardized column names and data types for downstream analysis.

3. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions, trends, and relationships between variables.
   - Visualized key patterns using Matplotlib/Seaborn.

4. **SQL Querying**
   - Loaded the cleaned dataset into PostgreSQL/MySQL/SQL Server.
   - Wrote SQL queries to extract aggregated insights, KPIs, and answer specific business questions.

5. **Dashboard Creation**
   - Built an interactive Power BI dashboard to visualize key metrics and trends.
   - Included filters/slicers for deeper, self-service exploration.

6. **Reporting**
   - Summarized findings, methodology, and recommendations in a written report.

7. **Presentation**
   - Created a concise, visual presentation using Gamma to communicate results to stakeholders.

## Dashboard

*(Add a screenshot or link to the Power BI dashboard here)*

**Key metrics visualized:**
- *(e.g., Sales trends over time)*
- *(e.g., Revenue by region/category)*
- *(e.g., Customer segmentation)*

## Results

- *(Summarize 2–4 key insights or findings from the analysis)*
- *(Mention any measurable impact or recommendation)*
- *(Link to full report and/or presentation, if hosted)*

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Set up the Python environment**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the data cleaning & EDA notebook/script**
   ```bash
   python scripts/data_cleaning.py
   jupyter notebook notebooks/EDA.ipynb
   ```

4. **Load data into your SQL database**
   - Import the cleaned dataset into PostgreSQL/MySQL/SQL Server using the provided schema in `sql/schema.sql`.
   - Run queries from `sql/queries.sql` to reproduce the analysis.

5. **Open the Power BI dashboard**
   - Open `dashboard/dashboard.pbix` in Power BI Desktop.
   - Refresh the data source to point to your local database.

6. **View the report and presentation**
   - Report: `report/final_report.pdf`
   - Presentation: `presentation/deck_link.txt` (Gamma link)

## Project Structure

```
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── EDA.ipynb
├── scripts/
│   └── data_cleaning.py
├── sql/
│   ├── schema.sql
│   └── queries.sql
├── dashboard/
│   └── dashboard.pbix
├── report/
│   └── final_report.pdf
├── presentation/
│   └── deck_link.txt
├── requirements.txt
└── README.md
```

## Contact

*(Add your name, LinkedIn, email, or portfolio link here)*
