# Assignment
To start the process, I acquired an online sales dataset from Kaggle. Afterward, I split the dataset into two parts, making sure that the "carID" column was consistent in both parts. Then, I imported the essential Python libraries and loaded the dataset.

Next, I performed a thorough examination for any null values in the dataset and proceeded to eliminate the relevant columns using the dropna() function. Lastly, I merged the two datasets into a cohesive unit using Python's merge() function, utilizing the "on='carID'" parameter to perform the join based on the common index column.
