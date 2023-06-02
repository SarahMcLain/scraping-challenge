# scraping-challenge

This code is designed to scrape data on mars.
Part 1:

Visit this website: url = 'https://static.bc-edx.com/data/web/mars_news/index.html' 
   
Set up BeautifulSoup to scape the designated url then:
    - extract all text elements snf ssave as variable

Store the results:
    - extract the headline and text preview from your text elements with for loop
    - save as dictionary 
    -print list in notebook

Part 2:

Scrape & analyze data from this website: "https://static.bc-edx.com/data/web/mars_facts/temperature.html"
    -Extract all rows of data

Store the data:
    - Using a for loop to loop through the scraped data and append to a list
    - Create a pandas dataframe 

Analyze the created dataframe:
    -Check dataframe column types
    -Update coumn types to match the following: 
        
            terrestrial_date    datetime64[ns]
            sol                          int32
            ls                           int32
            month                        int32
            min_temp                   float64
            pressure                   float64
    - Determine how many months exist on mars.
    - Determine how many Martian days worth of data exists in the data set.
    - Determine the average min_temp for each month & plot usng a bar chart
    - Sort the average min_temp for each month from coldest to hottest & plot
    - Determine the average pressure for each month & plot
    - Determine approx how many Earth days exist in a Martian year by plotting min_temp data. 

Save the dataframe as a csv file

