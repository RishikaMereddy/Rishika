# Rishika
# Lead Score Case Study
# Problem Statement
XEducation sells online courses to industry professionals.It needs help in selecting the most promising leads who convert customers into paying customers. The company needs a model wherein the lead score is assigned to each of the leads such that the customers with higher lead scorehave a higher conversionchance and the customers with lower lead score have a lower conversion chance.The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.
# Data
The dataset from the past provides with around 9000 datapoints. This dataset consists of various attributes such as LeadSource, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a leasd will be converted or not.The target variable, in thiscase, is the column "Converted" which tells a lead will be converted or not wherein 1 means it was converted and 0 means it wasn't converted.
# Goals of the Case Study
To build a Logistic regression model we have to assign a lead score between 0 and 100 to eachof the leads which can be used by the company to target potential leads. A high score would most likely to convert wherew as low score would most likely not get converted. 
