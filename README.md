# Data Science in 30 Minutes
A quick demo illustrating a few data science techniques, and all in 30 minutes!

## Requirements:
You'll need to install the requirements
```
pip install -r requirements.txt
```

## Add Twitter credentials:
Next, you will also need to sign up for Twitter, obtain API credentials, and add those credentials to `twitter_secrets.json.nogit` (this file is intentionally ignored by git).  You can obtain your API credentials on the [Twitter API page](http://apps.twitter.com/). This file must be in JSON format so that the SimpleJSON package can read it, which will look something like: 
```
{
"api_key": "XXXX",
"api_secret": "XXXX",
"access_token": "XXXX",
"access_token_secret": "XXXX"
}
```
where the XXXX values are yours.

## Run:
To run this demo, you will need to startup an ipython notebook instance:
```
ipython notebook
```

Then go to `localhost:8888` and click on `DS30.ipynb` to view the example.
