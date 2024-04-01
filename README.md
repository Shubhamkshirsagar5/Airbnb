# Navigating and Data Collection of Airbnb
#Listings: A Selenium WebDriver Approach

This Python script employs the Selenium package to navigate and scrape data from Airbnb's
website. The process is automated through a web driver that simulates a user browsing through
property listings on Airbnb. Specifically, the script is designed to:
Construct the URL for the Airbnb search page based on a specified location and date range.
Open the URL in a browser window controlled by Selenium.
Sequentially navigate through the first three pages of the search results.
For each listing found, extract the URL, nightly price, number of beds, and user rating, handling
instances where information may be missing.
Store the gathered information in a Pandas DataFrame and Export the DataFrame to a CSV file
for subsequent use or analysis.
