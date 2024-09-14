Context
DeltaSquare is an NGO that works with the government on matters of social policy to bring about a change in the lives of underprivileged sections of society. They are given a task of coming up with a policy framework using a dataset that the government received from WHO.

Objective
You, as a Data Scientist at DeltaSquare, are tasked with analyzing the data provided to identify the different factors that influence the income of an individual, build a prediction model that can help the government formulate policies for the right pockets of the society, and share a proposal for the government.

Dataset
The data contains characteristics of the people

age: continuous - age of a Person
workclass: Where does a person works - categorical - (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked, Unknown)
fnlwgt: continuous - Weight assigned by Current Population Survey (CPS) - People with similar demographic characteristics should have similar weights since it is a feature aimed to allocate similar weights to people with similar demographic characteristics.
education: Degree the person has - categorical - (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
education-num: no. of years a person studied - continuous.
marital-status: categorical - (Married, Never-married, Not-married)
occupation: categorical - (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces, Unknown)
race: categorical - (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
sex: categorical - (Female, Male)
capital-gain: Investment gain of the person other than salary - continuous
capital-loss: Loss from investments - continuous
hours-per-week: No. of hours a person works - continuous.
native-contienent: categorical - (North America, Asia, Other, Europe, South America)
salary: >50K, <=50K (dependent variable, the salary is in Dollars per year)

Conclusions and recommendations

We have been able to build a predictive model that can be used by the government to find the citizens having less than 50K salary with an f1_score of 0.87 on the training set and formulate policies accordingly.

All the logistic regression models have given a generalized performance on the training and test set.

Coefficient of some levels of education, workclass, and native country are positive an increase in these will lead to increase in chances of a person having <=50K salary.

Coefficient of age, fnlwgt, marital_status, working_hours_per_week,some levels of education, workclass, and native country are negative increase in these will lead to decrease in chances of a person having <=50K salary.

The government should promote education among citizens, they should make policies to make education accessible to all, as we say in our analysis that people who have higher education are more likely to have a salary above 50,000 Dollars.
Working hours is one of the significant predictors of salary, The government should implement laws to ensure that people are paid fairly for their work and are not overworked for the increase in salaries. This would improve work-life balance.
Reforms should be made for private-sector employees so that they are paid fairly for their work.
Policy formulated by the government should be considerate of equal pay and counter the pay gap that exists in society.
