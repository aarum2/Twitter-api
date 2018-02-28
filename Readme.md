In order to use the twitter API, we have to authorize ourselves. In order to do that, we should be having a twitter account.
To get authorized for using the twitter api, go to https://apps.twitter.com/ and sign into your existing twitter account or create a new account.
Press the create new application button on the screen.
We need the following four keys to authorize:
consumer_key
consumer_secret
token_key
Token_secret

For augmenting the URL with the keys, we use oauth which is also built in python. This process is clearly shown in the twurl.py file.
Replace the authorization keys with yours in the hidden.py file and run the the twitter.py. you will be able to see the status of your friends printed.
