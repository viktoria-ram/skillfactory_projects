{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# ReadMe.MD\n",
    "\n",
    "### Project 6, SF-DST-Pro Car Price prediction\n",
    "\n",
    "The goal of the project is to predict car price based on the auto characteristics which we can get on [auto.ru](https://auto.ru/) website. \n",
    "\n",
    "### repository structure\n",
    "#### 1. parsing [auto.ru](https://auto.ru/)\n",
    "- **`0.autoru_parsing.ipynb`** creates a dataset based on parsed data from [auto.ru](https://auto.ru/) website\n",
    "- select features we have in the test dataset in kaggle \n",
    "\n",
    "#### 2. data preparing\n",
    "The data format in test dataset in kaggle defer from parsed dataset. So we have to bring features and values to the same format. In happens in **`1.prepare_dataset_for_kaggle.ipynb`** notebook. \n",
    "In summary in notebook you can find the descriptions which main changes have been made. \n",
    "\n",
    "#### 3. EDA, modeling and predictiong\n",
    "- **`2.main`** this is the you'll find in kaggle. \n",
    "Here you can find the main work. EDA, modeling and predictions with different ML algorithms.\n",
    "\n",
    "Parsing and bring the data into the same format like test dataset took a lot of time and I didn't have time for modeling and parameter tuning. \n",
    "I tried following algorithms: \n",
    "\n",
    "- `Catboost`\n",
    "- `XGBoost`\n",
    "- `LightGBM`\n",
    "- `Ansambling`\n",
    "\n",
    "Catboost gave the best Score in Kaggle. \n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
