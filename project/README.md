# Project Description

### Primary Tools
1. R studio
2. Python (Jupyter Notebook)

### What it does 

Our goal is:
1) to help app stores to better advertise their apps through four steps of app download: when, why, how, what. Based on the data given, we discover some patterns of user habits and give app developers and providers useful suggestions accordingly. For example, we find out that games, social networking, utilities, weather, music are generally the top five types of apps that people will download. We then recommend app stores to push apps to their customers based on this pattern. 
2) to help the app store better advertise the store itself and its corresponding mobile phone brand. We build construct two models, SVM linear model and 4 layers neural network nonlinear model, to predict what mobile phone brand people are using based on their demographic information.  As a result, Apple, Blackberry, Andriod, Nokia, and Samsung happen to be the top five phone brands that people prefer the most. These two models can help app stores to better target their customers based on individuals’ demographic information, and so can advertise their phones with higher efficiency. 

### How we built it
We first use Python to read the data and do some data cleaning to choose the variables we are particularly interested in. Then we export the dataset to R studio to do some exploratory data analysis. Using R, we then plot the data to analyze users' habits for each of the five App stores (see code in CDC_EDA.Rmd). Based on the pattern from users' feedback, we come out with some suggestions for App stores and providers to better serve their current customers. Besides, given the large amount of data, we also use python to do the modeling, which predicts user's preference of phone brands based on their Gender, Age, Marital status, Occupation, income, etc (see code in CDC_Model.ipynb). In this way, we are able to further identify potential customers for different kinds of mobile applications. Thus, the app stores may use our model to better recommend products to their users according to their profile.
