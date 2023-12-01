# Multi-agency Rocky Networks Species Distributions Data Science Project

## Overview

This repository contains code for a visualization and machine learning modeling project focused on Multi-agency Rocky Networks Species Distributions. The project is divided into two main parts: visualization and modeling. We cooperated with UCSC MARINe to realize this  data science project.

## Visualization

### Description

The visualization part of the project utilizes the Pyecharts library in Python to create interactive charts and maps. The visualizations cover eight sites and include:

1. Geo-surface visualizations for each site
2. 3D scatter plots showcasing species distributions
3. Bar charts, river charts, and pie charts for species statistics
4. An interactive map integrating all visual results

### Requirements

- Python
- Pyecharts library
- Other dependencies specified in the `requirements.txt` file

### Usage

1. Use web browser to view the website by this link: https://raphaelyangwj.github.io/UCSC-MARINe-DS-Project/Websites/Navigation_page.html

## Machine Learning Modeling

### Description

The modeling part of the project focuses on predicting species distributions based on Sea Level Rise (Mean Z Rock Height). Two techniques are employed:

1. **Logistic Regression:**
   - Performs binary classification to identify specific species distribution probability.
2. **Neural Networks:**
   - Conducts multi-class regression to predict species distributions for five categories across eight sites.

### Requirements

- Python
- Necessary machine learning libraries (e.g., Pytorch, Scikit-learn)

## Project Structure

```
plaintextCopy code|_ data/                  # Data files used for visualization and modeling
|_ results/               # Output visualizations and modeling results
|_ visualization.py       # Python script for visualization
|_ logistic_regression.py  # Python script for Logistic Regression modeling
|_ neural_networks.py      # Python script for Neural Networks modeling
|_ README.md               # Project documentation
```

Feel free to explore and adapt the scripts to suit your needs. If you have any questions or issues, please create a GitHub issue, and we'll be happy to assist you.

## Contributors

- **UC Berkeley:** Weijie Yang, Jenna Sparks
- **UCSC Team:** Peter Raimondi, Melissa Miner, Rani Gaddam, 

Thank you for visiting the Multi-agency Rocky Networks Species Distributions Project and Feel free to contact us.

Weijie Yang: raphaelyang1998@berkeley.edu

Jenna Saprks: jenna_sparks@berkeley.edu
