# College-Placements-Analysis-and-Prediction
# Introduction

Almost each and every student has to go through placement process during the final year of their respective university courses. But what factors really affect the placement of a student? Is it their college degree percentage? School percentage? Performance in the entrance test of company? We will be studying about all these factors in the given notebook. Not only this, we will also be developing a predictive model to classify if a given student can get a placement or not.

# Data Sources
I have downloaded the dataset from [Kaggle](https://kaggle.com)
# Purpose
I will be analysing the factors that can affect the placement of an MBA student. Also, I will be creating a machine learning classifier model which will be able to predict if a given student can get a placement or not.

# NOTE
Size of dataset is very small(around 200-300 values). Performance will vary on increasing the size of dataset.

### Packages used
**sklearn, numpy, pandas, matplotlib, seaborn**
# Exploratory Data Analysis
Performed some analysis to better undertsand the data.

<img src="https://github.com/Vaibhavnaudiyal92/College-Placements-Analysis-and-Prediction/blob/master/download%20(9).png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
<img src="https://github.com/Vaibhavnaudiyal92/College-Placements-Analysis-and-Prediction/blob/master/download%20(8).png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

<img src="https://github.com/Vaibhavnaudiyal92/College-Placements-Analysis-and-Prediction/blob/master/c1%20.png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
     
<img src="https://github.com/Vaibhavnaudiyal92/College-Placements-Analysis-and-Prediction/blob/master/c2%20.png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />   
<img src="https://github.com/Vaibhavnaudiyal92/College-Placements-Analysis-and-Prediction/blob/master/c3%20.png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

# Conclusion
Decision Trees are performing better with an accuracy of 82% in comparison to Naive Baye's which has an accuracy of 72%. We can further improve the accuracy by using ensembling techniques like Random Forest and Gradient Boosted Trees. Salary feature was removed because it was a dependent feature.
