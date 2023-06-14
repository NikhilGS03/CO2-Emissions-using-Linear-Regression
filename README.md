# CO2-Emissions-using-Linear-Regression
This project demonstrates the application of simple linear regression to predict carbon dioxide (CO2) emissions of vehicles based on their engine size. The dataset used in this project is the "FuelConsumption.csv" dataset, which contains information on various features of vehicles, including engine size, cylinders, fuel consumption, and CO2 emissions.

It begins with data exploration, where the dataset is summarized and specific features of interest are selected. The relationship between these features and CO2 emissions is analyzed through data visualization using scatter plots and histograms.

Next, the dataset is divided into training and testing sets for model evaluation. The training set, which constitutes 80% of the data, is used to train a linear regression model. The engine size is chosen as the independent variable (train_x), and CO2 emissions as the dependent variable (train_y). The model is fitted using the training data.

The fitted regression line is plotted over the training data to visualize the relationship between engine size and CO2 emissions. The coefficients (slope) and intercept of the regression line are displayed.

To evaluate the performance of the model, the testing set (remaining 20% of the data) is used. Mean absolute error (MAE), mean squared error (MSE), and R-squared are calculated as evaluation metrics. These metrics provide insights into the accuracy and fit of the regression model.

Finally, an exercise is presented to compare the performance of the model when using engine size and fuel consumption as independent variables. The mean absolute error is calculated for the model trained with fuel consumption as the independent variable, demonstrating that it performs differently than the model trained with engine size.
