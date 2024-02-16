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

## Dependencies

- pandas
- numpy
- mlflow
- sklearn
- matplotlib
- seaborn

## Usage

To run the project, you need to have Python installed on your machine. You can then install the dependencies listed above using pip:

```bash
pip install pandas numpy mlflow sklearn matplotlib seaborn

## Run
Google Colab:

Go to Google Colab.
Click on Upload if you have the notebook file on your local machine, or GitHub if your notebook is in a GitHub repository.
Navigate to your notebook file and click Open.
Jupyter Notebook:

Open a terminal.
Navigate to the directory containing your notebook file using the cd command.
Run jupyter notebook. This will start the Jupyter Notebook server and open your default web browser.
In the browser, navigate to your notebook file and click to open it.
Once your notebook is open in Google Colab or Jupyter Notebook, you can run the cells using the play button, or Shift+Enter on your keyboard. Remember to install any necessary libraries using !pip install library-name for Google Colab, or !pip install library-name directly in a cell for Jupyter Notebook. 😊

## Results
The results of the experiments are logged using MLflow. You can view the results by running the MLflow UI:

mlflow ui

## Contributing
Contributions are welcome! Please read the contributing guidelines first.
