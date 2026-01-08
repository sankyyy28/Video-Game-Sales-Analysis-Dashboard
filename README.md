
#  Video Game Sales Analysis Dashboard (Power BI)

##  Project Overview

This project analyzes global video game sales data to uncover trends across regions, platforms, genres, and publishers.
Using **Power BI**, an interactive dashboard was created to help users understand market performance, top-selling games, and sales distribution over time.

The dataset used contains historical video game sales information from multiple regions, making it suitable for business intelligence and data visualization purposes.

##  Dataset Information

* **Dataset Name:** Video Game Sales Dataset
* **Source:** Provided CSV/Excel file (used as project dataset)
* **File Used:** `vgsales_final.xlsx`
* **Records:** Video game sales data across multiple years
* **Key Columns:**

  * `Name` – Game title
  * `Platform` – Gaming platform (PS4, Xbox, PC, etc.)
  * `Year` – Release year
  * `Genre` – Game genre
  * `Publisher` – Publishing company
  * `NA_Sales` – North America sales (in millions)
  * `EU_Sales` – Europe sales
  * `JP_Sales` – Japan sales
  * `Other_Sales` – Other regions
  * `Global_Sales` – Total worldwide sales

##  Objectives

* Analyze **global and regional video game sales**
* Identify **top-performing games, genres, platforms, and publishers**
* Understand **sales trends over time**
* Build an **interactive and user-friendly Power BI dashboard**

##  Tools & Technologies

* **Power BI Desktop** – Data modeling & dashboard creation
* **Excel** – Dataset preprocessing
* **DAX** – Measures and calculated fields

##  Dashboard Features

###  Home Page

* Overview of global video game sales
* Key KPIs:

  * Total Global Sales
  * Total Games
  * Top Platform
  * Top Genre
* Navigation buttons to different report pages

### Visual Insights

* Global sales by **Year**
* Sales distribution by **Region**
* Top **10 Games by Global Sales**
* Sales by **Genre and Platform**
* Publisher-wise performance

###  Interactivity

* Slicers for:

  * Year
  * Platform
  * Genre
  * Publisher
* Dynamic charts and drill-down capabilities

##  Data Cleaning & Preparation

* Converted `Year` column to numeric format
* Handled missing values in Publisher and Year
* Ensured consistent data types
* Created calculated measures using DAX

##  Project Files

* `vgsales_final.xlsx` – Cleaned dataset
* `VideoGame Sales Dashboard.pbix` – Power BI dashboard file
* `README.md` – Project documentation

##  How to Use

1. Download the `.pbix` file
2. Open it using **Power BI Desktop**
3. Ensure the dataset path is correctly mapped
4. Interact with slicers and visuals to explore insights

##  Key Insights

* Action and Sports genres dominate global sales
* Certain platforms show strong regional preferences
* A small number of publishers contribute to a large portion of total sales
* Global video game sales peaked during specific years

##  Future Enhancements

* Add more recent sales data
* Include user ratings and reviews
* Predict future sales using machine learning
* Create mobile-optimized Power BI views

