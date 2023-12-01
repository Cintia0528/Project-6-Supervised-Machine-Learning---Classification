# Supervised Machine Learning - Classification
## Goal
To classify properties into "Expensive" / "Not Expensive" categories with the help of Supervised Machine Learning.  

## Overview 
We are interested in making better investment decisions, and hence evaluating properties based on 70+ features, whether they qualify as expensive or inexpensive properties.

## Context
Trying out and fine-tuning a variety of Machine Learning models to get the best prediction

1. Is our Machine Learning model predicting the value of properties successfully?
2. What type of errors are most prone for each of the models?

### Task: 
* Import database of over 1500 properties
* Explore, analyze and clean over 70 features
* Try and fine-tune ML models for the best outcome

## Deliverables
The **Google Colab Notebook** for trying out different ML algorithms is found [here](https://github.com/Cintia0528/Project-6-Supervised-Machine-Learning---Classification/blob/1c9d84d012a3df27d01b413010a3be04dec79acf/5_b_Housing_Model_Selection_.ipynb).
Further Machine Learning experimentation with LazyPredict and VotingClassifier is found [here](https://github.com/Cintia0528/Project-6-Supervised-Machine-Learning--Classification-/blob/aa13379741c4444573b21000712825789fd7ef70/5_c_Housing_Model_Selection_LazyPredict%20(1).ipynb), with a supporting Medium article [here](https://medium.com/@ubp0528/another-ml-puzzle-decoding-the-factors-behind-expensive-homes-a6f096aa91e1).

## Skills & Tools
1. Data Reading & Cleaning 
2. Data Splitting 
3. Building a Preprocessor
4. Modelling ( Decision Tree, KNN, Random Forest, XGBoost)
5. Fine Tuning
6. Error Analysis

## Further Analysis
1. Perfecting the model with Lazy predict
2. Pooling individual models' strength with Voting Classifier

Note: In the notebook the Lazypredict + VotingClassifier combo gave us approximately 95%, but when applied to brand new dataset via a Streamlit application it had the highest accuracy with over 97%.  
