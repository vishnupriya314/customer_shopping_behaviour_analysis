# Customer_Shopping_Behaviour_Analysis
An end-to-end data analytics project focused on analyzing customer purchase records to identify shopping patterns, customer segments, product preferences, and subscription trends using Python, PostgreSQL, and Power BI. The project transforms raw transactional data into meaningful business insights through data cleaning, exploratory data analysis (EDA), SQL-based analysis, and interactive dashboard development.

## 1. Dataset

The project uses a customer shopping behavior dataset containing customer demographic information, purchase details, product preferences, and shopping habits.

The dataset includes attributes such as:
- Customer demographics: Age, Gender, Location
- Purchase information: Item Purchased, Category, Purchase Amount, Season, Size, Color
- Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases
- Customer feedback: Review Rating
- Order details: Shipping Type, Subscription Status

The dataset was examined and preprocessed to handle missing values, standardize column names, and improve data consistency before analysis.

## 2. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas & NumPy | Data manipulation and preprocessing |
| Matplotlib & Seaborn | Data visualization |
| PostgreSQL | SQL-based business analysis |
| Power BI | Interactive dashboard development |
| Jupyter Notebook | Python development and analysis |

## 3. Project Workflow

### Step 1: Data Loading & Exploration
- Imported the dataset into Python using Pandas.
- Examined dataset structure, data types, and summary statistics.
- Identified missing values and potential data inconsistencies.

### Step 2: Data Cleaning & Preprocessing
- Handled missing values in the Review Rating column using category-wise median imputation.
- Standardized column names using snake_case.
- Created age groups through feature engineering.
- Derived purchase frequency metrics.
- Identified redundant columns and removed unnecessary fields.

### Step 3: SQL Analysis using PostgreSQL

Imported the cleaned dataset into PostgreSQL and performed SQL-based analysis to explore customer purchasing behavior and identify business insights.

- Analyzed revenue distribution across customer demographics and age groups.
- Evaluated spending patterns of discount users and subscribers.
- Identified top-rated and best-selling products across categories.
- Compared purchasing trends across different shipping methods.
- Analyzed discount dependency across products.
- Segmented customers into New, Returning, and Loyal groups based on purchase history.
- Examined the relationship between repeat purchases and subscription adoption.

### Step 4: Power BI Dashboard

Developed an interactive Power BI dashboard to present key performance indicators and customer shopping insights.

**Dashboard Highlights:**
- Total number of customers
- Average purchase amount
- Average product rating
- Customer distribution by subscription status
- Revenue and sales by product category
- Revenue and sales by age group
- Interactive filters for gender, subscription status, category, and shipping type

### Step 5: Business Insights & Recommendations

Derived actionable recommendations based on the analysis:

- Encourage subscription adoption through exclusive benefits.
- Introduce loyalty programs to retain repeat customers.
- Review discount strategies to balance sales and profitability.
- Promote top-rated and best-selling products.
- Focus marketing campaigns on high-revenue customer segments.

## 4. Dashboard Preview

The Power BI dashboard provides an interactive overview of customer purchasing behavior, revenue distribution, subscription patterns, and product performance.

![Customer Shopping Behavior Dashboard](https://github.com/vishnupriya314/customer_shopping_behaviour_analysis/blob/main/Customer%20Behaviour%20Dashboard.pbix)

## 5. Key Results

- Analyzed customer purchase records to understand shopping behavior.
- Identified customer segments: New, Returning, and Loyal.
- Analyzed subscription patterns and customer spending behavior.
- Identified high-revenue age groups and product preferences.
- Evaluated discount dependency, product ratings, and shipping preferences.
- Developed business recommendations to improve customer retention and subscription growth.

## 6. How to Run the Project

### Prerequisites
- Python 3.x
- Jupyter Notebook
- PostgreSQL
- pgAdmin 4
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd customer_shopping_behaviour_analysis
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
```

### Step 3: Run Python Analysis
- Open the Jupyter Notebook.
- Update the dataset path if required.
- Execute the cells to explore, clean, and preprocess the dataset.
- Configure your PostgreSQL connection details.

### Step 4: Run SQL Queries
- Create a database in PostgreSQL.
- Load the cleaned dataset into the database.
- Open the SQL script in pgAdmin 4.
- Execute the queries to reproduce the business analysis.

### Step 5: Open Power BI Dashboard
- Open the `.pbix` file using Power BI Desktop.
- Update the data source connection if required.
- Refresh the dataset to view the dashboard.

## 7. Project Deliverables

- Python notebook containing data cleaning and EDA.
- PostgreSQL SQL scripts for business analysis.
- Interactive Power BI dashboard.
- Project documentation and business recommendations.

---
