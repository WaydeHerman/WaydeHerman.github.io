# Data Science Portfolio

Portfolio of my data science projects.

My Linkedin profile: [Linkedin](https://www.linkedin.com/in/wayde-herman/)

My Kaggle profile: [Kaggle](https://www.kaggle.com/waydeherman/)

My HackerRank profile: [HackerRank](https://www.hackerrank.com/wayde_h)

**Noteable achievements** include coming in the top 2% in [Kaggle CareerCon 2019](https://www.kaggle.com/c/career-con-2019) competition as well as coming 5th (out of 1600 students) in [mlcourse.ai](https://mlcourse.ai/rating)

---

### [Expected Goals Model:](https://github.com/WaydeHerman/Expected_Goals)

An end-to-end football expected goals model. The predictions are the probability of a shot resulting in a goal.

Interesting things about this project include the structure as well as the evaluation of calibration. The code is structured as a pipeline with the code intending to be reusable and modular as opposed to a once off project. Models are tuned using a predefined hyperparameter space stored in dictionaries.

The models are evaluated both by their predictive performance as well as the calibration of their predictions. The latter is evaluated using visual inspection of their calibration curves as opposed to a single metric, which is usually advised.

**Keywords:** Python (Pandas, Matplotlib) / Logistic Regression / SVM / Random Forest / Gradboost / XGBoost / Calibration / Model Pipeline

![example result](/Arsenal_Chelsea_2014-2015.png "Example Result")

---

### [Kaggle CareerCon 2019:](https://github.com/WaydeHerman/Kaggle_CareerCon_2019)

My top 2% solution to [Kaggle's CareerCon 2019 competition](https://www.kaggle.com/c/career-con-2019)

Interesting things about this project include the out-of-the-box solution used to overcome the noise in the data. The sequences provided were too noisy to classify accurately so a novel method of chaining together sequences was used. This method was based on the sequences' orientation data.

Each sequence was first labelled using a random forest classifier. Then the sequences were chained together. Each sequence then 'voted' for the classification of the entire chain which then overruled each individual sequence's original labels.

**Keywords:** Python / Time Series / Scikit Learn / Random Forest

---

### [Categorical Feature Encoding Tutorial:](https://www.kaggle.com/waydeherman/tutorial-categorical-encoding)

Tutorial describing various ways of representing categorical features for machine learning models.

**Keywords:** Tutorial / Feature Engineering / Categorical Features
