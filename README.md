# Web-Scraping-Using-
Using the Google Custom Search API to perform web scraping and extract information about the fastest cars in the world.
The goal is to retrieve relevant data from search results, including titles, links, and snippets, and then proceed to scrape data from specific websites containing information about the top fastest cars.

Libraries Used:

Beautiful Soup 4 (bs4) for HTML parsing
pandas for data manipulation
Steps in the Project:

Import necessary libraries, including BeautifulSoup, pandas, and requests.
Define the Google Custom Search API key and engine ID.
Set up the parameters for the search query.
Send a GET request to the Google API and check the response status.
Parse the response content using BeautifulSoup to extract information about search results.
Iterate through the search results and extract titles, links, and snippets.
Select a specific website (Wikipedia in this case) from the search results.
Send a GET request to the selected website and parse the content using BeautifulSoup.
Locate and extract tables containing data about the fastest cars.
Clean and organize the data extracted from the tables.
Create a pandas DataFrame to store the extracted data, including attributes like top speed, engine type, etc.
