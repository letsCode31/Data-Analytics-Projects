# Zomato Restaurant Analysis

## Overview
This project analyzes a dataset of Zomato restaurants to uncover key insights about ratings, votes, costs, and other features. 

## Dataset
The dataset contains the following columns:
- **name**: Name of the restaurant.
- **online_order**: Whether the restaurant accepts online orders (Yes/No).
- **book_table**: Whether the restaurant allows table booking (Yes/No).
- **rate**: Customer rating (e.g., 4.1/5).
- **votes**: Number of votes received by the restaurant.
- **approx_cost**: Approximate cost for two people.
- **listed_in(type)**: Category of the restaurant (e.g., Buffet, Cafes).

---

## Objectives
I will be using the dataset to answer the below questions:
- What percentage of restaurants provide online ordering services and how many have table booking?
- What are the most common restaurant types in the dataset?
- Which restaurant types have online ordering and table booking?
- What is the average cost for two people overall and across different restaurant types?
- What is the average rating across all restaurants and average across various types?
- Total number of votes and average votes per restaurant across restaurant types
- Is there a relationship between online ordering and customer ratings?
- Is there a relationship between online ordering and votes?
- Is there a relationship between booking table and customer ratings?
- Is there a relationship between booking table and votes?
- Is there a relationship between cost and customer ratings or votes?
- How does the number of votes affect a restaurant's rating?
- Which restaurant features (e.g., online ordering, table booking) are most likely to drive higher ratings and votes?
- Which restaurant categories should Zomato prioritize for promotions or partnerships?

---

## Visualizations
- **Scatter Plots**: To visualize relationships between features like cost, votes, and ratings.
- **Box Plots**: To compare distributions of ratings and votes based on online ordering and table booking availability.
- **Correlation Matrix**: Heatmap showing relationships between all numeric features.
- **Priority Score Bar Chart**: Ranking restaurant categories for promotions based on combined metrics.

---

## Tools and Libraries
- **Python**: Data analysis and visualization.
- **Pandas**: Data manipulation and grouping.
- **Seaborn**: Statistical visualizations (scatter plots, box plots, heatmaps).
- **Matplotlib**: Custom visualizations.
- **Scikit-learn**: Regression analysis for feature importance.

---
