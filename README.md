# Mushroom Classification Dataset

This repository contains code to explore, visualize, preprocess, and build machine learning models on the mushroom classification dataset.

## Dataset Description

The dataset contains descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family. Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one.

The attributes for each mushroom sample include morphological features such as cap shape, cap color, habitat, as well as physical features like stalk shape and root type. 

## Data Analysis and Visualization

The code performs the following analysis and visualization:

- Plots counts of each attribute by class to visualize class imbalance
- Computes correlations between attributes  
- Encodes categorical attributes for modeling
- Splits data into train and test sets

## Modeling

The following classification models are trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors  
- Linear Support Vector Machine
- Kernel Support Vector Machine
- Gaussian Naive Bayes

Models are compared based on training and test accuracy. Confusion matrices are also plotted.
