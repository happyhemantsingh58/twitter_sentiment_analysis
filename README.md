# twitter_sentiment_analysis
First of all login from your Twitter account and goto Twitter Apps. Create a new app (How to create twitter app) and goto Keys and access tokens and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later.

Installation
Download or Clone the repo, Navigate to the directory containing the files and run

python setup.py install
or if you have different versions of python installed then

python3 setup.py install 
to install the dependencies.

Usage
Once you have created an app on twitter and installed all the dependencies by running setup.py, open main.py and paste your Consumer Key, Consumer Secret, Access Token and Access Token Secret. After that save and run the script. You will be prompted to enter the keyword/hashtag you want to analyze and the number of tweets you want to analyze. Once the analysis is completed, a pie chart will be generated disclosing the results of analysis.

