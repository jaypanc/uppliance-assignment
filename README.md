# Uppliance-assignment

## Cooking Sessions and User Orders Analysis

### Project Overview
This project focuses on cleaning, merging, and analyzing data from three datasets:

- **UserDetails**: Information about users including age, location, and favorite meal.
- **CookingSessions**: Details about cooking sessions including dish names, meal types, and session ratings.
- **OrderDetails**: Data on user orders, including order status, amounts, and ratings.

The goal is to extract actionable insights and create visualizations to inform business decisions, such as identifying popular dishes, understanding demographic influences, and exploring relationships between cooking sessions and orders.

---

### Data Analysis Objectives

1. **Data Cleaning & Merging**: Standardize and combine data from multiple sources to create a unified dataset.
2. **Insights**:
   - Analyze the relationship between cooking sessions and user orders.
   - Identify popular dishes.
   - Explore demographic factors that influence user behavior.
3. **Visualizations**:
   - Pivot tables and plots to highlight key findings.
   - Bar charts, line charts, and stacked bar plots for insights.
4. **Recommendations**:
   - Provide actionable suggestions based on the analysis.

---

### Key Insights

1. **Most Popular Dishes**:
   - **Spaghetti** and **Grilled Chicken** were frequently ordered dishes.
   - Dinners had higher session ratings compared to other meal types.

2. **Demographic Trends**:
   - New York, Chicago and Los Angles are top performing locations contributing to **54%** of total revenue.
   - Users aged 20-30 preferred Dinner.

4. **Correlation Between Sessions & Orders**:
   - Sessions with higher ratings led to more frequent orders.
     
---



### Business Recommendations

1. Focus marketing efforts on Dinner promotions, as it is the most preferred meal type.
2. Provide personalized offers based on user location and age group preferences.
3. Improve session engagement to boost order ratings and overall satisfaction.

---

### Requirements

1. Libraries
   - Numpy `py -m pip install numpy`
   - Pandas `py -m pip install pandas`
   - Plotly `py -m pip install plotly`
