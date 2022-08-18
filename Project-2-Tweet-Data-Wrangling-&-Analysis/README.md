# WeRateDogs Tweet Data Wrangling and Analysis 


## Datasets

### 1. Enhanced Twitter Archive

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which was used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets,  they have filtered for tweets with ratings only (there are 2356). They extracted this data programmatically, but they didn't do a very good job. Provided by Udacity course instructor

### 2. Additional Data via the Twitter API

> Back to the basic of Twitter archives: retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered by anyone from Twitter's API. Well, "anyone" who has access to data for the 3000 most recent tweets, at least. However, we have the WeRateDogs Twitter archive and specifically the tweet IDs within it, can gather this data for all 5000+. I queried **Twitter's API** to gather this valuable data.

> Gathering each tweet's retweet count and favorite ("like") count at the minimum and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file.

> Each tweet's JSON data was written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.

### 3. Image Predictions File

They (Udacity course intructor) ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images). This was assessed and cleaned

## Summary on Findings

Check the wranling analysis report document.......

