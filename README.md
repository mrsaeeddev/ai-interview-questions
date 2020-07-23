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

# DATA SCIENCE QUESTIONS

Q. If the dataset you are using is large and you face runtime issues handling it, how would you handle it?
<br />
A. Different appraoches:
- Historical Data:
    - Large Dataset: - [See this](https://www.analyticsvidhya.com/blog/2018/08/dask-big-datasets-machine_learning-python/)
                     - Load data in batches
    - Small Datasets: You are good to go with Pandas and Numpy as usual
- Realtime Data: - You need to look into big data solutions like Kafka, Hadoop etc
