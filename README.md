# IMF-Assessment
This repository consists of all the required files and information based on the two test questions received.

There are two folders, PowerBI and Python

1. PowerBI : Documentation, .pbix file
2. Python : Excel file, economic_analysis.py

[PYTHON Question]

Economic Data Analysis Script
This Python script processes economic data (GDP growth and inflation) for several countries, generates analytical charts, and exports all findings to an Excel file.
Prerequisites & Installation
To run this script, you need Python installed along with the following libraries:
pip install pandas matplotlib seaborn xlsxwriter

How to Run
Save the provided Python code as economic_analysis.py on your computer.
Open your terminal or command prompt.
Navigate to the directory where you saved economic_analysis.py.
Execute the script using:
python economic_analysis.py


Understanding the Output
After running the script, you will see the following:
1. Console Output: A "Summary Table" will be printed directly in your terminal, showing the average GDP growth and inflation rates per country over the 2015-2024 period.
2. Chart Windows: Two separate pop-up windows will appear, displaying:
3. A line chart showing GDP growth trends for each country from 2015-2024.
4. A bar chart comparing inflation rates across countries specifically for 2024.
5. Generated Files (in the same directory as the script):
6. economic_data_analysis.xlsx: An Excel file containing the summary table and both charts embedded as images.
6. gdp_growth_chart.png: An image file of the GDP growth line chart.
7. inflation_2024_chart.png: An image file of the 2024 inflation bar chart.
These outputs will provide you a quick overview of economic performance and trends.
