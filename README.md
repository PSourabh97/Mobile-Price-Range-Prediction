# Mobile-Price-Range-Prediction
# Introduction
In the competitive mobile phone market companies want to understand sales data of
mobile phones and factors which drive the prices. The objective is to find out some
relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its
selling price.
The goal of this project is to combine the historical mobile price data to predict the
price w.r.t the specifications.

# Problem Statement
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is and also the factors affecting the price range.
## Data Description 
Battery_power ,Bluetooth ,Clock_speed executes instructions, Dual_sim ,Front Camera  mega pixels, Four_g  
Int_memory , M_dep , Mobile_wt ,Number of cores of processor, Primary Camera mega  pixels, Pixel Resolution Height, Pixel Resolution Width, Ram , Screen Height , Screen  Width , Talk_time , Three_g - Has 3G or not 
Touch_screen , Wifi , Price_range - This is the target variable with value of 0(low cost),  1(medium),cost), 
2(high cost) and 3(very high cost). 
## Steps Followed to complete the project
After reading the data I have performed Exploratory Data analysis. ∙ I have checked the Null values and Outliers present in the Dataset. ∙ I have done some statistical analysis   of the data. 

I have checked the the distribution of all the numerical columns and correlation  between the variables. 

After that I have applied different Machine Learning models( Logistic Regression,  Random Forest, KNN, SVM, XGBoost ) . 

I have hypertune the Models using GridSearchCV. 

Checked the performance of the Models by using some performance metrics(  Confusion matrix, precision, recall, AOC ROC curve). 
## Outcomes
Cost prediction is the very important factor of marketing and business. To predict  the cost same procedure can be performed for all types of products for example  Cars, Foods, Medicine, Laptops etc. 

Best marketing strategy is to find optimal product (with minimum cost and  maximum specifications). So products can be compared in terms of their  specifications, cost, manufacturing company etc. 

By specifying economic range a good product can be suggested to a costumer.



