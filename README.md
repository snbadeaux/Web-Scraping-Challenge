# Web-Scraping-Challenge<br>


Background<br>
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.<br>
As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.<br>
What You're Creating<br>
This new assignment consists of two technical products. You will submit the following deliverables:<br>
•	Deliverable 1: Scrape titles and preview text from Mars news articles.<br>
•	Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.<br>


Instructions<br>

Part 1: Scrape Titles and Preview Text from Mars News<br>

Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.<br>
1.	Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.<br>
2.	Create a Beautiful Soup object and use it to extract text elements from the website.<br>
3.	Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:<br>
o	Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.<br>
o	Store all the dictionaries in a Python list.<br>
o	Print the list in your notebook.<br>
4.	Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)<br>


Part 2: Scrape and Analyze Mars Weather Data<br>

Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.<br>
1.	Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.<br>
2.	Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.<br>
3.	Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:<br>
o	id: the identification number of a single transmission from the Curiosity rover<br>
o	terrestrial_date: the date on Earth<br>
o	sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars<br>
o	ls: the solar longitude<br>
o	month: the Martian month<br>
o	min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)<br>
o	pressure: The atmospheric pressure at Curiosity's location<br>
4.	Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.<br>
5.	Analyze your dataset by using Pandas functions to answer the following questions:<br>
o	How many months exist on Mars?<br>
o	How many Martian (and not Earth) days worth of data exist in the scraped dataset?<br>
o	What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:<br>
	Find the average minimum daily temperature for all of the months.<br>
	Plot the results as a bar chart.<br>
o	Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:<br>
	Find the average daily atmospheric pressure of all the months.<br>
	Plot the results as a bar chart.<br>
o	About how many terrestrial (Earth) days exist in a Martian year? To answer this question:<br>
	Consider how many days elapse on Earth in the time that Mars circles the Sun once.<br>
	Visually estimate the result by plotting the daily minimum temperature.<br>
6.	Export the DataFrame to a CSV file.<br>


Sources:<br>

Python Tutorial. (n.d.). https://www.w3schools.com/python/<br>

Stack Overflow - Where Developers Learn, Share, & Build Careers. (n.d.). Stack Overflow. https://stackoverflow.com/<br>

https://chat.openai.com/: used to help debug problematic for loop.<br>

Starter code given from boot camp class and instructions<br>
