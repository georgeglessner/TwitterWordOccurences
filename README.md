# Word Occurrence Analyzer for Twitter
### Analyze a user's Twitter feed to find the words tweeted the most

# Setup
1. Create a new [Twitter application](https://apps.twitter.com/) to obtain the needed keys in credentials.py 
2. Add your keys to credentials.py
3. Run `pip3 install -r requirements.txt`

# Usage

	Usage: 
    	tweet_analyzer [-u USER] [-n NUMBER OF OCCURRENCES] [-f OUTPUTFILE]

	Options:
	    -h --help       show this  
	    -u --user       username of account to analyze  
	    -n --num        minimum number of occurrences the word appears [default: 20]  
	    -f --file	    name of output file (.csv) [default: results.csv]  

The results will be stored in a .csv file in the working directory with the filename you specified or "results.csv" if you did not specify a filename. 
