# Heart-Disease-Detection-With-LogisticRegression

Jupyter Notebook
README.md
11/12/2020
GitHub Flavored Markdown
File
Edit
View
Language
23
8. [Cross Validation](#cross-val)
24
9. [Model Building](#data-model)
25
10. [Model evaluation & comparison](#model-eval)<br>
26
11. [Feature Selection](#model-eval)<br>
27
12. [Model Evaluation](#model-inter)
28
13. [Conclusion](#data-conc)
29
​
30
## About Data 
31
​
32
This dataset consists of 11 features and a target variable. It has 6 nominal variables and 5 numeric variables. The detailed description of all the features are as follows:
33
​
34
**1. Age:** Patients Age in years (Numeric)<br>
35
**2. Sex:** Gender of patient (Male - 1, Female - 0) (Nominal)<br>
36
**3. Chest Pain Type:** Type of chest pain experienced by patient categorized into 1 typical, 2 typical angina, 3 non-anginal pain, 4 asymptomatic (Nominal)<br>
37
**4. resting bp s:** Level of blood pressure at resting mode in mm/HG (Numerical)<br>
38
**5. cholestrol:** Serum cholestrol in mg/dl (Numeric)<br>
39
**6. fasting blood sugar:** Blood sugar levels on fasting > 120 mg/dl represents as 1 in case of true and 0 as false (Nominal)<br>
40
**7. resting ecg:** Result of electrocardiogram while at rest are represented in 3 distinct values 0 : Normal 1: Abnormality in ST-T wave 2: Left ventricular hypertrophy (Nominal)<br>
41
**8. max heart rate:** Maximum heart rate achieved (Numeric)<br>
42
**9. exercise angina:** Angina induced by exercise 0 depicting NO 1 depicting Yes (Nominal)<br>
43
**10. oldpeak:** Exercise induced ST-depression in comparison with the state of rest (Numeric)<br>
44
**11. ST slope:** ST segment measured in terms of slope during peak exercise 0: Normal 1: Upsloping 2: Flat 3: Downsloping (Nominal)<br>
45
​
46
#### Target variable
47
**12. target:** It is the target variable which we have to predict 1 means patient is suffering from heart risk and 0 means patient is normal.
48
​
49
## Installations :
50
This project requires Python 3.x and the following Python libraries should be installed to get the project started:
51
- [Numpy](http://www.numpy.org/)
52
- [Pandas](http://pandas.pydata.org/)
53
- [matplotlib](https://matplotlib.org/)
54
- [scikit-learn](https://scikit-learn.org/stable/)
55
- [seaborn](https://seaborn.pydata.org/installing.html)
56
- [xgboost](https://xgboost.readthedocs.io/en/latest/build.html)
57
​
58
I also reccommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project which also include jupyter notebook to run and execute [IPython Notebook](http://ipython.org/notebook.html).
59
​
60
## Code :
61
Actual code to get started with the project is provided in two files one is,```heart-disease-classification.ipynb```
62
​
63
## Run :
64
In a terminal or command window, navigate to the top-level project directory PIMA_Indian_Diabetes/ (that contains this README) and run one of the following commands:
65
​
66
```ipython notebook heart-disease-classification.ipynb```
67
or
68
​
69
```jupyter notebook heart-disease-classification.ipynb```
70
​
71
This will open the Jupyter Notebook software and project file in your browser.
72
​
73
## Model Evaluation :
74
I have done model evaluation based on following sklearn metric.
75
1. [Cross Validation Score](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html)
76
2. [Confusion Matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)
77
3. [Plotting ROC-AUC Curve](https://en.wikipedia.org/wiki/Receiver_operating_characteristic)
78
4. [Plotting Precision recall Curve](https://acutecaretesting.org/en/articles/precision-recall-curves-what-are-they-and-how-are-they-used)
79
5. [Sensitivity and Specitivity](https://en.wikipedia.org/wiki/Sensitivity_and_specificity)
80
6. [Classification Error](https://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/)
81
7. [Log Loss](https://www.kaggle.com/dansbecker/what-is-log-loss#:~:text=Log%20Loss%20is%20a%20slight,by%20understanding%20the%20likelihood%20function.)
82
8. [Mathew Correlation coefficient](https://www.kaggle.com/dansbecker/what-is-log-loss#:~:text=Log%20Loss%20is%20a%20slight,by%20understanding%20the%20likelihood%20function.)
83
​
84
​
