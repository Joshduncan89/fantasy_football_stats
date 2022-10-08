## Fantasy Predictor: Project Overview
Created a tool that collects NFL Player stats
- Web scraping using Pandas
- ETL process using Pandas, Numpy
- Data Visualization using Searborn, Matplotlib
- Web Scraping
Data scraped from profootballreference of players stats from 2017-2021.

### Data Cleaning
After scraping the data, I needed to clean it up so that it was usable for the model. It also felt redundant to keep players in the data that had minimal fantasy impact. I transformed the data and added measures i might want to investigate further.

- Removed Junk Data
- Parse numeric data types
- Extract data to CSV based on year
- Add rank columns for Top N by position
### EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables.
## Screenshots

![Login](https://github.com/Joshduncan89/fantasy_football_stats/blob/master/screenshots/Screenshot6.png?raw=true)
![Login](https://github.com/Joshduncan89/fantasy_football_stats/blob/master/screenshots/Screenshot7.png?raw=true)
![Login](https://github.com/Joshduncan89/fantasy_football_stats/blob/master/screenshots/Screenshot8.png?raw=true)
![Login](https://github.com/Joshduncan89/fantasy_football_stats/blob/master/screenshots/Screenshot9.png?raw=true)

