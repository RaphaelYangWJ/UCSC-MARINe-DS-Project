# 🌊 Multi-Agency Rocky Intertidal Network Species Distributions Data Science Project

## Overview

### This repository contains code for a visualization and machine learning modeling project focused on intertidal species distributions. The project is divided into two main parts: visualization and modeling. We collaborated with University of California, Santa Cruz Multi-Agency Rocky Intertidal Network (MARINe) Team to realize this data science project.

## Visualization

### Description

The visualization part of the project utilizes the Pyecharts library in Python to create interactive charts and maps. The visualizations cover eight sites and include:

1. Geo-surface visualizations for each site
2. 3D scatter plots showcasing species distributions
3. Bar charts, river charts, and pie charts for site's species statistics
4. An interactive map integrating all visual results

### Requirements

- Python
- Pyecharts library
- Other dependencies specified in the `requirements.txt` file

### Usage

1. Use web browser to view the website by this link: https://raphaelyangwj.github.io/UCSC-MARINe-DS-Project/Websites/Navigation_page.html

## Machine Learning Modeling

### Description

The modeling part of the project focuses on predicting species distributions based on mean sea level rise (Mean(z_rock_height). Two approaches were employed:

1. **Single Species Prediction:**
Performs binary classification to identify specific species distribution probability
   - Logistic Regression
   - Random Forest
   - 
2. **Multi-Species Prediction:**
Conducts multi-class regression to predict species distributions for five categories across eight sites.
   - Neural Networks

### Requirements

- Python
- Necessary machine learning libraries (e.g., Pytorch, Scikit-learn)

## Project Structure

```
|_ Code Notebooks/
   |_ Homepage_Interactive_Map.ipynb
   |_ UCSC_Academic_Research_MARINe_Site_Visualisation_Notebook.ipynb
   |_ ddiscovery_elevation_data_update_20231108.xlsx
   |_ homepage_sites_data.csv
|_ Machine_Learning/
|_ Binary_Classification_LR_RF/     # Modeling Files for Logistic Regression and Random Forest
   |_ dataset/     # Dataset folder
      |_ point_contact_numeric_raw_lumped logisitic knotted spline mussels for the eight sites for data vis (1 M slr).csv        # Mussel only dataset
   |_ musselpredict_lr.ipynb
   |_ musselpredict_rf_fixedsample.ipynb   # Resample to unbias dataset
   |_ musselpredict_rf_oversample.ipynb    # Resample to unbias dataset
|_ Multiclass_Neural_Networks/      # Modeling Files for Neural Networks
   |_ NN - Feature Engineering.ipynb
   |_ Phase I - Neural Networks.ipynb
   |_ Phase II - Neural Networks.ipynb
   |_ neural_network_model/         # Trained-model parameters
      |_ Phase I - Species Distribution Model.pth
      |_ Phase II - Species Distribution Model.pth
   |_ dataset/      # Dataset folder
      |_ raw_data.xlsx
      |_ phase_1_testset.csv
      |_ phase_1_trainset.csv
      |_ phase_2_testset.csv
      |_ phase_2_trainset.csv
|_ Websites/
   |_ source_pic
      |_ Bogeda.jpg
      |_ Cape Arago.jpg
      |_ Forgarty Creek.jpg
      |_ berkeley_logo.png
      |_ home_bg.png
      |_ map_temp.png
      |_ ml.jpeg
      |_ reg.jpeg
   |_ Navigation_page.html
   |_ UCSC_MARINe_Homepage.html
   |_ bob_creek.html
   |_ bodega.html
   |_ buck_gulley_south.html
   |_ cape_arge.html
   |_ fogarty_creek.html
   |_ heisler_park.html
   |_ point_fermin.html
   |_ white_point.html
|_ pyecharts-assets-master/
   |_ assets
|_ README.md
```

Feel free to explore and adapt the scripts to suit your needs. If you have any questions or issues, please create a GitHub issue, and we'll be happy to assist you.

## Contributors

- **University of California, Berkeley:** Weijie Yang, Jenna Sparks
- **University of California, Santa Cruz:** Peter Raimondi, Melissa Miner, Rani Gaddam, 

Thank you for visiting the Multi-Agency Rocky Intertidal Network Species Distributions Project!

Weijie Yang: raphaelyang1998@berkeley.edu
Jenna Saprks: jenna_sparks@berkeley.edu
