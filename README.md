# Adopt-a-buddy

A Machine Learning Challenge conducted by HackerEarth.   

[Click Here to see Adopt a Buddy Challenge in HackerEarth](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-pet-adoption/problems/  "Adopt a Buddy Challenge")

# Problem Statement as mentioned in the challenge
&nbsp; &nbsp; ***A leading pet adoption agency is planning to create a virtual tour experience for their customers showcasing all animals that are available in their shelter. To enable this tour experience, you are required to build a Machine Learning model that determines type and breed of the animal based on its physical attributes and other factors.***

# Data Description
The data folder consists of 2 CSV files
- train.csv - 18834 x 11
- test.csv - 8072 x 9

# Targets
* breed_category
* pet_category

# Approach
* Preprocessing & Feature Engineering.
  - Converted height(meters) to height(centimeters).
  - selected all columns except pet_id and dates columns.
  - coverting color_types to a constant using [LabelEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html#sklearn-preprocessing-labelencoder).
* Algorithm used for prediction.
  - [Lightgbm classifier](https://lightgbm.readthedocs.io/en/latest/pythonapi/lightgbm.LGBMClassifier.html).
* Making prediction table.
