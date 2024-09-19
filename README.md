# **CORTEVA Weather API**


## **Overview**
The CORTEVA Weather API is a part of the coding challange, that provides endpoints for ingesting, retrieving, and processing weather data. This application is built with Flask and Flask-RESTx, allowing interaction with weather data stored in a MySQL database. It includes functionalities for data ingestion, fetching weather data, and generating weather statistics. However this application is not hosted at the moment, 


## **Features**
   -  **Weather Data Ingestion:** Inserts data from the weather data file into MySQL database
   -  **Weather Data Rerieval:** Fetches weather data from database based on user filters(whereever applicable)
   -  **Weather Data Statistics:** Generates few insights on the weather data, also can be filtered


## **Installation**

### **Prerequisites**
   -  Python 3.9 or higher
   -  Git
   -  Flask
   -  Flask-RestX
   -  MySQL Database or any SQL Database (some queries wll change accordingly)
   -  Python packages specified in requirements.txt

### **Setup**
   1. Clone the repository

      ```bash
      git clone https://github.com/subratapanda17/corteva_weather_apis.git
      cd corteva_weather_apis```

   2. Create a virtual environment
      - using python virtualenv
         ```bash
         python -m venv corteva_weather_venv
         source corteva_weather_venv/bin/activate```

      - using conda
         ```bash
         conda create -n "corteva_weather_env"
         conda activate corteva-env```
      
