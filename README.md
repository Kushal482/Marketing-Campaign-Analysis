# Marketing-Campaign-Analysis
Built an interactive Power BI dashboard to analyze the effectiveness of various marketing campaigns across regions and platforms. The goal was to help stakeholders understand which campaigns were delivering the best return on investment.
----

Here’s how I approached it technically:
📥Data Preparation:
- I imported data into Power BI from a CSV file (or relevant source).
- Cleaned and transformed the dataset using Power Query—this included renaming columns, changing data types, and removing nulls.
- I ensured proper relationships between tables using the data model view.


✅Measure Creation using DAX:
- I created key DAX measures such as:
   Total Revenue = SUM(Revenue)
   Total Spend = SUM(Spend)
   ROI = DIVIDE([Total Revenue] - [Total Spend], [Total Spend])
   Average ROI = AVERAGE(ROI)
- Also created measures to calculate campaign-level and region-level aggregations.


📊Visualizations:


- Used bar charts to compare total spend and revenue by region.
- Used a combo chart (bar + line) to display both spend and average ROI by campaign name.
- Created a horizontal bar chart for total ROI by campaign to help identify the top-performing ones.
- Added KPI cards at the top to show key metrics like Average ROI, Total Revenue, and Total Spend.
- Used a pie chart to show the split between digital and traditional campaigns.
- Added a gauge visual for total ROI performance at a glance.


➤ Interactivity:

- Used slicers and filters to allow users to view performance by campaign type or region dynamically.
- Configured tooltips to display contextual details on hover for each visual.


**The dashboard helped identify that Influencer Marketing was the most efficient campaign with the highest ROI (1.10), while traditional methods like TV commercials underperformed. This allowed stakeholders to shift budget towards higher-performing channels.
