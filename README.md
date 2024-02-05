# Automated Climate Data Retrieval System

## Overview
The Automated Climate Data Retrieval System is a UiPath automation project designed to collect climate data from the web and store it in an Excel file. This system is perfect for environmental researchers, meteorologists, or anyone interested in tracking weather patterns over time.

## Features
- Automates the process of retrieving climate data such as temperature, humidity, and wind speed.
- Data extraction from search engines using UiPath's browser automation activities.
- Easy storage of extracted data into an Excel spreadsheet with predefined structure.
- Can be scheduled to run at regular intervals, providing up-to-date information.

## Prerequisites
- UiPath Studio
- Google Chrome Browser
- Microsoft Excel

## Installation
To use the Automated Climate Data Retrieval System, follow these steps:
1. Install UiPath Studio on your machine.
2. Clone this repository to a local directory.
3. Open the project in UiPath Studio.
4. Ensure that all necessary UiPath packages are installed and up-to-date.

## Usage
1. Run the workflow from UiPath Studio.
2. The automation will open Google Chrome, navigate to the search engine, and enter queries for the desired location's temperature, humidity, and wind speed.
3. The retrieved data will be written into the specified Excel spreadsheet cells.
4. The Excel spreadsheet `weather of cities.xlsx` will be updated with the latest data.

## Configuration
To customize the locations and data points:
1. Modify the 'Type Into' activities to search for different climate data or locations.
2. Update the 'Get Text' activities to extract specific data from the search results.
3. Adjust the 'Write Cell' activities to match the structure of your Excel file.

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements
- UiPath Community for their continuous support and resources.
- Data providers for their accessible weather data services.
