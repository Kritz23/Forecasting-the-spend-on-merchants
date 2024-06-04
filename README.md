We built a forecasting model for total spend on shopping/merchant category. The training features would be the date and total amount spent on shopping.
Predicting the spend amount datewise -> because if we resample the data to month, we won't have enough data samples to train. (4 years data-> 48 samples only). The predictions for each date can be summed up to get forecast for a month or a season.
