# html_challenge
For this challenge there are two deliverables: part_1_mars_news.ipynb and part_2_mars_weather.ipynb 
The first deliverable part_1_mars_news.ipynb visits the Mars News Website and scrapes the title and preview texts of the articles, and stores in a Python list of dictionaries. 
Using beautiful soup, the script finds all the 'div' elements with the class 'list_text' which contains the titles and preview text of the articles. The script iterates over each 'div' element to extract the data using their classes ('content_title' and 'article_teaser_body') Each dictionary in the list represents an article and contains two key-value parts: 'title' and 'preview.' 
After the scraping is complete, the script prints the extracted data of titles and texts. 
Then the Chrome browser is closed after the scraping is complete. 

The second deliverable part_2_mars_weather, visits the Mars temperature and atmospheric pressure dataset and scrapes the data to perform analysis. 
Using Beautiful Soup, the script finds the table containing the dataset, then extracts the rows of data from the table and  stores it in a list named data, which is organized as a list of lists. 
Using Pandas, the script creates a data frame extracted from the table.
The script prints the answers to the questions about the dataset, such as the number of months, number of Martian days, temperature, atmospheric pressure by month, etc. 
The script, using Matplotlib then generates two bar plots to which measure the average minimum daily temperature and the average daily atmospheric pressure by month. 
The analyzed data will be saved to a CSV named mars_data.csv in the same directory as the script. 
The Chrome browser is closed after scraping, and the analysis is complete. 
