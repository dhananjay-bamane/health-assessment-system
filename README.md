# Multiple Disease Predictor

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:

- Diabetes
- Breast Cancer
- Heart Disease
- Kidney Disease
- Liver Disease
- Malaria
- Pneumonia

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Diabetes       | Machine Learning Model   | 74.48%   |
| Heart Disease  | Machine Learning Model   | 85.25%   |
| Kidney Disease | Machine Learning Model   | 99%      |

## NOTE

==> You can access the website live at: https://health-assessment-system.onrender.com <br>
==> Python version 3.6.8 was used for the whole project.<br>

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.

3. Install all the dependencies:

```
pip install -r requirements.txt
```

4. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.

- [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)


