The code is available in jupyter notebook (python 3.7) format.
It is also possible to open it via google colab (from google drive) if it is more comfortable for the checker.

In order to recreate the results you can choose the dataset type in the config and to descide whether or not it should be saved to a file.
The submission file ("ATT_results1.csv") was created by hand by merging outputs of this script ("ATT_results1.csv" & "ATT_results2.csv").

For the first 3 methods I used Random Forest, so I did not standatarize the data.
for the last model I used KNN, it could have been better to scale the covariates and maybe even do dimensionallity reduction for that purpose. But I decided to leave it as it is.

As my final prediction, I submit the mean of the first 3 methods.