# WeRateDogs-Twitter-Archives-Data Wrangling Project

![](https://wallpaperaccess.com/full/266689.jpg)

The wrangling efforts for this project were split into three main phases.

##### The Gathering Phase: 
There were three different datasets for this project all from different sources. The first dataset is a tweet archive of the WeRateDogs twitter account. It is a csv file and I opened it by using pandas library. The second data set is an image prediction tsv file that I programmatically downloaded from udacity's servers using the request library and read it into a dataframe using the pandas library. The last data set I got by querying the Twitter API for each tweet's JSON data using python's tweepy library, then storing each tweet's entire set of JSON data before extracting the retweet count and favorite count for each tweet id and then reading it into a pandas dataframe.

##### The Accessing Phase: 
I went on to the accessing phase. In this phase I visually and programmatically accessed all three datasets to detect quality and tidiness issues. I checked for wrongly imputed data, duplicate records, checked that all variables were in their correct format, checked for issues with the structure of the data, and then I documented all quality and tidiness issues

##### The Cleaning Phase: 
Then I went on to the cleaning phase of the wrangling process were I fixed all of the quality and tidiness issues that I detected in the accessing phase.
