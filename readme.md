# Patten Recommender 

Recommendation system powered by recommendation models.
## Implemented by Team #7

# Dependencies
* Python 3.7
* flask
* sqlite
* pandas


Install packages by

`pip install -r requirements.txt`

Download the common stopwords by
`python recommender/download.py`
then select to download the `popular` section.

Set the env variable
`sudo ./setenv.sh`

Initialize the sqlite db by
`python manage.py initdb`

Start the app by
`python manage.py runserver`


