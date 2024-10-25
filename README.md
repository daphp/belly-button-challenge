# Belly Button Biodiversity Dashboard

This project is an interactive data visualization dashboard for exploring belly button biodiversity, created using D3.js and Plotly.js. The dashboard allows users to examine bacterial cultures from different individuals, analyze the top 10 bacterial species found, and visualize data using bar and bubble charts.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The Belly Button Biodiversity Dashboard provides insights into the types of bacteria found in the belly buttons of various volunteers. The data originates from a study aiming to understand human microbial diversity and is presented in an accessible, visually engaging manner. Users can explore data for each test subject, view demographic information, and analyze bacterial samples through dynamic, interactive charts.

## Features

- **Demographic Information Panel**: Displays key demographic data for the selected individual.
- **Interactive Bar Chart**: Shows the top 10 bacterial species (OTUs) found in the selected sample, with bacterial counts on the x-axis.
- **Bubble Chart**: Displays bacterial data across all OTU types for each individual, with marker size representing bacterial counts.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/belly-button-challenge.git
	```
2. Navigate to the project direcctory:
	```bash
	cd belly-button-challenge
	```
3. Open index.html in your web browser to view the dashboard.

	Alternatively, view the dashboard directly online:
	Live Dashboard Link: https://daphp.github.io/belly-button-challenge/
	Note: The project loads data directly from an external JSON URL, so internet access is required to view the dashboard's content.

## Usage

1. Open the dashboard either by:
	Opening index.html in any web browser, or
	Navigating to the live dashboard https://daphp.github.io/belly-button-challenge/.
2. Use the dropdown menu at the top left to select a test subject ID.
3. The demographic information will update based on the selected individual.
4. The bar chart will display the top 10 bacterial species found in that sample.
5. The bubble chart visualizes the entire bacterial profile of the selected subject, with bacteria counts shown on the y-axis and OTU IDs on the x-axis.

## Files

- **index.html**: Main HTML file containing the structure of the dashboard.
- **/static/js/app.js**: JavaScript file responsible for fetching data, building charts, and handling interactivity.
- **README.md**: Project documentation.

## Technologies Used

- **JavaScript**: Core programming language used for logic and interactivity.
- **D3.js**: Used for data handling and selecting HTML elements.
- **Plotly.js**: Used to create responsive, interactive charts.
- **Bootstrap**: For styling and responsive layout.

## Contributing
Contributions are welcome! To contribute:

- **Fork the repository.**
- **Create a feature branch (git checkout -b feature/AmazingFeature).**
- **Commit your changes (git commit -m 'Add some AmazingFeature').**
- **Push to the branch (git push origin feature/AmazingFeature).**
- **Open a pull request.**

## License
This project is open-source and available under the MIT License.

