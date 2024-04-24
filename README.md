## LAC-ofsted-outcomes-model

# Project Overview
This repository hosts a data-driven analysis and modeling project aimed at understanding the impact of local authority Ofsted grades on the social and educational outcomes of children in care from 2018 to 2022. 

# Repository structure 
**Data**
In the data folder you will find the raw_data subfolder containing the datasets required for the preprocessing script to run as well as the final_data subfolder containing the results of the preprocessing script. 

**EDA** 
The EDA folder contains the script which will produce insights and analysis of the data that was used to inform the modelling approaches. 

**Preprocessing** 
In the preprocessing script you will find the script used to extract variables from the original datasets, merge them together, clean the data and complete the imputation process. 

**Modelling**
We used 4 different models each of which is placed in the modelling folder under the subfolder that matches its name. For the random forest model and the linear regression models two scripts can be found, one which models the data pre imputation and the other post imputation. For the beta regression and random effects models, both the pre and post imputation modelling can be found within the same script. 

# Getting started 

To replicate this analysis, clone this repository on your local machine

git clone https://github.com/Maysont/LAC-ofsted-outcomes-model.git


