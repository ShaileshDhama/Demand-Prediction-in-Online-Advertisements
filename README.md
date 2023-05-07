# Demand Prediction in Online Advertisements

This repository contains the code and documentation for the project "Demand Prediction in Online Advertisements" by Shailesh Dhama. The goal of this project is to predict the demand for an online classified ad based on its full description, context, and historical demand for similar ads. The project involves both natural language processing (NLP) on Russian text data and image data along with numerical data.

## Dataset

The data used in this project is from the Avito Demand Prediction Challenge on Kaggle, which can be found [here](https://www.kaggle.com/c/avito-demand-prediction/data). The dataset includes train and test data, supplemental data, and image data.

## Approach

The project follows the following approach:

1. Data processing and exploratory data analysis (EDA)
2. Build a Convolutional Neural Network (CNN)
3. Show important plots
4. Test the model

### Data Processing and Exploratory Data Analysis

The first step of the project is data processing and exploratory data analysis. This includes loading and processing data, and exploring the data with visualizations. Important visualizations include:

- Region distribution
- Deal probability by region
- City-wise distribution of ads
- Parent category distribution
- Deal probability by parent category
- Category name of ads count
- User type distribution
- Log of price histogram
- Activation dates in train and test
- Number of users in train and test
- Number of titles in train and test
- Number of words in title column
- Number of words in description column
- Distribution of deal probability
- Demand visualization among Russia
- Good online advertisements
- Bad online advertisements

### Build a Convolutional Neural Network

The second step is building a Convolutional Neural Network (CNN) to predict the demand for an online classified ad based on its image. The model used in this project is the VGG16 model.

### Show Important Plots

The third step is showing important plots. The visualizations include:

- VGG16 model summary

### Test the Model

The fourth and final step is testing the model.

## Results

The project produced important visualizations that provide insights into the data. These visualizations include region distribution, deal probability by region, city-wise distribution of ads, parent category distribution, deal probability by parent category, category name of ads count, user type distribution, log of price histogram, activation dates in train and test, number of users in train and test, number of titles in train and test, number of words in title column, number of words in description column, distribution of deal probability, demand visualization among Russia, good online advertisements, and bad online advertisements.

The project also produced a CNN model based on the VGG16 architecture to predict the demand for an online classified ad based on its image.

For more information, see the project's [Jupyter notebook](./Demand%20Prediction%20in%20Online%20Advertisements.ipynb).

## Repository Structure

```
├── README.md                                   <- The top-level README for reviewers
├── Demand%20Prediction%20in%20Online%20Advertisements.ipynb  <- Narrative documentation of analysis
├── https://www.kaggle.com/c/avito-demand-prediction/data     <- Dataset
└── images                                      <- generated from code
```

## Citing

If you use this project for your research, please consider citing:

```
@misc{Shailesh:2020,
  Author = {Shailesh Dhama},
  Title = {Demand Prediction in Online Advertisements},
  Year = {2020},
  Publisher = {GitHub},
  Journal = {GitHub repository},

