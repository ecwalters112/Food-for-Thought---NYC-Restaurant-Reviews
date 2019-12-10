# Group C Yelp Data

## Title: New York City Restaurant Comparison
by Chana Messinger, Elizabeth Walters-Parish, and Michael Weisner

### Project Link: http://www.columbia.edu/~mw2931/food_for_thought.html

### To Run Project Code:

+ Download raw data from https://www.dropbox.com/s/eui1updjryfuqxz/group_c_data.zip?dl=0
+ Unzip contents of data zip file to the project directory
+ Open the "food_for_thought" RMD file and run all / knit

### Process Book: 
http://www.columbia.edu/~mw2931/food_for_thought_process.pdf (also in github as food_for_thought_process.pdf)

### Project Description:

Explore trends in Yelp review scores, written Yelp reviews, and DOHMH health inspection scores to explore the landscape of New York City restaurants.

### Original Project Goals Writeup:

+ Compare distribution of restaurants of various reviews and relation to distribution of health violations
+ Look at most frequent cuisine by neighborhood
+ Perform network analysis of reviewers' restaurants? Or restaurants who share reviewers?
Do linked restaurants share cuisine, neighborhood or price?
+ Sentiment Analysis of Scores? Or of reviewers? We could give reviewers mean positive/negative scores and compare them to star scores.
+ Look at restaurant ratings by neighborhood economics, trees, and community health (e.g. obesity).
Filtered maps
Frequency of health code inspections
Filter maps by health violations or star ratings or price
Potentially hard code neighborhoods


We will use leaflet, tmap, ggplot2, and text mining (tm and sentiment packages) and potentially network analysis for this project. 

### Data:

Yelp Data via Yelp API - https://www.yelp.com/fusion
Stonybrook NYC Restaurant Review Dataset - http://odds.cs.stonybrook.edu/yelpnyc-dataset/
DOHMH Health Code Data - https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j
NYC Zip files: https://data.cityofnewyork.us/widgets/i8iw-xf4u

### Citations:

#### Yelp Data
NYC Yelp Price and Score data was collected via calls to the [Yelp API](https://www.yelp.com/developers/documentation/v3) in March 2019. The academic dataset is national, and does not include a great number of New York City restaurants.

#### Health Violation Data
Health code Violation data was retrieved from the [New York City Department of Health and Mental Hygiene (DOHMH) via the NYC OpenData website](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j) in March 2019.


#### Yelp Review Data
NYC Yelp Restaurant Reviews were provided by [Stonybrook University's Outlier Detection Datasets (ODDS)](http://odds.cs.stonybrook.edu/yelpnyc-dataset/) and can be found in the following papers:

Collective Opinion Spam Detection: Bridging Review Networks and Metadata. Shebuti Rayana, Leman Akoglu, ACM SIGKDD, Sydney, Australia, August 10-13, 2015

Collective Opinion Spam Detection using Active Inference. Shebuti Rayana, Leman Akoglu, SIAM SDM, Miami, Florida, USA, May 5-7, 2016

To get the datasets with ground truth please email: srayana@cs.stonybrook.edu

#### New York City Census Data
The data, curated by www.kaggle.com users muonneutrino here:
https://www.kaggle.com/muonneutrino/new-york-city-census-data#nyc_census_tracts.csv

The data was taken from the American Community Survey 2015 5-year estimates (https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml).

The census block coordinate data was taken from the FCC Census Block Conversions API (https://www.fcc.gov/general/census-block-conversions-api)

As public data from the US government, this is not subject to copyright within the US and should be considered public domain.
