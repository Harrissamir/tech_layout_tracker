# Tech Layoff Tracker

Problem Statement-

The tech industry has experienced significant layoffs in recent times, and tracking these layoffs helps in understanding industry trends, company stability, and market conditions. However, manually monitoring layoffs from different sources is tedious and inefficient.

Solution-

This Python-based Tech Layoff Tracker provides a simple and automated way to analyze layoffs using a CSV file as input. The script processes the layoff data and offers visual insights into:

Total layoffs by company

Layoff trends by industry

Filtering layoffs by date

Using Pandas, Matplotlib, and Seaborn, the tool presents clear data visualizations to help users understand workforce reductions across the tech industry. This helps the HR as to how to track the database of MANG like companies for giving them new oppertunities in their organisation.

Features-

Reads layoff data from a CSV file.

Bar chart displaying the Top 10 companies with most layoffs.

Pie chart showing layoffs by industry.

Date filtering to analyze layoffs within a specified time range.

Handles inconsistencies in column names to ensure smooth data processing.

Prerequisites

Before running the script, ensure you have the following installed:

Python 3.x

Jupyter Notebook (optional but recommended)

Required Python libraries:

pip install pandas matplotlib seaborn

How to Use

Update the CSV file path in the script:

file_path = r"C:\Users\samir\OneDrive\Desktop\github\Layoffs.fyi - Tech Layoffs Tracker.csv"

Run the script in Jupyter Notebook or any Python environment.

Functions Available:-

display_data(): Shows the first few rows of the dataset.

visualize_layoffs(): Generates a bar chart of layoffs by company.

layoffs_by_industry(): Displays layoffs by industry using a pie chart.

filter_by_date(start_date, end_date): Filters layoffs between two dates.

Example Usage

# Display sample data
display_data()

# Visualize layoffsisualize_layoffs()
layoffs_by_industry()

# Filter layoffs from January 2023 to April 2023
filtered_df = filter_by_date('2023-01-01', '2023-04-01')
print(filtered_df)

Expected Output -

A bar chart showing the top 10 companies with the highest layoffs.

A pie chart representing layoffs by industry.

A filtered dataset when using the date filter function.

Conclusion

This Tech Layoff Tracker provides valuable insights into workforce trends, helping professionals, researchers, and analysts make informed decisions based on layoff data. 🚀
