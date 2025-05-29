# Weather-ETL
A web application that processes and displays real-time weather data using a backend API and an ETL pipeline

## Technologies
- Flask (backend and routing)

- SQLite (database storage)

- WeatherAPI (fetching weather data)

- Requests (HTTP requests to API)

- HTML/CSS (frontend)

## Installation
Create a virtual environment

``python3 -m venv venv``

Install dependencies

``pip install -r requirements.txt``

Start backend API

``python3 server/api.py``

Split terminal and start web application

``python3 server/app.py``

## Usage

Open web application in a browser (http://127.0.0.1:5000)

Enter city name to view real-time weather data


## Project Structure

server/

- app.py                 
    
- api.py                 

client/

- templates/             
    
- static/                

requirements.txt        
