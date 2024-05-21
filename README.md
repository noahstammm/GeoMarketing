# PawsPlace Jupyter Notebook

## Overview

This Jupyter notebook is designed to help dog owners plan their walks with their pets by determining the best walking routes based on user inputs. The notebook interacts with the user to get the desired address and the maximum duration for the walk, then calculates and displays the best routes using geographical data.

## Contents

1. **Input Section**
   - Asks for the address where the walk should start.
   - Asks for the maximum duration of the walk.

2. **Processing Section**
   - Processes the user inputs to determine the optimal walking routes.
   - Utilizes mapping and geographical data to display these routes.

3. **Output Section**
   - Displays the best route for the user and their pet.
   - Includes an evaluation and summary of the results.

## Detailed Description

### Input Section
- **Address Input**
  - The user is prompted to input the desired address where they want to start the walk.
  - Example: `Adresse: hallo, Switzerland`
- **Duration Input**
  - The user is asked to input the maximum duration for the walk.
  - Example: `Wie lange sollen ihre Spaziergänge mit Ihrem Viebeiner maximal dauern`
  - The duration is input in minutes.

### Processing Section
- **Route Calculation**
  - Functions are called to process the input data and calculate the best walking routes based on the given address and duration.
- **Geographical Data Integration**
  - Integrates geographical data to display routes on a map.
  
### Output Section
- **Best Route Display**
  - Displays a map with the best walking route for the user and their pet.
- **Evaluation and Summary**
  - Provides a summary and evaluation of the calculated routes.

## Getting Started

To use this notebook:

1. Ensure you have Jupyter Notebook installed on your system.
2. Open the notebook in Jupyter.
3. Run the cells sequentially:
   - Start with the input cells to provide the necessary data.
   - Proceed with the processing cells to calculate the routes.
   - Finally, run the output cells to view the results.

## Requirements

- Python 3.9 or higher
- Jupyter Notebook
- Libraries: (Ensure these libraries are installed)
  - `geopy`
  - `folium`

## Notes

- Make sure to have an active internet connection when running the notebook to fetch and display geographical data accurately.
- Adjust the input values as needed to suit your specific requirements and location.

## Acknowledgements

Special thanks to all the contributors and the open-source community for their invaluable resources and support.
