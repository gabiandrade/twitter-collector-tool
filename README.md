# tweepy
## Environment:
```
$ pip install tweepy
```
```
$ pip install psycopg2
```
```
$ pip install senticnet
```
## How to use:
Create a file named auth.py with your own twitter api keys and postgresSql data of connection keys by the following script:
### auth.py
```py
# Authentications
consumer_key = 'your consumer key here'
consumer_secret = 'your consumer secret here'
access_token = 'your access token here'
access_token_secret = 'your access token secret here'

# DataBase connection keys
dbname='your database name here'
user='your user here'
host='your host here' #by default postgres uses 'localhost'
password='your password here'
port='your port here' #by default postgres uses '5432'
```
### example.py
```py
from coletor import collect

collect('amor')
```
As paramter for collect function you can put the key word you expect to search.
main.py is a example of script, you can run on your prompt by the following command in the directory of the aplication:
```
python main.py
```
A message as 'collecting tweets with key amor' will confirm the correct run.
