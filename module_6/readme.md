# ReadMe.MD

### Project 6, SF-DST-Pro Car Price prediction

The goal of the project is to predict car price based on the auto characteristics which we can get on [auto.ru](https://auto.ru/) website. 

### repository structure
#### 1. parsing [auto.ru](https://auto.ru/)
- **`0.autoru_parsing.ipynb`** creates a dataset based on parsed data from [auto.ru](https://auto.ru/) website
- select features we have in the test dataset in kaggle 

#### 2. data preparing
The data format in test dataset in kaggle defer from parsed dataset. So we have to bring features and values to the same format. In happens in **`1.prepare_dataset_for_kaggle.ipynb`** notebook. 
In summary in notebook you can find the descriptions which main changes have been made. 

#### 3. EDA, modeling and predictiong
- **`2.main`** this is the you'll find in kaggle. 
Here you can find the main work. EDA, modeling and predictions with different ML algorithms.

Parsing and bring the data into the same format like test dataset took a lot of time and I didn't have time for modeling and parameter tuning. 
I tried following algorithms: 

- `Catboost`
- `XGBoost`
- `LightGBM`
- `Ansambling`

Catboost gave the best Score in Kaggle. 
