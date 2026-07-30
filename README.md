# Data-Science-Lab1
https://www.kaggle.com/datasets/himanshunakrani/iris-dataset
Experiment Description: This experiment involves loading and performing an initial Exploratory Data Analysis (EDA) on the Iris dataset.

Key EDA Observations:

The dataset consists of 150 entries and 5 columns.
There are no missing values across any of the columns, as confirmed by df.isnull().sum().
The dataset contains four numerical features (sepal_length, sepal_width, petal_length, petal_width) all of type float64.
There is one categorical feature (species) of type object.
The df.describe() output provides statistical summaries for the numerical columns, showing their count, mean, standard deviation, min, max, and quartiles. For instance, sepal_length ranges from 4.3 to 7.9, while petal_width ranges from 0.1 to 2.5.
df.head(10) and df.tail(10) show a clear distinction in species at the beginning and end of the dataset, implying that the dataset might be sorted by species.
