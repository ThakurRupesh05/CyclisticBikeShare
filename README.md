# Cyclistic Bike Share

My business task was to figure out “How do annual members and casual riders use Cyclistic bikes differently?” 

## Tools Used

- Python
    - numpy
    - pandas
    - matplotlib

## Data Source

- The data has been made available by Motivate International Inc. under Data Licence Agreement. Data License Agreement | Divvy Bikes
- All data is in the .csv file format. I have collected data from January 2020 to December 2020.
- This data is publicly available for us to use and analyze.
- There are some rules that we need to follow while using data. We can not use data to identify personal information.
- The bikeshare company provides data that shows its credibility.
- There are started and ended date columns which we will use to find the answers.

## Data manipulation

- I have sorted the data by start date. 
- I have created two new columns for the ride time of the rider and the weekday when the ride starts.
- Some rows in the ride length are less than 1 min. There is no sense in riding a bike for a second. That is why I have filtered out the data.
- Some data are missing that we will not need for our analysis. 
- We can not drop those rows because it can affect our research.

## Analysis

I have performed descriptive analysis on every aspect of the data. I have found that Cyclistic customers distribution is 59% annual members and 41% casual members. Annual members use the Cyclistic services only for a commute. There number of rides is consistent throughout the weeks. Casual members use Cyclistic service for pleasure. There number of rides increase on week ends.

The average ride times of both types of customers are very distinct. Casual members' ride times increase on weekends, while annual members' ride times are consistent throughout the weeks.

The Cyclistic Bike share company sees an increase in customer numbers from April 2020 to July 2020. At the end of the year, their customers have decreased in numbers may be because of the winter.

June, July, and August have seen the most rides in the year. At the end of the year, this number has decreased for casual and annual members.

The average ride time of casual riders is higher than the annual riders members throughout the year.

The Cyclistic Bike Share uses three different kinds of bikes, which are classic, docked bikes, and electric bikes. The most used bikes are electric bikes, then the classic bikes, a small margin of members also use docked bikes.
