<img src="dog-rates-social.png" style="width:1000px; height:500px"/>

# Twitter's WeRateDogs Analysis
## Overview
Real-world data rarely comes clean. Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assesssed its quality and tidiness, then cleaned it: the data wrangling process. I documented my wrangling efforts in a Jupyter Notebook, plus showcased them through analyses and visualizations using Python (and its libraries).

The dataset that I was wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

## Installation
This project requires Python 3.xx and the following Python libraries:
* Numpy
* pandas
* matplotlib
* seaborn
* json
* datetime
* Tweepy
* Requests
* io
* os

## Table of Contents
1. Data Gathering
2. Data Assessing
3. Data Cleaning - Tidiness
4. Data Cleaning - Quality
5. Data Storing
6. Analyze
7. References

## Files
* `wrangle_act.ipynb`: code for gathering, assessing, cleaning, analyzing, and visualizing data
* `wrangle_report.pdf` or `wrangle_report.html`: documentation for data wrangling steps: gather, assess, and clean
* `act_report.pdf` or `act_report.html`: documentation of analysis and insights into final data
* `twitter_archive_enhanced.csv`: file as given
* `image_predictions.tsv`: file downloaded programmatically
* `tweet_json.txt`: file constructed via API
* `twitter_archive_master.csv`: combined and cleaned data
* any additional files (e.g. files for additional pieces of gathered data or a database file for your stored clean data)

## Resources

* Twitter API - [Tweepy](https://tweepy.readthedocs.io/en/latest/)
