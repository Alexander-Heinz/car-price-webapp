# Car Price Prediction Web App

> **⚠️ NOTE:**  
> The web service / web app is currently **offline**.  
> I had to **pause the cloud hosting (previously on DigitalOcean)** due to ongoing costs.  
> I'm actively **looking for a free or lower-cost alternative** to resume hosting in the near future.

This web app allows users to predict the price of a car based on various input details. The app uses an advanced machine learning model trained on a large dataset from AutoScout24. The model takes into account key features of the car, such as brand, model, mileage, year, transmission type, and power, to estimate the car's market price.

The web app was developed as a final project for the MLOps Zoomcamp.


**It uses the model developed during the course as a MLOps pipeline:**
> 👉 [autoscout-price-prediction (MLOps Pipeline) on GitHub](https://github.com/Alexander-Heinz/autoscout-price-prediction)  


## Features

- **Car Model:** Choose the car model.
- **Mileage:** Enter the mileage of the car (in kilometers).
- **Year:** Select the manufacturing year of the car.
- **Brand:** Specify the car brand.
- **Transmission Type:** Choose between manual or automatic transmission.
- **Power:** Provide the car's engine power in horsepower.

## How to Use

1. **Go to the web app:** Access the app via the following link:  
   [Car Price Prediction Web App](http://164.90.187.32/)

2. **Enter the car details:** Fill in the form with the car's information, including the brand, model, mileage, year, transmission type, and power.

3. **Get the price prediction:** After entering the details, the app will display an estimated price for the car.

## How it Works

The app uses a machine learning model trained on a large dataset from AutoScout24. The model employs advanced ML to predict the market value of a car based on input features. It leverages historical data to identify patterns and estimate prices accordingly.

## Technologies Used

- **Frontend:** React.js
- **Backend:** Python (Flask or FastAPI)
- **Model:** Pre-trained car price prediction model based on tree-based machine learning methods
- **Hosting:** DigitalOcean cloud hosting
- **Dataset:** Large AutoScout24 dataset

## Access the App

You can access the Car Price Prediction Web App here:  
[Car Price Prediction Web App](http://164.90.187.32/)

## Disclaimer

This app provides an estimated car price based on the information provided. Prices may vary depending on factors not included in the model, such as location, car condition, or market demand.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
