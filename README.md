# Kaggle Games
This repo collects my notebooks of Kaggle, a data science competition site, games.

### Quick Start
1. clone the repository.

```
$ git clone https://github.com/saluf/ml-kaggle-games.git
```

2. get data from Kaggle and put it in a folder "data" under each game

```
#ex: to run notebook under 01_house_prices, then put all input data under
/01_house_prices/data/ #<- put you data here
```

## 01 House Prices
[House Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) is about building a regression model to predict recidential real estate prices.

### Key Features
- Apply simple data clean and feature engineering to deal with missing values, outliers, non-linearity, collinearity
- Use extremely simple linear ridge regression model to catch the behavior

The notebook is also shared on [Kaggle](https://www.kaggle.com/sal001/beginner-s-note-top-12-by-single-linear-model)

## 02 Predict Futreu Sales
[Predict Futreu Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales) provides 3 years hisorical sale data of kinds of 22,000 items from 60 shops. The sale data is from the largest software firms in Russia, 1C company. Players aim to predict how many it could be sold in the very next month in item-shop pair basis.

### Key Features
- Extracted IP (ex: GTA, Batman,...) from item names to be new features
- Import Google Trends Internet popularity data to form another feature for prediction
- Tranin model by single GPU-accelerated XGboost which construct fast and satisfactory model
- Reach top 5% on the leaderboard

The notebook is also shared on [Kaggle](https://www.kaggle.com/sal001/google-trends-for-sale-prediction-xgboost)



