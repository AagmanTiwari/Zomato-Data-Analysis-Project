# 🍽️ Zomato Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on Zomato restaurant data using Python.

The main objective is to analyze restaurant-related information, identify meaningful patterns, and solve real-world business questions using data analysis and visualization techniques.

The project includes data exploration, data cleaning, statistical analysis, and visualization to understand restaurant ratings, customer votes, online ordering trends, table booking availability, and approximate dining costs.

This project is part of my hands-on learning journey in Data Analytics and is currently under development.

## 🎯 Project Objectives

- Understand and explore restaurant-related data.
- Perform data cleaning and preprocessing.
- Analyze restaurant ratings and customer votes.
- Identify popular restaurant categories.
- Understand online and offline ordering trends.
- Analyze table booking availability.
- Compare average ratings across restaurant types.
- Explore approximate restaurant costs for two people.
- Solve business problems using data-driven analysis.

## 🛠️ Tech Stack & Tools

| Technology | Purpose |
|---|---|
| Python | Programming and data analysis |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive development and analysis |

## 📂 Dataset Information

The project uses a Zomato restaurant dataset containing **148 records and 7 columns**.

### Dataset Attributes

| Column | Description |
|---|---|
| Restaurant Name | Name of the restaurant |
| Online_Order | Availability of online ordering |
| Book_Table | Whether table booking is available |
| Rate | Restaurant rating |
| Votes | Number of customer votes |
| Approx_Cost(For Two People) | Approximate cost for two people |
| Listed_In(Type) | Restaurant category |

## 🧹 Data Cleaning & Preprocessing

The following data preprocessing operations have been performed:

1. Converted restaurant ratings into numerical values by removing the `/5` format.
2. Standardized column names into lowercase.
3. Renamed the approximate cost column to `cost`.
4. Checked for missing values.
5. Checked for duplicate records.
6. Inspected dataset structure and statistical summaries.

**Data Quality Check:**
- Total Records: 148
- Total Columns: 7
- Missing Values: 0
- Duplicate Records: 0

## 📊 Business Problems Solved

The following 10 business questions have been explored using Python:

### 1. How many customer votes has each restaurant type received?
- Used `groupby()` and `sum()` to calculate total votes for each restaurant category.

### 2. How many restaurants offer table booking?
- Used `value_counts()` to analyze table booking availability.
- Created a pie chart to visualize the distribution.

### 3. Which five restaurants have the highest number of votes?
- Used `nlargest()` to identify the top five restaurants based on customer votes.
- Visualized the results using a horizontal bar chart.

### 4. Is there a relationship between restaurant ratings and customer votes?
- Created a scatter plot to analyze the relationship.
- Calculated correlation and covariance.

### 5. What is the average rating for each restaurant type?
- Used `groupby()` and `agg()` to calculate average ratings for different restaurant categories.

### 6. What type of restaurants do the majority of customers order from?
- Used Seaborn's `countplot()` to compare the number of restaurant records across categories.

### 7. What ratings do restaurants most commonly receive?
- Created a histogram to understand the distribution of restaurant ratings.

### 8. Which restaurant type has the highest average cost for two people?
- Used `groupby()` and `mean()` to calculate and compare average costs across restaurant categories.

### 9. Which ordering mode, online or offline, gets better ratings?
- Used box plots to compare restaurant rating distributions for online and offline ordering.

### 10. Which restaurant type has more offline ordering records?
- Created a Pandas pivot table to compare online and offline ordering records across restaurant categories.
- Used a Seaborn heatmap to visualize the results.

## 📈 Key Analytical Techniques

The project covers the following Python and data analysis concepts:

- Data Loading and Exploration
- Data Cleaning and Preprocessing
- DataFrame Operations
- GroupBy and Aggregation
- Sorting and Filtering
- Statistical Analysis
- Correlation and Covariance
- Pivot Tables
- Data Visualization
- Business Problem Solving

## 📁 Project Structure

```text
Zomato-EDA-Project/
│
├── Zomato EDA Project.ipynb
├── zomato_data.csv
├── README.md
└── requirements.txt
```

*The structure above represents the suggested repository layout. Adjust filenames and folders to match your actual GitHub repository.*

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/AagmanTiwari/Zomato-Data-Analysis-Project.git
```

### 2. Navigate to the Project Directory

```bash
cd Zomato-Data-Analysis-Project
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebook

Open `Zomato EDA Project.ipynb` and execute the cells to explore the analysis.

Make sure `zomato_data.csv` is available in the appropriate working directory.

## 🚀 Future Improvements

- Perform deeper statistical analysis.
- Explore additional restaurant and customer trends.
- Add more business questions and insights.
- Improve data visualizations.
- Build an interactive dashboard using Streamlit or Power BI.
- Document important findings and recommendations.

## 📌 Project Status

**In Progress 🚧**

The initial exploratory analysis and 10 business problem solutions have been implemented. Further analysis, visualizations, and improvements will be added as the project develops.

## 👨‍💻 Author

**Aagman Tiwari**

- GitHub: [AagmanTiwari](https://github.com/AagmanTiwari)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!
