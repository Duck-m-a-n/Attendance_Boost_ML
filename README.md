# Attendance_Boost_ML
 
## Problem Overview:

GoalZone is a fitness club chain providing five types of fitness classes in Canada. Finally, the fitness classes schedule is back to normal after the COVID-19 restrictions are lifted. However, they have received many complaints from the customers about having a hard time booking a fitness class.

From initial analysis, the program operation team found out that the fitness classes are always fully booked but are having a low attendance rate per class. To improve this situation, they would like to increase the class capacity for customers to sign up if a low attendance rate is predicted.

## Problem Statement:

The operation manager has asked the team to answer the following questions: 
- Can the team predict the attendance rate for each fitness class? 
- How can the team use the predicted results to optimize the class capacity?

## Approach: 
The team will use machine learning to predict the attendance rate for each fitness class. 
The machine learning model will be trained on historical data to accurately predict the attendance rate. 
The team will then use the predicted results to optimize the class capacity. The team will set the capacity for each fitness class based on the predicted attendance

## Results:

I used Linear and Ridge regression to predict gym attendace rate. 
Ridge regression performed slightly better using `RMSE` to compare the models.
Ridge regression had an `R^2` value of 60.578% so the model is a good fit to the data and can accurately predict future attendance rate.
The business outcome means that Goalzone will be able to change the capacity of specific classes to best optimize member attendace. 


$$r_{1}^2$$
