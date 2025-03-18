# Weather Data Visualization and Analysis

This project is a Python-based application that fetches weather data from the OpenWeatherMap API, visualizes it using `matplotlib`, and stores historical search data in a MySQL database. It also provides an interactive command-line interface for users and administrators to explore weather data and generate graphs.




## Dependencies
To run this project, you'll need to install the following dependencies:  
- `requests` for API calls
- `matplotlib` for data visualization
- `mysql-connector-python` for database interactions
- `pandas` for data manipulation and analysis




## Features

1. **Weather Data Fetching**:
   - Fetches weather data (temperature, feels-like, min/max temperature, pressure, humidity, wind speed, etc.) for a given city using the OpenWeatherMap API.

2. **Data Visualization**:
   - Generates line graphs for various weather parameters (e.g., temperature, humidity, wind speed) for a single city or a comparison between two cities.
   - Includes options to visualize:
     - Temperature
     - Feels-like temperature
     - Minimum and maximum temperature
     - Pressure
     - Sea level
     - Ground level
     - Humidity
     - Wind speed

3. **Historical Data Tracking**:
   - Tracks user search history in a MySQL database.
   - Admins can view a pie chart of the most searched cities.

4. **User and Admin Interfaces**:
   - **User**: Register, log in, and explore weather data for one or two cities.
   - **Admin**: View search history and generate a pie chart of the most searched cities.





## How to Use

### Step 1 : Install Dependencies

### Step 2 : create Database 

### Step 3 : Run the Project

### Step 4 : Login or Register

### Step 5 : Enter city name(s) to fetch weather data

### Step 6 : Visualize weather data using line graphs