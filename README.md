# Project 1: Excel Coffee Shop Sales Dashboard
Q1-Q2 Sales Dashboard for Coffee Shop 


 ![coffeesalesdashboard](https://github.com/user-attachments/assets/c41416dc-15df-40f1-a345-0fdfbb895e85) 

# Table of Contents 
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Data Analysis and Building the Dashboard](#data-analysis-and-building-the-dashboard)
- [Findings](#findings)
- [Recommendations](#recommendations)

# Project Overview

The goal of this project was to develop a comprehensive Q1-Q2 sales dashboard for a coffee shop solely using Microsoft Excel. This dashboard aims to provide insights into sales performance, customer trends, and product popularity, enabling informed decision-making for business strategies.

# Data Source

The sales data used in this project is the "CoffeeShopSales.xlsx" file. 

# Data Preparation and Cleaning

The initial data preparation/cleaning phase involved:
- Understanding the different columns used in the dataset.
- Inspecting the columns to see if there needed to be any changes to the data.
- Making any necessary changes to clean the data using Power Query. Cleansing steps performed include:
  - Assigning column headers and renaming  
  - Changing data types
  - Removing duplicates + fixing spelling errors in some of the products
  - Breaking up the product detail column to have product size as a separate column
    
# Data Analysis and Building the Dashboard

To create the dashboard visuals, I used pivot tables to organize and segment the sales data. Each visual on the dashboard is built off of its own individual pivot table. 
Slicers and a timeline linked to the pivot tables allow for interactivity and filtering options for end users. Users can click on specific product categories, store locations, and time periods to filter the visuals dynamically, allowing for tailored insights and more in-depth analysis.
There is also a notes page for any clarifications on interacting with the dashboard.


The different pivot tables and visuals they represent


# Findings

- Daily sales follow the same trend of peaking from around 7am through 10am reguardless of the month or store location.
- Besides February being slightly lower than January in sales (likely due to there being less days), sales have been steadily increasing MoM.
- The three different store locations have around 230k total sales (Hell's Kitchen 236.5k, Astoria 232.2k, Lower Manhattan 230k) and follow the very similar top selling product trends in both quarters. 
- The percent of the top 10 selling products compared to total sales by location is Astoria at 80.74%, Lower Manhattan at 78.3%, and Hell's Kitchen at 77.7%. 

# Recommendations


- Evening Sales Initiatives: Explore opportunities to increase sales during slower hours (after 10 AM). Consider offering discounts or special events in the late afternoon or evening to attract customers.
- Morning Promotions: Capitalize on peak hours by offering morning specials (e.g., buy one, get one free, or discounts on certain drinks) to increase foot traffic.
- Diversify Menu: Given the reliance on the top 10 products, consider introducing seasonal items or limited-time offerings to attract customers and keep the menu fresh.

