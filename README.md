# Kickstarter-Crowdfunding-Analysis-Dashboard
# Kickstarter Crowdfunding Analysis Dashboard

## 📌 Project Overview

This project analyzes **Kickstarter crowdfunding campaigns** to understand project performance, funding trends, backer behavior, campaign outcomes, and factors associated with successful and unsuccessful projects.

The analysis was performed using **MySQL, Excel, Power BI, and Tableau**, combining data cleaning, SQL analysis, exploratory analysis, KPI development, and interactive dashboard creation.

The main goal was to transform crowdfunding campaign data into meaningful insights that can help understand **funding performance, project success, category trends, and backer engagement**.

---



---

## 🛠️ Tools & Technologies

| Tool                | Purpose                                                             |
| ------------------- | ------------------------------------------------------------------- |
| **MySQL**           | Data querying, filtering, aggregation, and analysis                 |
| **Microsoft Excel** | Data cleaning, Pivot Tables, calculations, and exploratory analysis |
| **Power BI**        | Interactive dashboard development and KPI analysis                  |
| **Tableau**         | Interactive visualization and dashboard development                 |
| **SQL**             | Data segmentation and business analysis                             |

---

# 📊 Dataset

The dataset contains information about Kickstarter crowdfunding projects, including:

* Project name
* Category
* Subcategory
* Country
* Project status/outcome
* Funding goal
* Amount pledged
* Number of backers
* Campaign duration
* Launch date
* Deadline
* Project-related attributes

The dataset was cleaned and prepared before performing analysis and creating dashboards.

---

# 🔄 Project Workflow

```text
Raw Kickstarter Dataset
          ↓
Data Understanding
          ↓
Data Cleaning & Validation
          ↓
MySQL Data Analysis
          ↓
Excel Exploratory Analysis
          ↓
KPI & Metric Development
          ↓
Power BI Dashboard
          ↓
Tableau Dashboard
          ↓
Business Insights
```

---

# 🧹 1. Data Cleaning & Preparation

The first step was to understand the dataset and prepare it for analysis.

### Data preparation included:

* Identifying missing values
* Checking duplicate records
* Reviewing data types
* Standardizing category and country values
* Cleaning project outcome/status fields
* Formatting date fields
* Validating funding-related numerical fields
* Creating calculated fields where required
* Preparing data for SQL and BI analysis

Excel was used for initial data exploration and validation, while MySQL was used for structured data analysis.

---

# 🗄️ 2. MySQL Analysis

MySQL was used to analyze the crowdfunding dataset and answer key business questions.

### SQL analysis included:

* Number of projects by category
* Number of projects by country
* Successful vs unsuccessful projects
* Total funding raised
* Average funding goal
* Average amount pledged
* Number of backers
* Success rate by category
* Funding performance by country
* Funding goal vs project outcome
* Campaign duration analysis
* Backer activity analysis

### Example SQL Query

```sql
SELECT
    category,
    COUNT(*) AS total_projects,
    SUM(pledged) AS total_pledged,
    AVG(goal) AS avg_funding_goal
FROM kickstarter_projects
GROUP BY category
ORDER BY total_projects DESC;
```

This query helps compare project volume, total funding, and average funding goals across categories.

---

# 📗 3. Excel Analysis

Excel was used for exploratory analysis and validation.

### Excel techniques used:

* Pivot Tables
* Pivot Charts
* Filters
* Conditional Formatting
* Calculated Metrics
* Data Cleaning
* Aggregation
* Category-level analysis
* Outcome analysis

### Key Pivot Table Analysis

Projects were analyzed by:

* Category
* Subcategory
* Country
* Outcome
* Funding Goal
* Amount Pledged
* Number of Backers
* Campaign Duration
* Time Period

Pivot Tables helped identify trends and validate the results before dashboard development.

---

# 📈 4. Power BI Dashboard

An interactive Power BI dashboard was developed to monitor Kickstarter project performance.

### Key KPIs

The dashboard includes metrics such as:

* **Total Projects**
* **Successful Projects**
* **Failed Projects**
* **Canceled Projects**
* **Total Funding Goal**
* **Total Amount Pledged**
* **Total Backers**
* **Average Funding Goal**
* **Average Amount Pledged**
* **Project Success Rate**

### Dashboard Features

* KPI cards
* Bar charts
* Line charts
* Donut charts
* Tables
* Slicers
* Interactive filters
* Category analysis
* Country analysis
* Outcome analysis
* Time-based analysis

