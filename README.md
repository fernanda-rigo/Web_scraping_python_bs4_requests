## Web scraping with python, using beautiful soup and request
Following the tutorial:
https://www.dataquest.io/blog/web-scraping-python-using-beautiful-soup/

### scraping data from https://forecast.weather.gov/MapClick.php?lat=37.7772&lon=-122.4168
What I did:
- Downloaded the web page containing the forecast.
- Created a BeautifulSoup class to parse the page.
- Located the div with id seven-day-forecast, and assign to seven_day
- Inside seven_day, located individual forecast item.
- Extracted and printed the first forecast item.
- Extracted all information from the page.
- Constructed a dataframe with the data.
- Isolated the numeric values using Series.str.extract and regular expression 
- Conducted a briefly exploratory data analysis, including:
  - calculating the mean temperature (including high and low)
  - Selecting by lower temperatures at night 

 # next step: apply this concept for other pages, focusing on business intelligence.
