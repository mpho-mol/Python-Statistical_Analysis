Statistics is a branch of applied mathematics of collecting, analysing, interpreting and presenting large quantities of empirical data, more specifically to make inferences on fractions of a population that have certain characteristics from those in a representative sample. Statistics is foundational in data science as it is used to find a structure and relations between various unstructured data in order to derive actionable business insights. Both supervised and unsupervised learning techniques, namely logistic regression and clustering are statistical use cases. Numerous machine learning performance measurements are based on statistics such as precision, accuracy, recall, root mean squared error and f-score.

This project was completed in Jupyter Notebook using the StudentsPerformance.csv file which contains entries of 1000 with their details such as gender, parents' education and race/ethnicity. The aim of the task was to perform statistical analysis on the dataset to uncover underlying patterns and derive insights, thus applying knowledge on descriptive statistics, inferential statistics and hypothesis testing. The data was loaded and explored  using measures of central tendency (mean) and measures of dispersion (standard deviation). Furthermore, hypothesis testing was performed on the dataset by defining four hypotheses and validating the  using using different statistical techniques using the Pandas, NumPy, Matplotlib, Seaborn and Scipy libraries.

Hypothesis testing is a statistical method used to validate whether a hypothesis about a population or sample is true or false. The formulation of the null hypothesis is the first step and it generally states that there is no significant difference between the population parameter and a hypothesized value or between two variables or samples. Four hypotheses were tested and the significance level was set at 0.05 throughout the entire analysis.
The hypotheses are as follows:
Hypothesis 1 - There is no significant difference between a student's performance in any skills - reading, writing, or math. 
A one-way ANOVA test to validate this hypothesis.

Hypothesis 2 - There is no significant difference in the mean math scores of students who have taken test preparation and those who have not taken any test preparation.
A two sample t-test was performed to verify the hypothesis.

Hypothesis 3 - An educational consultancy claims that students receive a mean score of 70 or more on average.
A one sample t-test was conducted to confirm the hypothesis.

Hypothesis 2 - There is no relation between the gender of a student and their corresponding academic performance. 
The chi-square test of independence was performed to test the significance between these two variables.