Users can interact with the dashboard to compare crowdfunding performance across different categories, countries, outcomes, and time periods.

---

# 📊 5. Tableau Dashboard

A Tableau dashboard was created to provide another interactive view of the Kickstarter dataset.

### Analysis included:

* Project performance by category
* Successful vs unsuccessful projects
* Funding trends
* Country-level project activity
* Backer analysis
* Funding goal analysis
* Campaign duration
* Project success rates

Tableau was used to create interactive visualizations and make it easier to explore relationships between project characteristics and outcomes.

---

# 💰 6. Funding Analysis

A major part of the project was comparing the **funding goal** with the **amount actually pledged**.

The analysis examined:

* Projects that exceeded their funding goals
* Projects that reached their funding goals
* Projects that failed to reach their goals
* Average funding goals by category
* Average pledged amount by category
* Funding performance by country

This helped identify categories and project types with stronger funding performance.

---

# 👥 7. Backer Analysis

Backer activity was analyzed to understand audience engagement.

The analysis focused on:

* Total number of backers
* Average backers per project
* Backers by category
* Backers for successful vs unsuccessful projects
* Relationship between backers and amount pledged

This helped identify whether projects with stronger backer participation also tended to achieve better funding outcomes.

---

# ⏱️ 8. Campaign Duration Analysis

Campaign duration was analyzed to understand whether the length of a campaign was associated with project outcomes.

The analysis compared:

* Campaign duration
* Funding goal
* Amount pledged
* Number of backers
* Project outcome

This provided additional insight into how campaign characteristics may relate to crowdfunding performance.

---

# 📐 9. Key Metrics

### Project Success Rate

```text
Success Rate =
Successful Projects / Total Projects × 100
```

### Funding Achievement Rate

```text
Funding Achievement Rate =
Amount Pledged / Funding Goal × 100
```

### Average Pledged Amount

```text
Average Pledged =
Total Amount Pledged / Number of Projects
```

### Average Backers

```text
Average Backers =
Total Backers / Number of Projects
```

These metrics were used across the dashboards to evaluate project and campaign performance.

---

# 🔍 10. Key Business Questions

The analysis was designed to answer:

1. Which categories have the most crowdfunding projects?
2. Which categories have the highest success rates?
3. Which countries have the highest project activity?
4. Which categories generate the highest funding?
5. What percentage of projects successfully reach their funding goals?
6. How does the funding goal affect project outcomes?
7. Do successful projects attract more backers?
8. How does campaign duration vary across project outcomes?
9. Which categories show stronger backer engagement?
10. Which project characteristics are commonly observed among successful campaigns?

---

# 💡 11. Key Insights

The analysis helped identify patterns related to:

* Project success and failure rates
* Category-level crowdfunding performance
* Country-level project activity
* Funding goals and actual pledged amounts
* Backer engagement
* Campaign duration
* Funding performance across different project categories
* Differences between successful and unsuccessful projects




-

# 🚀 Skills Demonstrated

### Data Analysis

* Exploratory Data Analysis
* Data Cleaning
* Data Transformation
* Trend Analysis
* Business Analysis
* Performance Analysis

### MySQL / SQL

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* Aggregate Functions
* CASE Statements
* Filtering
* Data Segmentation

### Excel

* Pivot Tables
* Pivot Charts
* Data Cleaning
* Calculated Metrics
* Conditional Formatting
* Exploratory Analysis

### Power BI

* Dashboard Development
* KPI Cards
* Slicers
* Interactive Visualizations
* Data Modeling
* DAX Measures

### Tableau

* Interactive Dashboards
* Filters
* KPI Visualization
* Trend Analysis
* Category Analysis
* Geographic Analysis

---

# 🎓 Learning Outcomes

Through this project, I strengthened my ability to:

* Analyze crowdfunding datasets using **SQL and Excel**.
* Clean and prepare data for business analysis.
* Develop KPIs and performance metrics.
* Build interactive dashboards using **Power BI and Tableau**.
* Analyze project success and funding performance.
* Understand relationships between funding goals, backers, and outcomes.
* Convert raw data into meaningful business insights.
* Present analytical findings through interactive visualizations.

---

# 👨‍💻 Conclusion

The **Kickstarter Crowdfunding Analysis Dashboard** demonstrates an end-to-end data analytics workflow, from data cleaning and SQL analysis to Excel exploration and interactive Power BI/Tableau dashboard development.

The project showcases the ability to work with crowdfunding data, analyze project performance, identify funding and backer trends, and communicate insights through business-focused data visualization.
