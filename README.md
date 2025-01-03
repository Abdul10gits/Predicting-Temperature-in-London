As the climate changes, predicting the weather becomes ever more important for businesses. You have been asked to support on a machine learning project with the aim of building a pipeline to predict the climate in London, England. Specifically, the model should predict mean temperature in degrees Celsius (°C).

Since the weather depends on a lot of different factors, you will want to run a lot of experiments to determine what the best approach is to predict the weather. In this project, you will run experiments for different regression models predicting the mean temperature, using a combination of sklearn and mlflow.

You will be working with data stored in london_weather.csv, which contains the following columns:

date - recorded date of measurement - (int)

cloud_cover - cloud cover measurement in oktas - (float)

sunshine - sunshine measurement in hours (hrs) - (float)

global_radiation - irradiance measurement in Watt per square meter (W/m2) - (float)

max_temp - maximum temperature recorded in degrees Celsius (°C) - (float)

mean_temp - target mean temperature in degrees Celsius (°C) - (float)

min_temp - minimum temperature recorded in degrees Celsius (°C) - (float)

precipitation - precipitation measurement in millimeters (mm) - (float)

pressure - pressure measurement in Pascals (Pa) - (float)
snow_depth - snow depth measurement in centimeters (cm) - (float)
