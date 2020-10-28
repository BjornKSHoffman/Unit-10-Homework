# Unit-10-Homework - three files; part 1, part 2 and readme
### Based on the p-values, is the model a good fit (p < 0.05)?

Our ARIMA-model p value of .36 was a much better fit for the data than the ARMA model, which had a p value of .42; although both models could be applied for forccasting the data in fact, the models both look very similar in that the 5 forecasted days of percent change in the Yen start at around .01 percent change and lower down to the roughly 0 percent change by the end of the window period.
Their average AIC values suggest that these models may fit nicely but the AIC does not reveal which is superior as the numbers are nearly identical, falling in at 15798 for ARMA and 15807 for ARIMA.
### Based on your time series analysis, would you buy the yen now?
I would tell my traders that they may have some upside on the yen over the next two or three days but that there is a risk of negative returns after days four and five as predicted by the ARIMA model. Yes, I would buy the yen for a short period of time, then return to the benchmark currency.
### Is the risk of the yen expected to increase or decrease?
It looks to be expected to decrease given the high risk of the next two days surpasses the risk of the further three.
 
### Based on the model evaluation, would you feel confident in using these models for trading?
 I would not feel confident using these models because the p-values are still relatively high. Additionally, it makes some degree of sense that the percent change would rise and fall in fluctuation as predicted, but the timing of it is not at all guarenteed and the models simply estimate to a low enough degree of accuracy that I would'nt trust them.
 
## Linear Regression
 Out-of-Sample Root Mean Squared Error (RMSE) is equal to: 0.41545437184712763
 In-sample Root Mean Squared Error (RMSE) is equal to: 0.5962037920929946
a lower RMSD is better than a higher one and neither RMSE in this case looks very promising. This can be substantiated when looking at the graph comparing the test period and the predicted results. The datapoints appear to be nearly opposite of one another on the graph. Although the total gain on the period does look to be accurate, this is simply due to the graph strattling 0 as it is a percent change graph. This model has little to no predictive value. I would suggest looking elsewhere for our Yen predictions.
