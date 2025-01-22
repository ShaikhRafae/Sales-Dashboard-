This project demonstrates the creation of a dynamic Power BI dashboard designed to track and analyze key metrics—Sales, Profit, and Quantity—across four regions: Central, East, South, and West. I built this dashboard using Power BI to provide an interactive experience where users can filter and compare metrics based on the selected year, and dynamically switch between Sales, Profit, and Quantity. Here's an overview of how the project was created using various Power BI features and visualizations.

Project Development:
Data Import & Preparation:

I began by importing the necessary datasets containing Sales, Profit, and Quantity data for each region (Central, East, South, and West) over multiple years. Data cleaning and transformation were performed using Power Query to ensure that the dataset was ready for analysis.
I created calculated columns to calculate Year-over-Year (YoY) growth for Sales, Profit, and Quantity to provide more insights into performance trends.
Regional Metrics:

I used slicer filters to allow users to select the desired year for analysis. The dashboard automatically updates to show Sales, Profit, and Quantity data for the selected year across all regions.
To allow users to toggle between Sales, Profit, and Quantity, I employed buttons and bookmarks for dynamic switching of the displayed metrics.
Bar Sparklines were added for each region to show monthly trends for Sales, Profit, and Quantity. An average line was incorporated to provide a visual benchmark for performance evaluation.
Sales by State:

I used a Bubble Map to visualize the distribution of sales across different states. The size of each bubble was determined by the sales volume, providing an intuitive way to identify regions with high or low sales performance.
In addition to the map, I included a Bar Chart to complement the bubble map. The bar chart displays the exact sales numbers for each state and allows easy comparison of sales across states. Sorting options were added to let users rank states by sales volume.
Key Metrics Table/Grid:

A Table/Grid was created to display key metrics for both the current year (CY) and previous year (PY). This includes:
CY Sales, PY Sales, and YoY Sales Growth.
CY Profit, PY Profit, and YoY Profit Growth.
CY Quantity, PY Quantity, and YoY Quantity Growth.
Conditional formatting was applied to highlight significant growth or decline in the metrics.
Interactivity:

I integrated several interactive elements such as slicers and filters to enhance the user experience. These elements allow users to filter data by year, region, and metric (Sales, Profit, Quantity), enabling them to dynamically explore different perspectives of the data.
Visualization Techniques:

For visualization, I employed a variety of Power BI charts including:
Bar Charts for regional comparison.
Line Charts for trend analysis over time.
Pie Charts for proportional distribution across states.
Sparklines for quick visual trends in monthly data.
Maps for geographical sales distribution.
I also used DAX formulas to calculate Year-over-Year growth and other custom metrics, ensuring accurate comparisons and insights.
