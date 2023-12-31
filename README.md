[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()
![MIT LICENSE](https://badgen.net//badge/license/MIT/green) ![MAINTAINED BADGE](https://img.shields.io/badge/Maintained%3F-yes-green.svg) 
![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/ArmandoSaboia/weather_prediction_app)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ArmandoSaboia/weather_prediction_app)
![GitHub contributors](https://img.shields.io/github/contributors/ArmandoSaboia/weather_prediction_app)

# Weather Prediction App

![Weather Prediction App](weather.jpg)

## Description

The Weather Prediction App is a user-friendly application that predicts the temperature for the next day based on historical weather data fetched from the OpenWeatherMap API. The app integrates the PyCaret library for automated machine learning and uses the Dash framework to provide an interactive user interface.
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

1. Predicts tomorrow's temperature using historical weather data fetched from the OpenWeatherMap API
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
   git clone https://github.com/ArmandoSaboia/weather_prediction_app.git
   cd weather_prediction_app

2. Install the required packages using pip:
   ```bash 
   pip install -r requirements.txt

## Usage

### Running the App

1. Open the `weather.py` file in a text editor.

2. Replace the following placeholders with your actual values:
   - `[API Key]`: Replace this with your OpenWeatherMap API key.
   - `[City Name]`: Replace this with the name of the city for which you want to predict the temperature.
   - `[start_date]`: Replace this with the start date for fetching historical weather data.
   - `[end_date]`: Replace this with the end date for fetching historical weather data.

3. Save the `weather.py` file.

4. Run the Dash app using the Waitress server:
   ```bash
   python server.py

5. Open your web browser and navigate to http://127.0.0.1:8050/ to access the app.

6. Enter your OpenWeatherMap API key and city name in the respective input fields.

7. Click the "Predict Tomorrow's Temperature" button to see the prediction.

## Screenshots
- Screenshot 1
- Screenshot 2

## Contributing
Contributions are welcome! Feel free to open issues and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/ArmandoSaboia/weather_prediction_app/blob/main/LICENSE) file for details.
