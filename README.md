# Module-11-Challenge
# Mars Weather Data Analysis

## Overview

This repository contains Jupyter Notebook code for scraping and analyzing Mars weather data. The code utilizes automated browsing to visit the Mars Temperature Data Site and extracts relevant information using Beautiful Soup. The scraped data is then organized into a Pandas DataFrame for further analysis.

## Part 2: Scrape and Analyze Mars Weather Data

### Steps:

1. Open the Jupyter Notebook: `part_2_mars_weather.ipynb` located in the `starter code` folder.

2. Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and inspect the page to identify elements to scrape.

3. Create a Beautiful Soup object to scrape data from the HTML table. Assemble the data into a Pandas DataFrame with columns matching the table on the website.

4. Examine the data types associated with each column and convert them to the appropriate types (datetime, int, or float) if necessary.

### Analysis Questions:

1. **How many months exist on Mars?**
   - Utilize Pandas functions to determine the number of months present in the dataset.

2. **How many Martian days' worth of data are there?**
   - Calculate the total number of Martian days represented in the scraped dataset.

3. **Temperature Analysis:**
   - Find the average minimum daily temperature for all months.
   - Plot the results as a bar chart to identify the coldest and warmest months on Mars.

4. **Atmospheric Pressure Analysis:**
   - Find the average daily atmospheric pressure for all months.
   - Plot the results as a bar chart to identify the months with the lowest and highest atmospheric pressure on Mars.

5. **Martian Year Duration:**
   - Estimate the number of terrestrial days in a Martian year by plotting the daily minimum temperature.
   - Provide a visual estimate within a 25% margin.

6. **Export Data:**
   - Export the final DataFrame to a CSV file for further use.

## Requirements

### Part 2: Scrape and Analyze Mars Weather Data (60 points)

1. **HTML Table Extraction:**
   - Extract the HTML table into a Pandas DataFrame using either Pandas or Splinter and Beautiful Soup.
   - Ensure the DataFrame columns have correct headings and data types.

2. **Data Analysis:**
   - Answer specified questions using Pandas functions.
   - Create data visualizations (bar charts) to support the answers.

3. **Export to CSV:**
   - Export the final DataFrame to a CSV file.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/mars-weather-analysis.git
   ```

2. Open the Jupyter Notebook and run the code cells in `part_2_mars_weather.ipynb` sequentially.

3. Explore the analysis results and visualizations.

4. Feel free to adapt the code for further analysis or use the exported CSV file as needed.

**Note:** Ensure you have the required dependencies installed, including Jupyter Notebook, Pandas, and Beautiful Soup.

Happy analyzing!
