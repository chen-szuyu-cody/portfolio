<h2 id="wids_datathon_2020">Wids Datathon 2020 | Predict ICU death probability</h2>

<h3>Notebook:</h3>

- [Predicting Encounter Death Probability by Using Machine Learning - XGBoost](https://nbviewer.jupyter.org/github/chen-szuyu-cody/portfolio/blob/master/Project/wids_datathon_2020/Predicting%20Patients%20Mortality%20Rate%20by%20Using%20Machine%20Learning%20-%20XGBoost.ipynb)

<h3>Blog:</h3> 

- [Machine Learning in Healthcare — WidsDatathon2020](https://medium.com/@chen.szuyu.cody/using-ensemble-learning-in-health-care-data-widsdatathon2020-318cb35edd96)

<h3>Overview</h3>
The challenge is to create a model that uses data from the first 24 hours of intensive care to predict patient survival. MIT's GOSSIS community initiative, with privacy certification from the Harvard Privacy Lab, has provided a dataset of more than 130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year timeframe. This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States.

Labeled training data are provided for model development; you will then upload your predictions for unlabeled data to Kaggle and these predictions will be used to determine the public leaderboard rankings, as well as the final winners of the competition.

<h3>Data Description</h3>

- training_v2.csv - the training data. You should see 91,713 encounters represented here. Please view the WiDS Datathon 2020 Dictionary file for more information about the columns.
- unlabeled.csv - the data without hospital_death provided. You are being asked to predict the hospital_death variable for these encounters.
- samplesubmission.csv - a sample submission file in the correct format
- solution_template.csv - a list of all the rows (and encounters) that should be in your submissions
- WiDS Datathon 2020 Dictionary.csv - supplemental information about the data
