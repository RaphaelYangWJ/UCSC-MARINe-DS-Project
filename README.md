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
plaintextCopy code|_ Machine_Learning/   # Data files for Modeling
|_ Binary_Classification/               # Output Binary_Classification

|_ Multiclass_Neural_Networks/      # Modeling Files for Neural Networks
   |_ NN - Feature Engineering.ipynb      # Jupyter Notebook for EDA & Feature Engineering
   |_ Phase I - Neural Networks.ipynb      # Jupyter Notebook for Phase I Neural Networks (By Pytorch)
   |_ Phase II - Neural Networks.ipynb      # Jupyter Notebook for Phase II Neural Networks (By Pytorch)
   |_ neural_network_model/      # Trained-model parameters
      |_ Phase I - Species Distribution Model.pth      # Phase I trained model
      |_ Phase II - Species Distribution Model.pth      # Phase II trained model
   |_ dataset/      # Dataset folder
      |_ raw_data.xlsx      # Raw dataset used in Feature Engineering
      |_ phase_1_testset.csv      # Testset for Phase I modeling
      |_ phase_1_trainset.csv      # Trainset for Phase I modeling
      |_ phase_2_testset.csv      # Testset for Phase II modeling
      |_ phase_2_trainset.csv      ## Trainset for Phase II modeling
```

Feel free to explore and adapt the scripts to suit your needs. If you have any questions or issues, please create a GitHub issue, and we'll be happy to assist you.

## Contributors

- **University of California, Berkeley:** Weijie Yang, Jenna Sparks
- **University of California, Santa Cruz:** Peter Raimondi, Melissa Miner, Rani Gaddam, 

Thank you for visiting the Multi-Agency Rocky Intertidal Network Species Distributions Project!

Weijie Yang: raphaelyang1998@berkeley.edu
Jenna Saprks: jenna_sparks@berkeley.edu
