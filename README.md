# Default-Payment
 (Data Scrubbing, EDA, Naive Bayes, Logit, CART)
Main task: Predict whether income exceeds $50k/YR based on census data. Also known as “Census 
	      Income” dataset.


Question / processes to answer within our analysis
Q1: How many observations (rows) and how many variables (columns) are there in the raw data?
Q2: Produce a table of variables showing their types.
Q3: Some of the variables appear to be numeric but should be treated as categorical. Your best clue is whether a variable has only a few discrete values. Which numeric variables should be treated as categorical?
Q4: For numeric variables, produce a table of statistics including missing values, min, max, median, mean, standard deviation, skewness and kurtosis.
Q5: How many outliers are present in each numeric variable? Show the tallies in a table. Set them to missing.
Q6: Count the unique values of each categorical variable, including missing values. Are there any unusual values in any of the categorical variables?
Q7: Impute the missing values. Be sure to explain how you did that in your presentation.
Q8: Produce a histogram or boxplot for each of the numeric variables.
Q9: Produce a bar chart for each of the categorical variables showing the counts for each unique value.
Q10: Naïve Bayes Model
Q10.1 Build a model to predict income > $50K using naïve Bayes. Randomly partition the data into a training set (70%) and a validation set (30%).
Q10.2 Score the validation data (predict) using the model. Produce a confusion table and an ROC curve for the scored validation data.
Q10.3 From the confusion table calculate the following metrics: accuracy, misclassification rate, true positive rate, false positive rate, specificity, precision, and prevalence.
Q11: Logit Model
Q11.1 Build a model to predict income > $50K using logistic regression. Randomly partition the data into a training set (70%) and a validation set (30%).
Q11.2 For which variables can we reject the null hypothesis that their coefficients equal zero?
Q11.3 Score the validation data (predict) using the model. Produce a confusion table and an ROC curve for the scored validation data.
Q11.4 From the confusion table calculate the following metrics: accuracy, misclassification rate, true positive rate, false positive rate, specificity, precision, and prevalence.
Q12: Tree Model (CART)
Q12.1 Build a model to predict income > $50K using a classification tree and a random forest with the same training and validation data used for the naïve Bayes and logistic regression models.
Q12.2 Which variables are useful for decision rules?
Q12.3 Show a plot of the tree.
Q12.4 Score the validation data (predict) using the model. Produce a confusion table and an ROC curve for the scored validation data.
Q12.5 From the confusion table calculate the following metrics: accuracy, misclassification rate, true positive rate, false positive rate, specificity, precision, and prevalence.
Q13: Compare Models
Q13.1 Compare these metrics between all three models. Which method do you prefer to use to predict income > $50K? Why?


Deliverables


The Assignment Details (Things to keep in mind)
Research Question: Can household income greater than $50k be predicted?
Why: Household with income > $50 will be the target of a marketing campaign given previous studies 
Given that Previous studies suggest this niche has a higher response rate thus profitable to the 
Bank.

age: continuous.
workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
fnlwgt: The fnlwgt indicates the number of people in the population that each record represents due to stratified sampling. To do real analysis and derive conclusions, this field must be used.: continuous.
education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
education-num: continuous.
marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
sex: Female, Male.
capital-gain: continuous.
capital-loss: continuous.
hours-per-week: continuous.
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands
