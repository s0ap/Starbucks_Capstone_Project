# Starbucks Capstone Project

This project is a part of the Machine Learning Engineer Nanodegree Program.

## **Table of Contents**

1. [Install Python and the required Python packages](#installation)
2. [Project Motivation](#project-motivation)
3. [File Descriptions](#files)
4. [Results](#results)

## **Install Python and the required Python packages <a name="installation"></a>**

Please download and install Anaconda (https://www.anaconda.com/download/), which provides a Python distribution that includes the scientific libraries for scientific and data analysis. After installation, proceed with the setup.
Also, please ensure you run this command to install additional libraries required to run the project notebook

```
pip install -r requirements.txt
```

## **Project Motivation <a name="project-motivation"></a>**

The project has two main components -

1. Exploratory Analysis - Use the data to identify which groups of people are most responsive to each type of offer and how does it related to their characteristics.
2. Modelling - Build a model that predicts whether a customer will respond to an offer or not (1/0).

Please refer to the proposal write up for more details

## **File Descriptions <a name="files"></a>**

There is a main notebook available in the repository that holds all the work related to the above questions with discussion of results and future improvements. The files included for this project are:

1. data/
   1. Raw data from Udacity/Starbucks
      1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
      2. profile.json - demographic data for each customer
      3. transcript.json - records for transactions, offers received, offers viewed, and offers completed
   2. A pickle object which holds the cleaned, combined dataset with class labels for the effective/ineffective offers.
2. Starbucks_Capstone_notebook.ipynb - Jupyter notebook with the code, analysis and the results.
3. plots/ holds the various charts exported from the notebook
4. models/ holds the saved sklean models which have been explored for this project.

## **Results<a name="results"></a>**

The main observations/analysis/conclusion of the project are published in the report.pdf file.
