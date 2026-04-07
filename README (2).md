
# Weather App

A simple Python-based Weather App that fetches real-time weather information for any city using the OpenWeatherMap API

Table of Contents
Main
Installation
Project Structure
Features
Running the App
Running Tests

Main

This Python script allows you to:

Input a city name
Retrieve current weather details like:
Temperature 🌡️
Humidity 💧
Weather condition ☁️🌞

It uses the requests library to fetch data from the OpenWeatherMap API and displays it in a readable format in the terminal.



## Features

Fetch current weather by city name
Display:
Temperature in Celsius
Humidity percentage
Weather condition description
Handles errors gracefully if city is not found
## Installation

1. Clone the repository
git clone https://github.com/2006risi-droid/project3.git
cd weather-app

2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

3. Install dependencies
pip install -r requirements.txt

4. Add your OpenWeatherMap API key
Replace the placeholder in the script:
api_key = "YOUR_API_KEY"
## Demo

https://github.com/user-attachments/assets/fea296e9-5ae8-4653-843b-a7c08f77c587


## Running Tests

Run the Python script:

python WA.py

Example output:
Enter city name: London
Weather in London:
Temperature: 18 °C
Humidity: 65 %
Condition: scattered clouds
Running Tests

For a simple app like this, you can manually test:

Enter valid city names (e.g., "New York", "Tokyo")
Enter invalid city names to see error handling in action

Optional: You can add automated tests using pytest by mocking API responses.



## Project Structure

weather-app/
├── weather.py          # Main Python script
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation