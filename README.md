# Traffic Navigator

Traffic Navigator is an innovative application designed to optimize urban mobility by providing users with real-time traffic updates and route suggestions. By leveraging advanced algorithms and data from various APIs, this application helps commuters navigate through congested areas effectively.

## Inspiration

Traffic congestion is a significant issue that affects daily commuters and overall urban mobility. With increasing vehicle counts and limited road infrastructure, finding the most efficient routes is crucial. Traffic Navigator aims to provide users with optimized routes that minimize travel time and reduce congestion.

## Features

- **Real-time Traffic Updates**: Integrates real-time traffic data to suggest the best routes based on current conditions.
- **Weather Integration**: Provides weather updates that may impact travel times.
- **Map Visualization**: Displays the optimized route on an interactive map, highlighting congestion levels with color-coded paths.
- **Advanced Algorithms**: Incorporates TomTom's traffic data for current traffic conditions and congestion information. Uses OpenWeatherMap API for weather data based on location coordinates.

## Technologies Used

- **Languages**: Python
- **Framework**: Flask
- **APIs**: 
  - TomTom API for traffic data
  - OpenWeatherMap API for weather data
- **Libraries**: 
  - OSMnx and NetworkX for road network processing
  - Folium for map visualization
  - Pandas and NumPy for data handling
  - Scikit-learn for machine learning models
  - Pyngrok for exposing the local server

## How to Run the Project
1.  Set up your environment variables for API keys:
2.   Set NGROK_AUTH_TOKEN for ngrok access.
Replace the placeholder API key in the code with your actual OpenWeatherMap API key.
