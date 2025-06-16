markdown
# Tides MCP Server

## Overview

The Tides MCP (Marine Control Platform) Server provides comprehensive tidal heights predictions for any location across the World Ocean. Designed to aid researchers, developers, and marine enthusiasts, the Tides server is equipped with advanced tools for tidal data analysis and prediction.

## Features

- **Global Coverage**: Access tidal height predictions at any location within the World Ocean.
- **High Accuracy**: Utilizes global tide models that integrate harmonic constants derived from over 20 years of altimeter and tide gauge data.
- **Interactive Predictions**: Generate interactive tide charts to visualize tidal data.
- **Comprehensive Parameter Support**: Customize your data retrieval with a wide range of parameters including latitude, longitude, interval, timestamp, duration, and radius.
- **Backwards Compatible**: The latest version is backwards compatible and includes new features like additional prediction models and more tidal datums.

## Tools

### Tides Tool

- **Functionality**: Retrieve tide predictions including extremes and water levels.
- **Parameters**:
  - **Latitude**: Required - Specify the latitude for the prediction, ranging from -90 to 90.
  - **Longitude**: Required - Specify the longitude for the prediction, ranging from -180 to 180.
  - **Interval**: Optional - Define the number of minutes between returned measurements (default is 60 minutes).
  - **Timestamp**: Optional - Set the prediction start time using a Unix timestamp (defaults to the current timestamp).
  - **Duration**: Optional - Indicate the number of minutes for which the forecast should be calculated (default is 1,440 minutes, equivalent to one day).
  - **Radius**: Optional - Specify the radius in kilometers to find the nearest prediction if none is found at the requested coordinates (default is 100 km).

## Usage

The Tides MCP Server is ideal for research and analysis purposes. It offers detailed tidal predictions which can be leveraged for various applications, excluding navigational purposes due to the absence of real-time weather and seismic activity data. 

For users interested in collaborating for research projects or needing a custom plan for extensive data access, the Tides team is open to discussions to tailor services to your needs.

## Disclaimer

The tidal predictions provided are based on historical tidal gauge data and satellite altimetry, and are not suitable for navigational or safety-critical applications.

## Support

For any questions, or if you require a custom plan for unlimited requests or research purposes, please contact us directly.

©2020 Tides MCP Server. Data generated using advanced tidal prediction models.