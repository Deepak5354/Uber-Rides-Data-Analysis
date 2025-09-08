# Uber-Rides-Data-Analysis


## Project Description
This project analyzes Uber ride data to uncover patterns in **ride categories, purposes, and distances**. It demonstrates **data cleaning, preprocessing, exploratory data analysis (EDA), and visualization** using Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**.

### Key Objectives
- Understand ride patterns for **Business vs Personal trips**
- Explore trip **purposes** and **distance distribution**
- Visualize trends over time (monthly and hourly)
- Generate actionable **business insights** from raw data

### Skills & Tools
Python | Pandas | NumPy | Matplotlib | Seaborn | Data Cleaning | EDA | Data Visualization

### Steps Performed
1. **Imported Dataset**: Loaded Uber rides CSV file
2. **Data Cleaning**: Handled missing values, converted date columns, removed duplicates
3. **Exploratory Data Analysis (EDA)**: Checked unique values, categories, purposes, and miles distribution
4. **Data Visualization**:
   - Count plots for Category and Purpose
   - Boxplots for Miles
   - Distribution plots for Miles
   - Stacked bar charts and trend lines over time
5. **Insights**:
   - Business rides are higher than personal rides
   - Most long-distance trips are business-related
   - Peak rides occur on weekdays
   - Monthly ride trends and purpose-category patterns

### Dataset
The dataset includes:
- `CATEGORY` (Business / Personal)
- `PURPOSE` (Meeting, Meal, etc.)
- `MILES` (Distance traveled)
- `START_DATE` & `END_DATE` (DateTime of ride)
- Other ride-related information

### Screenshots
![Category vs Purpose](screenshots/category_purpose.png)
![Miles Distribution](screenshots/miles_distribution.png)
![Rides Trend](screenshots/rides_trend.png)

### Outcome
This project transforms raw Uber ride data into meaningful insights, helping understand **user behavior, peak ride times, and trip patterns**, while showcasing strong **data analysis and visualization skills**.

### How to Run
1. Clone the repository:  
```bash
git clone https://github.com/Deepak5354/Uber-Rides-Data-Analysis.git
