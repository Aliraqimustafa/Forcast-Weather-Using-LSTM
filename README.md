# Forcast-Weather-Using-LSTM

![Weather Forecast](https://raw.githubusercontent.com/Aliraqimustafa/Forcast-Weather-Using-LSTM/main/unnamed.jpg)

Welcome to the "Forcast-Weather-Using-LSTM" repository!

I am Mustafa Muhammad, and I present to you in this repository a complete codebase that takes you from A to Z in forecasting the weather for your area.

## Web Scraping

In the file `Web-Scraping.ipynb`, you will find the code and instructions for extracting weather data from websites. I used `bs4` and `requests` for web scraping to collect data from the website [https://tcktcktck.org](https://tcktcktck.org). The scraped data is saved in CSV format.

## Data Analysis

The main data analysis can be found in the `main.ipynb` file. This section provides a comprehensive analysis of the collected weather data.

## LSTM, GRU, and Dense Model

I created a Sequential model using the Keras API with a model structure consisting of only three layers: LSTM, GRU, and Dense. The accuracy of R2 and mean square error was an impressive 96.7%.

## Weather Forecasting

On the test data, I designed the model to predict the weather for the next day based on the previous days that you specify. You can use the model in your environment by loading it with the following code:

```python
import tensorflow as tf
loaded_model = tf.keras.models.load_model('Forcast-weather-Lstm.h5')
```
The model provides weather forecasts for the previous five days and predicts the weather for the next day.

## Contact
If you have any questions or need further assistance, feel free to contact me:

## Contact

If you have any questions or need further assistance, feel free to contact me:

- **Facebook:** [Mustafa Mohammad](https://www.facebook.com/profile.php?id=100049592914479)
- **Telegram:** [Mustafa Mohammad](https://t.me/ha12qw)
