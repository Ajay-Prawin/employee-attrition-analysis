# Employee Attrition Analysis

**End-to-End Data Analysis Project: Python → SQL → Power BI**

[![Project Status](https://img.shields.io/badge/Status-Complete-brightgreen)](https://github.com/Ajay-Prawin/employee-attrition-analysis)
[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-MySQL-orange)](https://www.mysql.com/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)](https://powerbi.microsoft.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Project Overview

An comprehensive HR analytics project analyzing employee attrition patterns using the IBM HR Analytics dataset. This project demonstrates the complete data science workflow from data cleaning to interactive dashboard creation.

**Key Objective:** Identify factors influencing employee turnover and provide actionable insights for HR retention strategies.

## Technologies Used

- **Python**: Data cleaning, EDA, and visualization (Pandas, Matplotlib, Seaborn)
- **MySQL**: Database management and analytical queries
- **Power BI**: Interactive dashboard development
- **Excel**: Data validation and supplementary analysis

## Dataset Information

- **Source**: IBM HR Analytics Employee Attrition & Performance Dataset
- **Records**: 1,470 employees
- **Features**: 34 variables including demographics, job details, compensation, and satisfaction metrics
- **Target Variable**: Employee Attrition (Yes/No)

## Project Workflow

### 1. Data Preparation (Python)
```python
# Key preprocessing steps
- Handled missing values and duplicates
- Data type validation and conversion
- Feature engineering (Age Groups, Salary Ranges)
- Exploratory Data Analysis with visualizations
```

### 2. Database Analysis (SQL)
```sql
-- Sample analytical queries
- Total attrition rate calculation
- Department-wise turnover analysis
- Salary distribution comparisons
- Job role attrition breakdown
```

### 3. Dashboard Creation (Power BI)
- Interactive visualizations with drill-down capabilities
- KPI cards for key metrics
- Multi-dimensional analysis charts
- Consistent color coding and professional styling

## Key Insights

| Metric | Value | Insight |
|--------|-------|---------|
| **Overall Attrition Rate** | 16.12% | 237 out of 1,470 employees left |
| **Highest Attrition Department** | Sales | 20.63% turnover rate |
| **Most Affected Age Group** | 25-34 years | Younger employees show higher turnover |
| **Marital Status Impact** | Single | Higher attrition among unmarried employees |

### Business Recommendations

1. **Targeted Retention Programs**: Focus on young, single employees with mentorship and engagement initiatives
2. **Department-Specific Strategies**: Review compensation and work environment in Sales and R&D departments  
3. **Career Development**: Implement structured promotion paths for high-attrition job roles
4. **Exit Interview Analysis**: Conduct systematic exit interviews to understand role-specific issues

## Repository Structure

```
├── data/
│   ├── raw/                    # Original dataset
│   ├── processed/              # Cleaned data files
│   └── sql_exports/            # Query output CSVs
├── notebooks/
│   ├── 01_data_cleaning.ipynb  # Data preprocessing
│   ├── 02_exploratory_analysis.ipynb  # EDA and visualizations
│   └── 03_statistical_analysis.ipynb  # Advanced analytics
├── sql_queries/
│   ├── attrition_analysis.sql  # Core business queries
│   ├── demographic_analysis.sql # Demographic breakdowns
│   └── compensation_analysis.sql # Salary-related queries
├── dashboard/
│   ├── attrition_dashboard.pbix # Power BI file
│   └── dashboard_screenshots/   # Visual outputs
├── reports/
│   └── project_summary.pdf     # Executive summary
└── README.md
```

## Dashboard Preview

![Dashboard Overview](dashboard/dashboard_screenshots/main_dashboard.png)

**Dashboard Features:**
- Real-time KPI monitoring (Attrition Rate, Total Employees, Status)
- Interactive filtering by department, job role, and demographics
- Visual breakdown by age groups, marital status, and education field
- Professional color coding (Red: Attrition, Green: Retention)

## Technical Highlights

- **Data Quality**: Comprehensive data validation and cleaning process
- **Statistical Analysis**: Chi-square tests for categorical relationships
- **Visualization Best Practices**: Consistent color schemes, clear labeling, and intuitive layouts
- **Performance Optimization**: Efficient SQL queries and optimized Power BI data model

## Skills Demonstrated

- **Data Analysis**: End-to-end analytical thinking and problem-solving
- **Programming**: Python for data manipulation and visualization
- **Database Management**: SQL query optimization and data extraction
- **Business Intelligence**: Dashboard design and storytelling with data
- **Communication**: Translating technical findings into business recommendations

## How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/employee-attrition-analysis.git
   cd employee-attrition-analysis
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas matplotlib seaborn numpy jupyter
   ```

3. **Set up MySQL database**
   - Import the dataset into MySQL Workbench
   - Run the SQL queries from the `sql_queries/` folder

4. **Open Power BI Dashboard**
   - Open `dashboard/attrition_dashboard.pbix` in Power BI Desktop
   - Refresh data connections if needed

## Contact

**Ajay** - [ajayprawwinsk@gmail.com] - [[Your LinkedIn](https://www.linkedin.com/in/ajay-prawinsk/)]

Project Link: [https://github.com/Ajay-Prawin/employee-attrition-analysis](https://github.com/yourusername/employee-attrition-analysis)

---

If you found this project helpful, please give it a star!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*This project demonstrates practical application of data science techniques for solving real-world HR challenges. The insights and methodologies can be adapted for similar workforce analytics initiatives.*
