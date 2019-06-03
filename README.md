# Data Science Portfolio

Portfolio of my data science project(s).

My Linkedin profile: [Linkedin](https://www.linkedin.com/in/wayde-herman/)

My Kaggle profile: [Kaggle](https://www.kaggle.com/waydeherman/)

**Noteable achievements** include coming top 2% in [Kaggle CareerCon 2019](https://www.kaggle.com/c/career-con-2019) competition as well as coming 5th (out of 1600 students) in [mlcourse.ai](https://mlcourse.ai/rating)

---

### [Expected Goals Model:](https://github.com/WaydeHerman/Expected_Goals)

An end-to-end football expected goals model. The predictions are the probability of a shot resulting in a goal.

Interesting things about this project include the structure as well as the evaluation of calibration. The code is structured as a pipeline with the code intending to be reusable and modular as opposed to a once off project. Models are tuned using predefined hyperparameter space stored in config files.

The models are evaluated both by the prediction performance as well as the calibration of their predictions. The latter is evaluated using visual inspection of their calibration curves as opposed to a single metric, which is usually advised.

**Keywords:** Python (Pandas, Matplotlib) / Logistic Regression / SVM / Random Forest / Gradboost / XGBoost / Calibration / Model Pipeline

![example result](https://github.com/WaydeHerman/Expected_Goals/blob/master/Games/Arsenal_Chelsea_2014-2015.png)
