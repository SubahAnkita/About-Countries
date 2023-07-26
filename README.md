# About-Countries

# Rest Countries API Table

This web page utilizes the Rest Countries API to display a table of countries along with their population and capital. Users can search for specific countries, apply population filters, and sort the table based on different columns.

## Features

1. **Table Display**: The page displays a table with columns for country name, population, and capital. Initially, the table is empty.

2. **Search Functionality**: Users can enter a search term in the provided search input field to filter the table and display only the countries whose names start with the entered term. The search is case-insensitive.

3. **Population Filters**: The page provides two input fields for minimum and maximum population filters. Users can enter a value in either or both fields to filter the table and display countries with populations within the specified range.

4. **Apply Filters Button**: Clicking the "Apply Filters" button triggers the filtering process based on the entered population filters. The table is updated accordingly with the filtered results.

5. **Sorting Functionality**: The sorting functionality is currently commented out in the code (lines 36-45). If you uncomment the table header row in the code, the table headers become clickable. Clicking on a header sorts the table based on that column in ascending order. Clicking the same header again reverses the sorting order.

## How to Use

1. Open the HTML file (index.html) in a web browser.

2. The table is initially empty, waiting for data to be fetched from the Rest Countries API.

3. Once the API data is fetched, the table will be populated with country data, including columns for country name, population, and capital.

4. Enter a search term in the search input field to filter the table based on country names.

5. Optionally, enter minimum and/or maximum population values in the respective filter input fields.

6. Click the "Apply Filters" button to apply the population filters and update the table.

7. Optionally, uncomment the table header row in the code (lines 36-45) to enable sorting functionality based on column headers. This allows you to click on a header to sort the table in ascending order based on that column.

8. Experiment with different search terms, population filters, and sorting options to explore the functionality of the page.
