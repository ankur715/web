<p align="left">
  <img width="900" height="450" src="https://github.com/ankur715/web/blob/master/starbucks/Capture.JPG"> 
</p>


On the location of a New Retail Facility and solving the Retail Location Spatial Problem (RLSP) using Machine Learning in Manhattan, Chicago and Philadelphia

It is very difficult for strategic planners to identify the location of a New Retail Facility as they are faced with a very difficult spatial resource allocation problem. Recently a few studies by conducted by Aboulola(2018), Lee (2018) and Jordan Bean (2019), attempted to solve three different versions of the Retail Location Spatial Problem (RLSP). Aboulola(2018) solves the RLSP by adding social media activity variables (e.g., Twitter, Yelp) and applies it to Starbucks locations in Seattle, Lee (2018) compares the RLSP of a new entrant vs Starbucks in Korea and finally Bean (2019), performs ML (machine learning) on RLSP to determine the location of a Starbucks within a zipcode with the highest probability of success. We conducted a ML strategy (logistic regression) on the RLSP for Census Tracks from the 2010 census (many census tracks are constituted to create one zipcode) but demographic data from the American Community Survey(ACS) , transit data (subway stops and total ridership for each stop) for Philadelphia, Chicago and Manhattan and the Existing Locations of Starbucks in each city from Kaggle(2017). The training set for Manhattan was transit data, census track data and starbucks locations data for Philadelphia and Chicago. We created three distinct training sets and tested it on the three cities. We obtained the top 5 highest probability census tracks. The next Starbuck census track for each city was computed for an average distance from each track to the nearest Starbucks (194 feet for Manhattan, 276 feet for Chicago and 303 feet for Philadelphia). The Census Tracts with the highest probabilities are Census Track (36061007800) in Manhattan, Census Track (17031080202) in Chicago and Census Track (42101000801) in Philadelphia respectively.



