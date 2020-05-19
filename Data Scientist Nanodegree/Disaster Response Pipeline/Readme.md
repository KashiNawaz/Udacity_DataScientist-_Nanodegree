# Disaster Response Pipeline Project

### Project Motivation
This project is designed to apply data engineering skills in building an end to end machine learning pipeline to classify disaster messages into 36 categories. A machine learning model is built based on real messages by preproceesing them using NLTK library and improved its performance by doing grid search to find the optimal parameters. The prediction results can help connect the affected individual to the right department.
### Table of Contents
    File Descriptions
    Instructions
    Screenshots

### File/Folder  Descriptions
    app: This folder contains all the files related to the web API development.
    data: This folder contains the raw data, data processing script and its corresponding jupyter notebook.
    models: This folder contains the model training and saving script along with its jupyter notebook.
    imgs: This folder contains screenshots of tha app.
    ETL Pipeline Preparation.ipynb: It contains all the necessay pre processing steps.
    ML Pipeline Preparation.ipynb: It coontains the ML Pipeline i.e training, validation and testing etc steps
 ### Instructions
1. Go to the projects root directory and run the following command to run the ETL pipeline that does the preproceesing and stores in database : python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
2. To run the ML pipeline that trains our pipeline and saves the model, run the following command : python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
3. Run the following command to start running our web app to get predictions and see visualizations : python run.py
4. Visit (http://0.0.0.0:3001/) to see the web app
### Screenshots
