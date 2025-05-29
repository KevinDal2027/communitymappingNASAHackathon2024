# Emission Vision

A Comprehensive Community Mapping Platform for Environmental Monitoring and Analysis

Deployed at https://algaeandco2.vercel.app/

## Project Overview

Emission Vision is an advanced community mapping platform designed to visualize and analyze environmental data, focusing on CO2 emissions and their impact on local ecosystems. The platform provides interactive tools for monitoring, analyzing, and predicting environmental trends, empowering communities to make informed decisions about environmental management and sustainability.

The platform combines multiple data sources, including satellite imagery, ground-based measurements, and community-contributed data to create a comprehensive view of environmental conditions and their evolution over time.

## Features

- Interactive Heatmaps: Visualize algae population density and CO2 emissions across Alberta using dynamic heatmaps
- Year-based Data Analysis: Analyze data trends across different years
- Dual Data Visualization: Compare algae and CO2 emissions side by side
- Real-time Map Generation: Generate maps on demand based on user selection
- OpenStreetMap Integration: Utilize OpenStreetMap tiles for base mapping

## Technologies

- Python
- Flask web framework
- Folium mapping library
- Pandas for data processing
- HTML/CSS for frontend
- JSON for data storage and transfer
- OpenStreetMap tiles

## Current Implementation

Emission Vision currently provides:
- Interactive heatmaps for both algae density and CO2 emissions
- Dynamic map generation based on user selections
- Year-specific data visualization
- Dual data visualization capabilities
- Real-time map updates

## Implementation Details

The application is built using a Flask backend with a clean, interactive frontend. It leverages Folium for mapping and pandas for data processing. The current implementation includes:

1. Data Processing:
   - Reads and processes CSV data files
   - Normalizes data values for visualization
   - Handles both algae and CO2 emission datasets

2. Mapping:
   - Uses OpenStreetMap as the base map
   - Implements interactive heatmaps for both algae and CO2 data
   - Provides zoom and pan capabilities

3. User Interface:
   - Clean, intuitive interface for data selection
   - Real-time map updates based on user input
   - Support for different visualization options

4. Data Visualization:
   - Heatmaps with normalized opacity values
   - Support for different years of data
   - Dual visualization of algae and CO2 data

Setup Instructions

1. Clone the repository:
   git clone https://github.com/yourusername/Algae-CO2-Prediction.git

2. Navigate to the project directory:
   cd Algae-CO2-Prediction

3. Install dependencies:
   Ensure you have Python 3.x installed and set up a virtual environment:
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt

4. Run the Flask application:
   flask run

5. Open the web app:
   Navigate to http://127.0.0.1:5000/ in your browser.

Future Work

- Predictive Analysis: We plan to introduce predictive models (e.g., Linear Regression, Time Series) to forecast CO2 emissions and analyze the impact of algae on carbon sequestration.
- Satellite Imagery: Incorporating NASA's Worldview satellite imagery will enhance the accuracy of algae bloom tracking.
- Scalability: Expand the scope of the project to include all provinces in Canada, not just Alberta.

Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are reviewed actively.

License

This project is licensed under the MIT License.

Acknowledgments

- Open-source data providers
- NASA Worldview for satellite data
- ChatGPT for assistance in script development
