# Unsupervised and Supervised Analysis of Protein Sequences

Course project for *Computational Science – Machine Learning for Physicists* (Sorbonne Université).

## Overview

This project explores the structure of protein sequence space using a combination of unsupervised, supervised, and generative machine learning methods.

The main goal is to understand whether protein functionality can be inferred from sequence data, and how natural and artificial sequences are organized in sequence space.

## Methods

- one-hot encoding of protein sequences
- PCA for dimensionality reduction
- clustering with k-means and DBSCAN
- supervised classification with logistic regression, k-NN, and CNN
- generative modeling with a variational autoencoder (VAE)

## Main results

- functional and non-functional sequences are not clearly separated by unsupervised methods
- supervised models can still learn predictive signals from sequence data
- generated sequences preserve the global geometry of natural sequence space
- the VAE captures meaningful statistical structure in the data

## Files

- `analysis_notebook.ipynb` — full notebook with code, analysis, and results
- `presentation.pdf` — project presentation
- `project_assignment.pdf` — original project description

## Author

Pietro Scapolo