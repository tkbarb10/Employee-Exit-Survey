# Employee-Exit-Survey

This is employee exit survey data conducted by the Department of Education in Queensland Australia. The DETE Exit Survey was developed to effectively canvass the opinions and attitudes of departing employees to identify a wide range of operational, organizational and personal variables affecting the decision to leave.

The point of this project is to clean the dataset and perform an exploratory data analysis to answer the following questions:

**Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?**

**Are younger employees resigning due to some kind of dissatisfaction? What about older employees?**

The survey data had stopped being updated long ago so while features are self-explanatory (for the most part), some of the values we're taking our best guess on

Source: https://www.data.qld.gov.au/dataset/employee-exit-survey-dete

---

# Types of Data

The list of variables and their types are in the code, most of them are split between features that are survey questions with values that are answers given on a Likert scale, and values that are True/False.  The only numerical feature is the survey ID, the rest are categorical


---

# Further Questions

Looked into being able to predict whether or not a current employee was likely to leave based on their answers to questions that were related to satisfaction with their job.  The resulting models performed better than random guessing with an accuracy of 81-82% and a recall of True values in the 60%+ range. Recommendations are to survey employees periodically to gauge their satisfaction with their current circumstances,  and to give more attention to employees who rate higher on dissatisfaction to reduce turnover and increase engagement

---

# Limitations

- Need more data
- Imbalance in the target variable, hence why metrics for False values are much better than metrics for True values
- Different combinations of features may lead to different results
- Stronger models, like Neural Networks, that are less interpretable could be indirectly interpreted by selectively A/B testing features and comparing model performances