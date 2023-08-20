[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()
![MIT LICENSE](https://badgen.net//badge/license/MIT/green) ![MAINTAINED BADGE](https://img.shields.io/badge/Maintained%3F-yes-green.svg) 
![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/ArmandoSaboia/weather_prediction_app)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ArmandoSaboia/weather_prediction_app)
![GitHub contributors](https://img.shields.io/github/contributors/ArmandoSaboia/weather_prediction_app)

# Weather Prediction App

![Weather Prediction App](weather.jpg)

## Description

The Weather Prediction App is a user-friendly application that predicts the temperature for the next day based on historical weather data. The app integrates the PyCaret library for automated machine learning and uses the Dash framework to provide an interactive user interface. This README provides details on setting up and running the app.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the App](#running-the-app)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

1. Predicts tomorrow's temperature using historical weather data
2. Automated model selection and training using PyCaret
3. User-friendly interface built with the Dash framework

## Getting Started

### Prerequisites

1. Before you begin, ensure you have the following prerequisites:
   - Python (version 3.6 or later) installed.
   - An OpenWeatherMap API key. You can obtain one by signing up on the [OpenWeatherMap website](https://home.openweathermap.org/users/sign_up).
   - An active internet connection.

### Installation

1. Clone the repository:
   ```bash
   git clone [repository_url]
   cd Weather-Prediction-App
Weather Prediction App

Description
The Weather Prediction App is a user-friendly application that predicts the temperature for the next day based on historical weather data. The app integrates the PyCaret library for automated machine learning and uses the Dash framework to provide an interactive user interface. This README provides details on setting up and running the app.

Table of Contents
Features
Getting Started
Prerequisites
Installation
Usage
Running the App
Screenshots
Contributing
License
Features
Predicts tomorrow's temperature using historical weather data
Automated model selection and training using PyCaret
User-friendly interface built with the Dash framework
Getting Started
Prerequisites
Before you begin, ensure you have the following prerequisites:

Python (version 3.6 or later) installed.
An OpenWeatherMap API key. You can obtain one by signing up on the OpenWeatherMap website.
An active internet connection.
Installation
Clone the repository:

bash
Copy code
git clone [repository_url]
cd Weather-Prediction-App
Install the required packages using pip:

bash
Copy code
pip install -r requirements.txt
Usage
Running the App
Open the app.py file in a text editor.

Replace the following placeholders with your actual values:

[API Key]: Replace this with your OpenWeatherMap API key.
[City Name]: Replace this with the name of the city for which you want to predict the temperature.
[start_date]: Replace this with the start date for fetching historical weather data.
[end_date]: Replace this with the end date for fetching historical weather data.
Save the app.py file.

Run the Dash app using the Waitress server:

bash
Copy code
python server.py
Open your web browser and navigate to http://127.0.0.1:8050/ to access the app.

Enter your OpenWeatherMap API key and city name in the respective input fields.

Click the "Predict Tomorrow's Temperature" button to see the prediction.

Screenshots
Screenshot 1
Screenshot 2

Contributing
Contributions are welcome! Feel free to open issues and submit pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.
