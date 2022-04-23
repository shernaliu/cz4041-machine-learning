# Kaggle Competition - Realty Price Prediction for Sberbank Russian Housing Market

Our GitHub repository contains the datasest downloaded from Kaggle, Python code in Jupyter Notebooks and submissions (CSV Files) for the [Kaggle Challenge on Realty Price Prediction for Sberbank Russian Housing Market](https://www.kaggle.com/c/sberbank-russian-housing-market/overview/timeline). 

## File Description

| File Name     | Description   |
| ------------- | ------------- |
| ExploratoryDataAnalysis.ipynb | Contains the source codes to perform exploratory data analysis and data visualizations. |
| FeatureEngineering.ipynb | Contains the source code to perform data preparation, model hyperparameter tuning, and model fitting. |

## Leaderboard Scores and Ranking

| Model | Private Score | Public Score | Public Rank |
| ----- | ----- | ----- | ----- |
| Random Forest | 0.35739 | 0.35275 | 2668 |
| Decision Trees | 0.36366 | 0.36380 | 2734 |
| XGBoost | 0.37180 | 0.36423 | 2735 |
| SGD Regressor | 9.09261 | 9.07412 | 3260 |
| AdaBoost | 0.70015 | 0.70313 | 3220 |
| LightGBM | 0.32451 | 0.32355 | 1831 |
| Naïve XGBoost Raw | 0.32162 | 0.31741 | 1384 |
| LightGBM Raw | 0.31443 | 0.31041 | 532 |
| Custom Model | 0.36969 | 0.36742 | 2751 |

All the final prediction .csv files can be found in the `code/output_models`.

## Video Presentation
The YouTube presentation video link can be found at [here](https://youtu.be/AiheoHESNiw).

## Installing CZ4041

```
# clone this project
git clone https://github.com/shernaliu/cz4041.git
```
Anaconda is used as the package manager.
The packages used in this project are exported to `req.txt` file.
```
# install the environment using
conda create -n <environment-name> --file req.txt
```

To open the Jupyter Notebook, you can use Jupyter Lab.
```
jupyter lab
```

## Authors

* Sherna [@shernaliu](https://github.com/shernaliu)
* NengQi [@huangnq96](https://github.com/huangnq96)
* Mark [@mtrhorange](https://github.com/mtrhorange)
* Benjamin [@gohbwj](https://github.com/gohbwj)
