# COMPLAINTS DATA ANALYSIS & INSIGHT DASHBOARD PROJECT 

## Project Overview
This repository contains a Power BI dashboard for analyzing Indohub restaurant reviews from January'2023 to April'2023. The dashboard provides insights from customer feedback, ratings, and trends over time. The dataset includes reviews and customer information stored in a two different text document file. Data cleaning and transformation were performed using Power Query Editor, and visualizations were created using Power BI. 

## Features
- **KPIs**: Key Performance Indicators for total customers, repeated customer's reviews, number of reviews, and evaluating positive, negative, neutral feedback.

## Data Collection & Preparation:
- Customer.txt and Reviews.txt text files are extracted into PowerBi
- Then, Raw data are prepared based on the KPIs
- Creted Review_Category DAX measure by converting the review text into numerical form as 1,-1,2
  
## Data Exploration:
- Examine the data to uncover the patterns
- Then, created a Text_RC column to categorise the numerical form into categorical format as Positive, Negative, Neutral respectively.
- Once, the data is explored and its ready for the visualization
  
## Data Visualization:
- Bar chart, pie chart, and line graphs representing various aspects of restaurant reviews.
- Interactive filters to drill down into specific time periods and review categories.
  
## File Structure
- **/data**: Contains two sample data files (Customer.txt and Reviews.txt) used for the dashboard.
- **/reports**: Contains the Power BI report file (`Customer_reviews.pbix`).
- **/images**: Contains screenshots of the dashboard.

## Getting Started
### Prerequisites
- Power BI Desktop

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Revathi-Gangadaran/Restaurant_Reviews.git
    ```
2. Open `Customer_reviews.pbix` with Power BI Desktop.

### Usage
- Open the Power BI file and navigate through the different tabs to explore the visualizations.
- Use the filters to interact with the data and gain insights.

## Insights 
- Using Pie Chart it is clear that the rating for the Positive review is higher than negative & neutral 
- Line Chart clearly represents that customer's positive feedback falls in Quarter2, which may affect the sales on further period
- Bar chart represent that March month performs well with high positive ratings.

## Screenshot
![Dashboard Overview](images/dashboard.png)

## Languages Used

![Power BI](https://img.shields.io/badge/PowerBI-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Contact
For any questions or inquiries, please contact [revathigangadaran@gmail.com].

