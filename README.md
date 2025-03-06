# Module-11-Challenge
# Mars Web Scraping and Weather Analysis

This project scrapes and analyzes data from Mars websites, focusing on news and weather.

## Part 1: Mars News Scraping

**Objective:** Extract article titles and preview text from a Mars news website.

**Tools:**
- Splinter: Automates browser interactions.
- BeautifulSoup: Parses HTML content.

**Process:**
1. **Visit Target Page:** Use Splinter to navigate to `https://static.bc-edx.com/data/web/mars_news/index.html`.
2. **Extract Data:** Use BeautifulSoup to find and extract the title and preview text elements.
3. **Store Results:** Create a list of dictionaries, where each dictionary contains a title and its corresponding preview.

## Part 2: Mars Weather Analysis

**Objective:** Scrape and analyze Mars weather data from a table.

**Tools:**
- Pandas: For data manipulation and analysis.
- Matplotlib: For data visualization.

**Process:**
1. **Scrape Weather Data:**
   - Locate the weather data table on the website.
   - Extract table rows and cells, cleaning the data.
   - Store the data in a list of lists.
2. **Create DataFrame:**
   - Use Pandas to create a DataFrame from the scraped data.
   - Assign appropriate column names.
3. **Data Preparation:**
   - Examine data types using `dtypes`.
   - Convert columns to the correct data types (e.g., datetime, int, float).
4. **Data Analysis:**
   - **Average Pressure by Month:**
     - Group the DataFrame by 'month' and calculate the mean of 'pressure'.
     - Plot the results as a bar chart.
   - **Lowest/Highest Pressure Months:**
     - Sort the average pressure values.
     - Plot the sorted values as a bar chart.
