# SpaceXLandingProject
Capstone Project for IBM Data Science Professional Certificate
## Data Collection API
* First step is to request data, put it in a data frame launch_data
* then filter data with respect to BoosterVersion column to keep only Falcon 9 data.
* Put that in a data frame data_falcon9 and remove the null values.
## Web scrap Falcon 9 launch records with `BeautifulSoup`: 
- Extract a Falcon 9 launch records HTML table from Wikipedia
- Parse the table and convert it into a Pandas data frame
