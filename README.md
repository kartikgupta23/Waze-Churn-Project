# Waze-Churn-Project
The **purpose** of this model is to find factors that drive user churn.  
The **goal** of this model is to predict whether or not a Waze user is retained or churned.

**This activity has three parts:**

**Part 1:** Ethical considerations
* Consider the ethical implications of the request

* Should the objective of the model be adjusted?

**Part 2:** Feature engineering

 * Perform feature selection, extraction, and transformation to prepare the data for modeling

**Part 3:** Modeling

 * Build the models, evaluate them, and advise on next steps

In this stage, consider the following questions:

1.   What are you being asked to do?
> _Predict if a customer will churn or be retained._

2.   What are the ethical implications of the model? What are the consequences of your model making errors?
  *   What is the likely effect of the model when it predicts a false negative (i.e., when the model says a Waze user won't churn, but they actually will)?
  > _Waze will fail to take proactive measures to retain users who are likely to stop using the app. For example, Waze might proactively push an app notification to users, or send a survey to better understand user dissatisfaction._
  *   What is the likely effect of the model when it predicts a false positive (i.e., when the model says a Waze user will churn, but they actually won't)?
  > _Waze may take proactive measures to retain users who are NOT likely to churn. This may lead to an annoying or negative experience for loyal users of the app._
3.   Do the benefits of such a model outweigh the potential problems?
  > _The proactive measueres taken by Waze might have unintended effects on users, and these effects might encourage user churn. Follow-up analysis on the effectiveness of the measures is recommended. If the measures are reasonable and effective, then the benefits will most likely outweigh the problems._
4.   Would you proceed with the request to build this model? Why or why not?

  >_Yes. There aren't any significant risks for building such a model._
