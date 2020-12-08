# SML 310 Final Project: Modeling hurricane track development under climate change

North Atlantic hurricanes pose a substantial risk to people’s safety and wellbeing in the United States. As a result, it is important to investigate how storms will behave in the future and in particular how and why their movement will be affected by climate change. I investigate how hurricane steering flow is changing and how data science models can be used to understand these changes. 

My two questions are: 
1.	 How well can a simple statistical or empirical model predict hurricane movement from one time period to the next? 
2.	How has the way that hurricanes move been changing over time due to climate change? 

I used both a multiple regression model and a neural network model to predict hurricane track movement based on latitude, longitude, wind speed, and sea level pressure 6 hours before and 12 hours before, as well as the global mean temperature anomaly for that year. 

I produce predicted storm tracks and assess the accuracy of the model predictions 6 to 54 hours into the future. 

My results confirm that a simple multiple regression model can yield reasonable hurricane track predictions up to 6 to 12 hours into the future. Up to 18 hours in the future, the predictions are on average within 200km of the true storm locations. This model has the benefit of simplicity and explainability- it only requires knowledge of wind speed, SLP, latitude, and longitude for two consecutive points to build a prediction into the future. While global mean temperature anomaly (representing climate change from 1971 to 2019) did significantly affect wind speed and SLP in the regression model, with more intense storms associated with higher temperatures, it did not have a significant impact on the steering flow of the storms or the predictive accuracy of the model. This may indicate that the effect of climate change on steering flow is very small or that it is not captured in this model. The neural network model did produce predictions, but it requires further refinement before it will be an effective model. 


The data file for storm tracks was too large to upload here. 
Please find the file 'data.nc' at this google drive link: 
https://drive.google.com/drive/folders/1vRnlKlT18pZwSpG05X1k9G1r3EjS1EO7?usp=sharing





