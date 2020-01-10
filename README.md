Auto Tweet

     A python script to automate the process of posting tweets
   

Libraries and Requirements

     Tweepy - library for twitter API
     Pysocks - send traffic throughs  and HTTP proxy servers
     Certifi -verification of trustworthyness in secure shell 
     idna- internaltionalized domain name application
     Six -is a Python 2 and 3 compatibility library

How to Run the Script

  install dependencies
  
                  py -m venv env
                  env\Scripts\activate
                  pip install -r requirements.txt

Add a credentials.py in the follwing format 
      Link to creating tweepy [credentials](https://developer.twitter.com)

                      ACCESS_TOKEN = "####"
                      ACCESS_TOKEN_SECRET = "####"
                      CONSUMER_KEY = "####"
                      CONSUMER_SECRET = "####"

 Adjust the NUM_OF_TWEETS and WAIT_TIME parameter in  script.py. Make sure to not have a very small WAIT_TIME.

Run the script
                          
                          python script.py

