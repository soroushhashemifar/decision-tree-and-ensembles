# Decision tree and Ensembles

This project is created to compare performance of decision tree and different ensemble methods implemeneted in scikit-learn. So far, I have implemented the following methods in this project:
- Decision tree
- Random Forest
- Extra trees
- Voting Classifier
- Bagging Classifier
- AdaBoost
- Gradient Boosting

These experiments are done on occupancy dataset. 

## Dataset

Three data sets are submitted, for training and testing. Ground-truth occupancy was obtained from time stamped pictures that were taken every minute.

Attribute Information:

- date time year-month-day hour:minute:second
- Temperature, in Celsius
- Relative Humidity, %
- Light, in Lux
- CO2, in ppm
- Humidity Ratio, Derived quantity from temperature and relative humidity, in kgwater-vapor/kg-air
- Occupancy, 0 or 1, 0 for not occupied, 1 for occupied status

Dataset available at: https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+
