# London Weather Prediction

## Project Description

This project aims to predict the mean temperature in London, England, using various regression models. As the climate changes, predicting the weather becomes ever more important for businesses. This project uses a combination of sklearn and MLflow to run experiments and determine the best approach for weather prediction.

## Dataset

The dataset used in this project is stored in `london_weather.csv`, which contains the following columns:

- `date`: Recorded date of measurement (int)
- `cloud_cover`: Cloud cover measurement in oktas (float)
- `sunshine`: Sunshine measurement in hours (hrs) (float)
- `global_radiation`: Irradiance measurement in Watt per square meter (W/m2) (float)
- `max_temp`: Maximum temperature recorded in degrees Celsius (°C) (float)
- `mean_temp`: Target mean temperature in degrees Celsius (°C) (float)
- `min_temp`: Minimum temperature recorded in degrees Celsius (°C) (float)
- `precipitation`: Precipitation measurement in millimeters (mm) (float)
- `pressure`: Pressure measurement in Pascals (Pa) (float)
- `snow_depth`: Snow depth measurement in centimeters (cm) (float)

## Models

This project uses various regression models to predict the mean temperature. Here are the models used and their roles:

1. **Linear Regression (sklearn.linear_model.LinearRegression)**: This is a simple linear approach to modelling the relationship between a dependent variable and one or more independent variables. In this project, it's used as a baseline model to predict the mean temperature.

2. **Decision Tree Regressor (sklearn.tree.DecisionTreeRegressor)**: This model uses a decision tree to go from observations about an item to conclusions about the item's target value. It's a more complex model that can capture non-linear relationships between features and the target variable.

3. **Random Forest Regressor (sklearn.ensemble.RandomForestRegressor)**: This is a meta estimator that fits a number of classifying decision trees on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. It's used in this project to potentially improve the prediction accuracy by combining the predictions of multiple decision trees.

Each model is trained and evaluated using the same training and test data. The performance of each model is logged using MLflow, which allows for easy comparison of the models.

## Dependencies

- pandas
- numpy
- mlflow
- sklearn
- matplotlib
- seaborn

## Usage

### Google Colab

To use the `Code_Alpha_MRS.ipynb` file with Google Colab, follow these steps:

1. Open Google Colab.
2. Click on `File > Open notebook`.
3. Select the `GitHub` tab.
4. Enter the URL of your GitHub repository and press Enter.
5. Click on the `Code_Alpha_MRS.ipynb` file to open it.
6. You can now run and modify the notebook in Google Colab.

### Jupyter Notebook

To use the `Code_Alpha_MRS.ipynb` file with Jupyter Notebook, follow these steps:

1. Clone your GitHub repository to your local machine using Git.
2. Navigate to the directory containing the `Code_Alpha_MRS.ipynb` file in a terminal.
3. Run the command `jupyter notebook`. This will open a new tab in your web browser with Jupyter Notebook.
4. Click on the `Code_Alpha_MRS.ipynb` file to open it.
5. You can now run and modify the notebook in Jupyter Notebook.
   
Once your notebook is open in Google Colab or Jupyter Notebook, you can run the cells using the play button, or Shift+Enter on your keyboard. Remember to install any necessary libraries using !pip install library-name for Google Colab, or !pip install library-name directly in a cell for Jupyter Notebook. 😊

## Results
The results of the experiments are logged using MLflow. You can view the results by running the MLflow UI:

mlflow ui

## Contributing
Contributions are welcome! Please read the contributing guidelines first.
