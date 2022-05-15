# Spotify-ETL

In this project, I built an ETL pipeline that ingests data from Spotify's API transforms them and loads them into MySQL database.

## Steps
* Creating connection to the spotify's API. 
* You will need a spotify token generated from a developer account to access their API, you can login with you spotify account
* Get the 50 most recently played tracks and store them in a pandas dataframe
* Load the result to MySQL or any other database using SQLalhemy

As the first 50 songs doesn't really give aby interesting information, we want to see our music taste in over 30 days so I will use Airflow to automate the process

Check the Dag folder for the airflow code
