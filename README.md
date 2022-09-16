# web-scraping-challenge
Module 12 Challenge

## Mars Data Challenge Pt 1
* I scraped the Mars News (https://redplanetscience.com/) website by using Splinter and Beautiful Soup. Specifically, I scraped the title and preview text, or summary text, of each article on the landing page.
* I stored the scraping results in Python data structures as follows:
* Stored each title-and-preview pair in a Python dictionary. And, gave each dictionary two keys: title and preview.
Summary:
* Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)
* The titles and preview text of the news articles were scraped and extracted. (20 points)
* The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)

## DMars Data Challenge Pt 2
* Scraped the data in the HTML tableusing the Pandas's read_html method
* Assemble the scraped data into a Pandas DataFrame. 
* Converted the data to the appropriate datetime, int, or float data type

Then I answered the following questions:
* How many months exist on Mars?
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
* What are the coldest and the warmest months on Mars ?
* Which months have the lowest and the highest atmospheric pressure on Mars?
* About how many terrestrial (Earth) days exist in a Martian year? 

Then I exported the DataFrame to a CSV file.






