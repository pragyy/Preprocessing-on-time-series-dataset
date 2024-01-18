# Preprocessing-on-time-series-dataset
Various preprocessing techniques like cleaning, imputing and other such techniques are implemented.

Here, various basic pre-processing techniques essential to handle the chosen dataset are demonstrated. 
The dataset is a time-series of daily concentrations of four main air pollutants viz; NO2, SO2, SPM and RSPM.<br><br>
1. The dataset contains separate columns for representing days, months and years. 
The first task was to combine these columns and convert them into the date format for easier access.<br>
2. To enhance the readibility and to get a sense of the dataset, the time-series was briefly analyzed by grouping the data on the basis of months.<br>
3. The dataset was then scrutinised to determine any missing values that are to be further dealt with.<br>
4. These missing values were then filled in using the mean and median imputation techniques to complete the dataset.<br>
5. Finally, the completion of the imputed dataset was verified by checking for missing values, data-type, format testing and other such tests that validate the dataset's completion.
