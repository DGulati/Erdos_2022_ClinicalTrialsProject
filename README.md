# Erdos_2022_ClinicalTrialsProject
Members: 

  - Adriana Morales Miranda 
  - Meghan Peltier
  - Devashi Gulati 

# Project Summary 

# Notebook Descriptions

## ExtractingFromWebpage.ipynb

In this notebook we use web extrating techniques to ge information from the ClinicalTrials.gov website. The website itself allows us to download .csv files which contain most of the information we require for our analysis. Nevertheless, there are some columns we want to have that are not as easily available.

There are 30,000 webpages that we want to web scrape, below is a code for automated web scraping that speeds up our data collection process. We use this code to scrape :

  - NCT Number (so that we can match it to the .csv files
  - Desired enrollment
  - Countires were the trial was conducted

**Note:** If you have the NCT Number for a clinical trial you want to extract information from, you can use this code to do so.

## Data_Preparation.ipynb

In this notebook we clean and pre-proccess our data for analysis. 

## Exploratory_Data_Analysis.ipynb

In this notebook we use descriptive statistical techniques to analyze the correlation between data features and the status of a trial as completed or terminated.

## Model_All_Data.ipynb 

In this notebook we implement three differents modeling tools for classification problems:

  - Logistic Regression
  - Random Forests
  - Artifical Neural Networks (ANN)

**Goal:** We want to identify if the phase of a clinial trial will be completed or terminated based on different factors like:

  - Enrollment fraction: (actual number of people enrolled)/(desired number of people)
  - Phase of the trial
  - Age type of people enrolled in trial phase
  - Genders allowed in trial phase
  - Intervention method of the trial phase
  - Number of months between start and end of phase
  - Actual number of people enrolled
  - Estimated or desired number of people per trial

The goal is to see how well these three different models perform on our data and extract important information.


# Results 
