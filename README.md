A dataset containing over 33 million NYC 311 calls was analyzed, with entries from April 6, 2011. The dataset was preprocessed, including setting 'Created Date' as the index, converting suitable columns to 'category' and numeric types to optimize memory usage.

Key insights derived include:

The dataset spans from the earliest record on April 6, 2011, to the latest record on the same date.
In 2022, the average number of daily complaints was approximately 8684.
The maximum number of calls received on a single day was 24,415 on August 4, 2020, with 'Damaged Tree' being the most common complaint.
Historically, August 2023 was identified as the quietest month.
Seasonal decomposition showed a rounded value of 183 for the seasonal component on December 25, 2020.
The autocorrelation of daily calls with a lag of 1 day was found to be approximately 0.752.
A time series model (Prophet) was used to predict daily calls, achieving a Root Mean Square Error (RMSE) of 1231.51 on the test set.
