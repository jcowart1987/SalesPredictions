# SalesPredictions
Increasing Sales through a Predictive Model

Jon Cowart
Companies want to know the same thing: "How do I increase sales in order to grow my company?" With the age of machine learning and data analytics upon us, owners need not look too far to find the answers. In this data analysis of items sold by a several companies, you will see a model that can best predict the way to increase sales for any company using common metrics.

Data Source:
Sales Predictions: https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing

For this data set, there were 12 columns and 8523 rows. The column "Item Identifier" was ultimately dropped, due to the possibility that the numbered identifiers would interfere with the predictive models.

Data Dictionary
![image](https://user-images.githubusercontent.com/97577565/225773107-0cf6e115-baa5-4e90-aaeb-b2a7d2e986cb.png)


To prepare this data, the data was cleaned adn the following processes were performed:

Exploratory Data:


*   During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column.
*   Also, a barplot and heat map were created to find any useful insights into the data features and how they correlate.
* This gave good insight as to which features have more influence over sales than others.
* ![image](https://user-images.githubusercontent.com/97577565/225773306-8ed29b9a-78bd-4c00-a61b-45aa3d75dac9.png)
![image](https://user-images.githubusercontent.com/97577565/225773329-3965bf43-c6fb-49b2-9380-de669288177c.png)

Explanatory Visuals

![image](https://user-images.githubusercontent.com/97577565/225773436-8ed149fb-2859-4099-bd82-a237ef669cd4.png)

Supermarkets labeled as Type 3 sell more items than any other. Grocery stores sell the fewest amount of items. 

Dairy and Seafood are the highest sold items. 
Baking goods are the lowest sold items.

Machine Learning Using the Following Models:


*   Linear Regression
*   Decision Tree Regressor Model
* Tuned Decision Tree Regressor Model

Models Evaluated and Results
Linear Regression Model (Testing Set):
- R^2:.56
- RMSE: 1092.86

*Deciion Tree Regressor Model (Testing Set):
- R^2: .18
- RMSE: 1503.59

*Tuned Decision Tree Regressor Model (Testing Set):
- R^2: .59
- RMSE:1057.44

* The Final Model Chose was the tuned decision tree with a tuned max_depth of 5.
* For the testing set on that model, 59% of the variance in y was explained by x.
*The root mean squared error had a calculation of 1057.44.

Using this model will help companies identify the key metircs that affect sales the most in order to maximize profits.

Recommendations
* Companies should pay close attention to items that affect sales, such as item weight, visibility, and MRP. 
* The best model to predict sales is the Tuned Decision Tree Model. There was still some variance and bias, but this model slightly outperformed the linear regression model.


For Further Information
Please contact Jon Cowart at jonlcowart@gmail.com
