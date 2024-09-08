README


About the Project

This project is a simple implementation of the gradient descent algorithm for linear regression. It attempts to predict the price of a car in 1985 given 8 features. These are Length, Width, CurbWeight, NumOfCylinders, EngineSize, Horsepower, CityMpg, and HighwayMpg. Since some variables from the original dataset (found on https://archive.ics.uci.edu/dataset/10/automobile) were not as commonly known or linearly correlated to the price, they were removed from this set. The modified dataset (found on https://raw.githubusercontent.com/sanspandey45/ml-dataset/main/carsdata.csv) contains 8 features that were deemed the most important and strongly correlating with Price. As the current mileage is not a feature, we are to assume the cars are new or in similar conditions in terms of mileage. Some uses for this could be to figure out an appropriate car budget based on certain desired constraints, or to determine if a vehicle is being priced relatively fairly at a dealership.




Libraries used:
numpy
pandas
scikit-learn
matplotlib (and seaborn)




How to build and run:
Runs best using the Google Collab Link at the top of the python file, but by installing the necessary packages and libraries mentioned above before compiling and running.
