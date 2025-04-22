# Page-View-Time-Series-Visualizer-with-Python


**Project Description**:  
This Python project visualizes time series data using line charts, bar charts, and box plots. The dataset used contains daily page views on the freeCodeCamp.org forum from May 9, 2016, to December 3, 2019. The goal of this project is to help you visualize and analyze patterns of website traffic, including yearly and monthly growth, using **Pandas**, **Matplotlib**, and **Seaborn**.

---

### **Table of Contents**:
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [License](#license)

---

### **Project Overview**:
- **Objective**: Visualize time series data to identify patterns, trends, and growth in daily page views on the freeCodeCamp.org forum.
- **Dataset Source**: The data is from freeCodeCamp.org and contains page view data from May 2016 to December 2019.
- **Key Tasks**: 
  - Clean the data by removing outliers (top and bottom 2.5% of values).
  - Create three types of visualizations:
    - **Line Chart**: Daily page views over time.
    - **Bar Chart**: Monthly average daily page views grouped by year.
    - **Box Plot**: Distribution of page views over time for both years and months.

---

### **Technologies Used**:
- Python 3 🐍
- Pandas 📊
- Matplotlib 📉
- Seaborn 📦
- Git & GitHub 🦸‍♀️

---

### **Features**:
- **Data Cleaning**: Filters out the top and bottom 2.5% of the page view data to remove outliers.
- **Line Chart**: Draws a line chart to visualize daily page views over the entire period (May 2016 to December 2019).
- **Bar Chart**: Creates a bar chart to show the average daily page views per month, grouped by year.
- **Box Plot**: Draws two adjacent box plots to visualize trends (year-wise) and seasonality (month-wise) in the data.
  
---

### **Getting Started**:

1. **Clone the repository**:

 
git clone https://github.com/your-username/page-view-time-series-visualizer.git
2. **Install dependencies:

Ensure that you have Python 3 installed. You can install the necessary Python packages by running:

 
pip install pandas matplotlib seaborn
3. **Run the project**:

The main script for the project is time_series_visualizer.py. To run the visualizations, execute the following command:
 
python time_series_visualizer.py
3. **Testing**:

The unit tests for this project are in test_module.py. To ensure the code works as expected, you can run the tests using:

 
pytest test_module.py
## **Usage:**
The project reads a CSV file containing page view data for the freeCodeCamp forum. It cleans the data by filtering out extreme values (top 2.5% and bottom 2.5%) and then generates the following visualizations:

Line Chart: Displays daily page views from May 2016 to December 2019.

Bar Chart: Shows average page views per month, grouped by year.

Box Plot: Displays two box plots:

Year-wise Box Plot (Trend): Displays the distribution of page views per year.

Month-wise Box Plot (Seasonality): Displays the distribution of page views per month to analyze seasonality.

## **License:**
This project is licensed under the MIT License - see the LICENSE file for details.

