# Disaster Response Pipeline Project 2

### Work Steps:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/ETL_pipeline.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/MLP_pipeline.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

### Zip folder Files:
```
- app folder
| - template
| |- master.html  # main page of web app
| |- go.html  # classification result page of web app
|- run.py  # Flask file that runs app

- data folder
|- disaster_categories.csv  # data file
|- disaster_messages.csv  # data file
|- ETL_pipeline.py 
|- DisasterResponse.db   # database to save clean data to

- models
|- MLP_pipeline.py
|- classifier.pkl  # saved model

- notebooks
|- ETL Pipeline Preparation.ipynb # etl exploration
|- ML Pipeline Preparation.ipynb # ML exploration
|- disaster_categories.csv  # data file
|- disaster_messages.csv  # data file



### Required packages:

- flask
- joblib
- jupyter # If you want to view the notebooks
- pandas
- plot.ly
- numpy
- scikit-learn
- sqlalchemy


### Data and cleaning details:

Data cleaning porcess has been applied to create cleaned dataframe for ML model.


### My learning:

It is good learning excerise to test ML classifers and get the optimized classifer.
