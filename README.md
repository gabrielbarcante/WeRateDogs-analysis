# WeRateDogs Analysis
## Description
This is the fourth project of the Data Analyst Nanodegree Program from Udacity. I will be working to gather, assess, and clean data from the Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as WeRateDogs.

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "[they're good dogs Brent](https://knowyourmeme.com/memes/theyre-good-dogs-brent)". WeRateDogs has over 9 million followers and has received international media coverage.

The goal will be to wrangle the datasets described in the `Files used` section to store a clean DataFrame in a CSV file called [twitter_archive_master](twitter_archive_master.csv). Then, I will act on it to create interesting and trustworthy analyses and visualizations.
<br><br>

## Files used
I will gather the following files:
* [The WeRateDogs twitter archive](twitter-archive-enhanced.csv)
* [The tweet image predictions](image_predictions.tsv)
* Using the tweet IDs in [the WeRateDogs twitter archive](twitter-archive-enhanced.csv), I will query the Twitter API for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in a file called [tweet_json.txt](tweet_json.txt), with one tweet's JSON data per line.
<br><br>

## Softwares
* Python 3.8 or above
* Packages: 
  * matplotlib, 
  * seaborn, 
  * pandas, 
  * numpy, 
  * requests, 
  * tweepy, 
  * json, 
  * time
<br><br>

## License
The contents of this repository are covered under the [MIT License](LICENSE).
