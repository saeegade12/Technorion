# Technorion

# Weather Alert System

## Overview

This Python script utilises the `uagents` library to create a simple weather alert system. The script periodically checks the current temperature in a specified city using the WeatherAPI and sends alerts when the temperature goes outside the specified range.

## Features

- Retrieves real-time weather data using the WeatherAPI.
- Sends temperature alerts when the temperature exceeds the specified range.
- Uses the `uagents` library for agent-based programming.

## Setup

1. Install the required libraries:
	pip install uagents

2. Run the script:

python main.py

3. Follow the prompts to enter the city and temperature range.

## Configuration

- `city`: Enter the name of the city for which you want to receive weather alerts.
- `min_temp`, `max_temp`: Set the minimum and maximum temperature thresholds for alerts.

## Usage

- The script will run continuously, checking the temperature every 10 seconds.
- If the temperature goes outside the specified range, an alert message will be sent using `uagents`.
- View the alerts in the console or logs.

## Known Issues

- Due to limitations with `uagents`, the final completion message is printed using `print` outside the agent context.




