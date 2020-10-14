# IPL web scraping and EDA

The Indian Premier League (IPL) is a professional Twenty20 cricket league in India contested during March or April and May of every year by eight teams representing eight (previously upto 10) different cities or states in India. The league was founded by the Board of Control for Cricket in India (BCCI) in 2008.

The IPL is the most-attended cricket league in the world and in 2014 ranked sixth by average attendance among all sports leagues.

## Data scraping

I used scrapy framework for creating a web spider for extracting IPL statistics from espncricinfo.com
This website allows web scraping with delay of 15 seconds between requests.

I have made 2 scripts for extracting IPL data.\n
1st script (scrape_match_detail.py) retrieves match results and season summary.\n
2nd script (scrape_each_match.py) can be used for retrieving in-depth details of each match. \n\n

For running use below command
scrapy runspider -o output_file.csv scrape_match_details.py
scrape_each_match.py can be executed like any other pytho script using IDE.


## EDA
