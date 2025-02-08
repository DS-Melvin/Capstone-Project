## DS-670 Capstone Project  
---
### Saint Peter's University  
---
This repository contains all the files and resources used to complete my project. Codes and Jupyter notebook containing the step-by-step guide of data mining process.  
This readme.md will be updated as the repository is updated.
---
#### **Title - Crop Yield Prediction using Machine Learning (Crop Recommendation System)**
---
### Overview:
---
1. I have developed a comprehensive crop recommendation system by integrating multiple datasets related to temperature, rainfall, crop yield, and pesticide usage.
2. I began with data preprocessing, which involved cleaning, merging, and imputing missing values in the datasets.
3. Following this, I conducted an exploratory data analysis (EDA) to understand the distributions and correlations within the data.
4. I then implemented and evaluated several learning models, including DecisionTree, RandomForest, SVM, and KMeans clustering, assessing their performance using metrics such as MSE, R2, and inertia.
5. Lastly, I fine-tuned the hyperparameters of these models using GridSearchCV to optimize their performance.
6. The project encapsulates the essential data mining steps, from preprocessing and EDA to model selection, implementation, and hyperparameter optimization, providing a robust framework for crop recommendations.
7. After merging and cleaning the datasets to ensure only numeric columns remain, I handled missing values by imputing them with the mean using the SimpleImputer from sklearn, ensuring a complete dataset for modeling.
8. The target variable, Value_x, from the crop yield dataset, represents the crop yields we aim to predict.
9. The process involved preparing the data for learning models by replacing missing values and clearly defining the target variable, which is essential for training and evaluating our models to predict crop yields effectively.

### Datasets
The Sources of the Data can be found here:
- crop_yield: [FAOSTAT](http://www.fao.org/faostat/en/#data/QC)
- crop_pesticides: [FAOSTAT](http://www.fao.org/faostat/en/#data/RP)
- rainfall(1): [World Bank Group | Climate Change Knowledge Portal](https://climateknowledgeportal.worldbank.org/download-data)
- temperature: [World Bank Group | Climate Change Knowledge Portal](https://climateknowledgeportal.worldbank.org/download-data)
