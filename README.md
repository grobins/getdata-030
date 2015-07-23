# getdata-030


The script cleans up data obtained from accelerometer data on a Samsung Galaxy S Smartphone.

It combines the test and training set data for the x-axis and y-axis values, and enriches this

with additional data about the subject.  The flow of the script follows:

1. Read in all data, and combine into a larger dataset
2. Identify and extract variables relating to the mean and standard deviation
3. Make the column names more readable
4. Calculate the column means
5. Output the clean dataset.