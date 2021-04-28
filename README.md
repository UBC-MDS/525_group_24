Machine Learning Models in the Cloud to Predict Daily Rainfall in
Australia
================
DSCI 525 - Group 24 @ University of British Columbia
March 30, 2021

# About

In this project, we will build and deploy ensemble machine learning
models in the cloud to predict daily rainfall in Australia on a large
dataset (\~6 GB) (data source is
[here](https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681)),
where features are outputs of different climate models and the target is
the actual rainfall observation. The purpose of this project is to get
exposure to working with larger dataset and achieve various learning
objectives in each of the following four milestones:

Milestone 1: Get the data from web using API, process it, and convert it
to an efficient file format.  
Milestone 2: Move the data to cloud, setup the infrastructure in the
cloud and build a Machine Learning model.  
Milestone 3: Setup distributed infrastructure using Spark and run the
Machine Learning model on Spark.  
Milestone 4: Deploy Machine Learning model in cloud so that other
consumers can use it.

# Report

Milestone 1: A summary of observations and discussion on challenges
encountered, is documented in this
[notebook_1](notebooks/rainfall_eda.ipynb).

Milestone 2: A summary of moving data to cloud and wrangling for 
machine learning, is documented in this
[notebook_2](notebooks/milestone_2.ipynb).

Milestone 3: A summary of Machine Learning model building results 
is documented [here](notebooks/milestone3/).

Milestone 4: A summary of API deployment results 
is documented [here](notebooks/milestone4/).

# License

The material on analysis about “Machine Learning Models in the Cloud to
Predict Daily Rainfall in Australia” are licensed under the [MIT
License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)
(Copyright (c) 2020 Master of Data Science at the University of British
Columbia). If you want to re-use/re-mix the analysis and the materials
used in this project, please provide attribution and link to this
repository.

The data used to create the “Daily Rainfall over NSW, Australia” data
set are freely available under a [Creative Commons Attribution 4.0
International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
licence.

# Contributors

| Contributor Name | GitHub Username                         |
|------------------|-----------------------------------------|
| Huanhuan Li      | [huan-ds](https://github.com/huan-ds)   |
| Nash Makhija     | [nashmakh](https://github.com/nashmakh) |
| Nicholas Wu      | [nichowu](https://github.com/nichowu)   |
