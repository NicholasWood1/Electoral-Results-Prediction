# Predicting voting decisions based on demographics
## COMP2200 Group Project - Group 42
 - Michael Yee (46430261)
 - Nicholas Wood (46042210)

## Overview
This repository contains the notebooks and source data for an analysis of electorate demographics and voting choices. This analysis aimed to build a predictive model for electoral results in the 2019 Australian Federal Election based on demographic characteristics of different electorates measured in the 2016 Australian Nation Census. Several different types of models were tested, including logistic regression, K-nearest neighbours, decision tree, and multi-layer perceptron models.

Please note that this analysis makes use of the eli5 Python library which will need to be installed from pip or conda to execute the notebooks in full.

## Notebooks

The 'notebooks' folder contains the Jupyter notebooks that were used during the development of the final analysis. The final report notebook can be found in the root directory under the name 'Group 42 - Voting Prediction Final Report'.

## Source Data

The 'datasets' folder contains the raw and cleaned census and electoral data that was used throughout the analysis. Datasets have been categorised as raw or clean and are located in the 'Raw Datasets' and 'Clean Datasets' sub-folders accordingly. The census data and electoral data can be found in these folders as well as other data, which contains the CED to SA1 mapping for 2016 and 2018 which was used for cleaning the census data.
