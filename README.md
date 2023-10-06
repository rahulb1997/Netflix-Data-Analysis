Power BI Visualization - Netflix Movies and TV Shows Analysis
This GitHub repository contains the files and instructions to reproduce the Netflix Movies and TV Shows analysis visualization in Power BI. The visualization presents insights into Netflix content based on various attributes such as directors, cast, country, and listed_in categories.

How we did this analysis
Before creating this visualization, we followed these steps to preprocess and prepare the data:

Data Preparation in Excel:

We started with the raw dataset.
We separated the directors, cast, country, and listed_in columns into different columns using the "Text to Columns" feature in Microsoft Excel.
To ensure data cleanliness, we used the TRIM function to remove any extra spaces from both the beginning and end of all the new columns we created.
After cleaning and splitting the data, we organized the information into separate sheets.
The following columns were organized into individual CSV files:
Cast
Country
Description
Director
Listed_in
Data Import into MySQL:

We imported these CSV files into a MySQL database for better data management and organization.
Connecting MySQL to Power BI:

We established a connection between the MySQL database and Power BI to enable data retrieval for visualization.
Getting Started
To recreate the Power BI visualization, follow these steps:

Prerequisites:

Make sure you have Power BI Desktop installed on your machine.
You should have access to a MySQL database with the imported CSV files.
Clone or Download the Repository:

Clone this GitHub repository to your local machine or download it as a ZIP file and extract it.
Open Power BI Desktop:

Launch Power BI Desktop on your computer.
Import Data:

In Power BI Desktop, go to "Home" > "Get Data" > "Database" > "MySQL Database."
Connect to MySQL:

Enter the necessary connection details to connect to your MySQL database where you imported the CSV files.
Import Tables:

Select the relevant tables (e.g., Cast, Country, Description, Director, Listed_in) to import into Power BI.
Create Visualizations:

Use the imported data tables to create your visualizations as per your analysis requirements.
Save and Publish:

Save your Power BI report and publish it to your preferred Power BI service if needed.
