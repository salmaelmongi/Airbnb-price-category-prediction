# Airbnb Listing Price Prediction 🏠💰

## Overview:##


One of the biggest challenges for Airbnb hosts is determining the optimal price for their property listings. While some hosts may browse existing listings for reference, this manual approach can be time-consuming and may not always yield accurate results. In this Kaggle competition, we aim to enhance the user experience for potential Airbnb hosts by developing a machine learning model to predict the price range of their listings based on various listing characteristics.

## Problem Statement:##


The primary goal of this competition is to predict the price category for Airbnb listings in Montreal. Instead of predicting the actual price, we've divided pricing into three distinct categories: beginner, plus, and premium. Each listing will be assigned one of these categories (denoted by 0, 1, or 2), allowing new hosts to receive pricing recommendations tailored to their listings.

## Data Description:##


The dataset used for this competition contains information about various property listings in different areas of Montreal, collected during the year 2019. The dataset includes a rich set of features for each listing, providing comprehensive information to facilitate the price range predictions.

## Approach:##


This problem will be approached using a multi-objective (multi-task) and multi-modality solution. This method makes use of both the structured data connected with each listing as well as potentially any picture or text data. It enables to make price category forecasts while taking into account different features of the listing.

*Note:* the dataset can be found at https://www.kaggle.com/competitions/copy-of-cisc-873-dm-w23-a4/overview
