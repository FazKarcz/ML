# Projekt: Predykcja Ceny Wynajmu Mieszkań
The aim of the project was to build a regression model that, based on apartment data (location, number of rooms, area, etc.), predicts a realistic rental price.

## Models used:
* Random Forest Regressor
* XGBoost Regressor
* Linear Regression

## Wyniki modeli:
  | Model |                      | MAE |                   | RMSE |                  | R² |
  | --------------------- | ----------------- | ----------------------------- | --------------- |
  | **Random Forest**     | 524 zł            | 682 zł                        | 0.839           |
  | **XGBoost**           | 527 zł            | 662 zł                        | 0.849           |
  | **Linear Regression** | **407 zł**        | **512 zł**                    | **0.910**       |
