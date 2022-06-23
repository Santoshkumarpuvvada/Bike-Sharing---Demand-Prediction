# Bike-Sharing---Demand-Prediction:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1) Which variables are significant in predicting the demand for shared bikes.
2) How well those variables describe the bike demands

# Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

# Methodology:
First EDA was performed to understand the data & then Linear Regression was chosen for the analysis. Regression was chosen because the major business objective was to understand the factors influencing the demand rather than just demand prediction. Linear Regression has the best interpretability & hence it can deliver the required results

# Results & Recommendations:
Adjusted R2 of the final model developed was 81.1% & 79.3% on the test & train data. This is pretty much in an aceptable range in real time situatuations. All the assumptions of Linear Regression were also checked & found to be satisfied. 

Inferences: Features impacting the bike demand are found to be 
1) Clear, Few clouds, Partly cloudy, Partly cloudy days are best for bikes demand. Mist is bad & Light snow is worse & Heavy snow means zero bikes demand.
2) Year 2 has much higher demand than year 1. Looks like there is positive trend in terms of business growth(however 2 years is too small for commenting on trend)
3) Spring season is very bad compared to fall season for bikes demand
4) Higher Temperature is btr for are found to be  good bikes demand
5) Features like holidays impact demand negatively
