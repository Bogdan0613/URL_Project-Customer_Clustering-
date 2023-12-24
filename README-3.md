
# Midterm Clustering Project

About the Dataset: ./german_credit_data.csv

## Context

The original dataset contains 1000 entries with 20 categorical/symbolic attributes. In this dataset, each entry represents a person who takes credit from a bank. Each person is classified as good or bad credit risks according to the set of attributes.

## Content

    Age (numeric)
    Sex (text: male, female)
    Job (numeric: 0 — unskilled and non-resident, 1 — unskilled and resident, 2 — skilled, 3 — highly skilled)
    Housing (text: own, rent, or free)
    Saving accounts (text — little, moderate, quite rich, rich)
    Checking account (numeric, in DM — Deutsch Mark)
    Credit amount (numeric, in DM)
    Duration (numeric, in month)
    Purpose (text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others)

## Your assignment (points in brackets):

    (1P) Analyze and clean the data
        How many rows and columns and which data types?
    (1P) Encode and normalize the data
    (2P) Perform PCA and t-SNE to visualize data
    (3P) Find clusters by using k-means, Hierarchical Clustering, and DBSCAN
    (3P) Explain your results