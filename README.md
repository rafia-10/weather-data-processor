🌦️ Weather Data Processor

A simple, yet powerful Python pipeline to ingest, clean, transform, and prepare weather data for analysis. Built with Pandas and NumPy, this project processes real-world weather datasets to get them analysis-ready — perfect for data-driven insights and visualizations.

📌 Features
✅ CSV Ingestion: Reads raw weather data into a Pandas DataFrame

🧹 Data Cleaning:

Fills missing temperature_celsius using city-wise averages

Drops rows with missing or invalid dates

📅 Date Standardization: Converts dates to YYYY-MM-DD format

🌡️ Feature Engineering: Adds temperature_fahrenheit column

🚫 Data Filtering: Removes rows with unknown or null weather conditions

💾 Output: Saves the cleaned data to cleaned_weather_data.csv

📂 Input Data Structure
The input CSV (wather_data.csv) is expected to have the following columns:

Column	                  Type	       Description
date	                    string	       Date of weather reading
city	                    string	      Name of the city
temperature_celsius	      float	        Temperature in Celsius
humidity_percent	        float	         Humidity percentage
wind_speed_kph	          float       	Wind speed in km/h
weather_condition	        string	     Description of weather (e.g. Sunny)

🛠️ Technologies Used
🐍 Python 3

📊 Pandas

🔢 NumPy

🚀 How to Run
Clone the repo:

git clone https://github.com/rafia-10/weather-data-processor.git
cd weather-data-processor
Make sure you have dependencies installed:

pip install pandas numpy
Run the script:

python process_weather_data.py
Cleaned data will be saved as:
cleaned_weather_data.csv


👩🏽‍💻 Author
Rafia Kedir
Aspiring AI Intern @ Shega Media
🔗 GitHub • 🧠 Python | Data | AI

🌟 Why This Project?
This was built as part of a hiring assessment for Shega Media to demonstrate my ability to work with real-world data using Python. Clean data is the foundation of any good AI/ML model, and this pipeline makes sure the weather dataset is ready for the next level.

