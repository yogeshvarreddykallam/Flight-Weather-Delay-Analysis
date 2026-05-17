# Flight & Weather Delay Analysis — CSE 561

Predicting US flight departure delays using weather conditions at origin airports. Built a Random Forest classifier with extensive feature engineering and EDA across multiple cities.

## Overview
- Merged flight records with city-level weather data (Chicago, Dallas, Kansas, Minneapolis, Des Moines)
- Feature engineering: cyclical encoding of time features, weather aggregates, traffic load
- Model: Random Forest with hyperparameter tuning
- Evaluation: accuracy, confusion matrix, ROC curve, feature importance

## Results
Key plots in :
| Plot | Description |
|---|---|
|  | Model comparison |
|  | Feature importance ranking |
|  | Confusion matrix |
|  | ROC curve |
|  | Cyclical time feature encoding |
|  | Data skew analysis |

## Files
| File | Description |
|---|---|
|  | Full pipeline — EDA, feature engineering, modeling, evaluation |
|  | Result and analysis plots |

> **Data**: Weather CSVs (~6–17MB each) and flight data are not included due to size. Download from Bureau of Transportation Statistics and NOAA.

## Tech Stack
Python · pandas · scikit-learn · matplotlib · seaborn · numpy

## Course
CSE 561 — Penn State University

## Author
Yogeshvar Reddy Kallam
