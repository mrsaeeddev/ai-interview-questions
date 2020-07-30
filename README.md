<h1 align="center">
    <a href="https://github.com/mrsaeeddev/ai-interview-questions">
        <img src="https://raw.githubusercontent.com/mrsaeeddev/ai-interview-questions/master/logo.png">
    </a>
    <br/>
    <br/>
  AI INTERVIEW QUESTIONS
  
![GitHub last commit](https://img.shields.io/github/last-commit/mrsaeeddev/ai-interview-questions)
![GitHub contributors](https://img.shields.io/github/contributors/mrsaeeddev/ai-interview-questions)
![Twitter Follow](https://img.shields.io/twitter/follow/mrsaeeddev?label=Follow&style=social)
  > Real-World AI Interview Questions for You
</h1>
<br/>
<br/>

# GENERAL Requirements for AI related roles:

## DATA ENGINEERS:

Requirements:
- Programming Experience in a language like Python, Go etc.
- Solid Knowledge of Operating Systems
- Understanding of ETL pipelines
- Heavy, In-Depth Database Knowledge – SQL and NoSQL
- Data Warehousing – Hadoop, MapReduce, HIVE, PIG, Apache Spark, Kafka
- Basic Machine Learning Familiarity

## DATA SCIENTISTS:

Requirements:
- Programming Experience in a language like Python, R etc.
- Statistics (familiarity with statistical tests, distributions, maximum likelihood estimators, etc.)
- Basic Machine Learning Skills
- Multivariable Calculus & Linear Algebra
- In-Depth knowledge of SQL
- Data Wrangling and EDA Skills
- Data Visualization and Communication

## MACHINE LEARNING ENGINEERS:

Requirements:
- Programming Experience in a language like Python, R, Java etc.
- Advanced Probability and Statistics Knowledge
- Data Modeling & Evaluation
- Advanced Machine Learning
- Software Engineering and System Design

# DATA SCIENCE QUESTIONS

Q. How to find outliers in data?
<br />
A. i. If you know the outlier values, then you may set some threshold value for the outliers. So, by filtering the data that lies inside that values you can get filtered data.
<br />
ii. If you don't know the outlier values in advance, you can apply clustering to find out the clusters and drop the data that lies outside that. Same goes for other models like Linear Regression or SVM. 
<br />
iii. Scatter plots and Box plots are used to find visualize outliers so you can use them for visualization part.

Q. If the dataset you are using is large and you face runtime issues handling it, how would you handle it?
<br />
A. Different appraoches:
<br />
- Historical Data:
    - Large Dataset: - [See this](https://www.analyticsvidhya.com/blog/2018/08/dask-big-datasets-machine_learning-python/)
                     - Load data in batches
    - Small Datasets: You are good to go with Pandas and Numpy as usual
- Realtime Data: - You need to look into big data solutions like Kafka, Hadoop etc

Q. Why CatBoost and XGBoost is better than gradient boosting in sklearn?
<br />
A. 

Q. How Gradient Boosting works?
<br />
A. [See here](https://www.displayr.com/gradient-boosting-the-coolest-kid-on-the-machine-learning-block/)

Q. How Hyperparameters in an algorithm work?
<br />
A. [See here](https://towardsdatascience.com/understanding-hyperparameters-and-its-optimisation-techniques-f0debba07568)
