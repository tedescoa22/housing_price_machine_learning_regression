# Project 2 - Ames Housing Data and Kaggle Challenge




# Problem Statement:



Everyone who sells their house wants to get the best price possible for it. The problem is determining what your house is already worth and
what can be done to improve it. This project aims to use machine learning models to predict housing prices and determine what the most
important features are that correlate to sale price and if there are viable ways to implement changes to these features to improve housing
price. This project will use data from the Ames data set, which contains over 80 features about houses from Ames, Iowa. The data is split into
a training set, which includes sale price and  testing set which will be used to test the model against new, unseen data.





# Hypothesis:
Based on my own experiences in the real estate industry (working on and off with my father, who own his own real estate company, for 9 years) I predict that improvements made to the overall quality and condition of the house will raise its price. In other words, how well a house maintained determines housing price.


# Data Sets:

The data sets used in this project is the Ames Iowa housing data set, which has been split into two, with a training data set and a testing data to be used for a Kaggle coding challenge.



# Models:

For this project I used several machine learning packages from sklearn, such as pipeline, gridsearch, knn, linear regression, ridge and lasso.

Of these packages, the linear regression and ridge preformed the best with a R2 cross val score of 0.909 and a training R2 score of 0.908 for the linear regression and a R2 cross val score of 0.909 and train R2 score of 0.907 for the ridge. Their rmse's were a cross val predict of 20528.44 and a rmse score of 18504.23 on the testing for the linear regression and a cross val predict rmse of 19873.36 and a testing rmse of 18395.19 for the ridge. Even though the linear regression had a lower variance, I decided to use the ridge as my final model to use for Kaggle as it had the lower rmse, which is the goal of the competition.


# Analysis:


- High correlation between overall quality and housing prices as well as high correlation between overall quality transformed with the quality of sections of the house and housing prices

- Other features with good correlations with housing price all have to do with the square footage or size of the house and its amenities and their condition

- Hypothesis proven correct; as the quality of a home increase, so does its sale price.

- Above all else improving the quality of a house will improve, it's sale price and is the easiest way for a home owner to raise their property value

- model had a much better rmse than the baseline which had an rmse of 79239.33



# Conclusion:

 The hypothesis was proven correct and the model was able to predict the price of houses better than the baseline model was. This means that increasing the quality of one's home will lead to an increase in the sale price of that home. The model well outperformed the baseline with an rmse 1/4 of the baseline model. 



# Recommendations:

Based on the model, and my own personal experiences I suggest that home owners looking to sell should do simple and cheap but efficient home renovations and improvements to increase their home's sale value. These include; Exterior: landscaping, reseeding the grass, trimming hedges and tree's, adding or replacing flowers and other decorative plants, repaving the driveway, repainting the outside of the house, repairing any damages, Interior: repainting the walls, polishing the floors, steam cleaning the carpets, replacing old appliances and cleaning newer ones, replacing old/broken windows or cleaning them, making sure everything works and is hooked up properly, and cleaning all furniture and countertops. All of these things are cheap to do (especially if you do them yourself) and are easier and faster than expanding the house or a feature of the house, which would also increase its sale value.
