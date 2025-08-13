# Bayesian Housing Price Prediction  
Interactive Counterfactual Analysis with Bayesian Linear Regression

**Author:** Adarsh Pratap Singh  
**College:** Ajay Kumar Garg Engineering College (3rd Year B.Tech)  
**Internship:** YBI Foundation – Data Science & Machine Learning with Python

## Table of Contents

- [Motivation](#motivation)
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Files in this Repository](#files-in-this-repository)
- [License](#license)
- [Contact](#contact)

## Motivation

Accurate housing price prediction is important in real estate and finance. Traditional models provide point estimates but do not communicate prediction uncertainty. The goal of this project is to use Bayesian Linear Regression to quantify uncertainty, and to develop an interactive tool for "what-if" analyses.

## Overview

This project predicts housing prices in California using Bayesian Linear Regression. An interactive interface is included to let users explore how different features impact the predicted price and associated uncertainty. The tool runs entirely in Google Colab for accessibility and ease of use.

## Features

- Bayesian Linear Regression for probabilistic, interpretable predictions
- Uses the California Housing dataset from Scikit-learn
- Interactive counterfactual tool with input feature sliders
- Displays 95% credible intervals for each prediction
- Runs in Google Colab, no installation needed
- Well-documented, modular code

## Getting Started

1. Open the notebook in [Google Colab](https://colab.research.google.com/github/aDARSH41Hub/BayesianHousingPrediction/blob/main/ML_Project.ipynb)
2. In Colab, click "Runtime" then "Run all"
3. Go to the interactive section at the end of the notebook
4. Use the sliders to change input features and view updated predictions and credible intervals

## Project Workflow

1. Data loading and preprocessing using the California housing dataset
2. Model training with Bayesian Linear Regression
3. Interactive prediction using sliders for feature input
4. Visualization of predictions with 95% credible intervals
5. Counterfactual analysis to see how different factors affect housing prices

## Results

The model predicts prices and displays credible intervals, reflecting the uncertainty in each prediction. For example, increasing the number of rooms generally increases the predicted price and may also widen the credible interval, showing increased uncertainty for more extreme values. The interactive tool helps users see both the prediction and the confidence in that prediction.

## Files in this Repository

| File                   | Description                                                    |
|------------------------|----------------------------------------------------------------|
| `ML_Project.ipynb`     | Main Colab notebook with model, visualizations, and tool       |
| `README.md`            | Project description and usage instructions                     |
| `requirements.txt`     | Python dependencies                                            |
| `demo_screenshot.png`  | Screenshot of the interactive tool                             |

## License

This project is licensed under the MIT License.

## Contact

For questions or feedback:  
paradoxic493@gmail.com  
LinkedIn: [ LinkedIn Profile Link](https://www.linkedin.com/in/adarsh-pratap-singh-52632630a/)

This project was completed as part of the Data Science & Machine Learning internship at YBI Foundation.
