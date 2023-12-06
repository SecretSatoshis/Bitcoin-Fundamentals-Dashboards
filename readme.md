# Bitcoin Chart Library

Welcome to the repository of Bitcoin Chart Library, an automated chart generator that visualizes Bitcoin data. The application is built using Python, with Plotly and Dash serving as the core for the web interface.

## Project Overview

This project provides an automated system for generating comprehensive charts. It leverages Plotly, a Python graphing library, to create interactive charts, and Dash, a productive Python framework for building web applications.

The chart generator is composed of several Python files:

- `data_format.py`: Fetches and processes data from CoinMetrics.
- `chart_format.py`: Defines the structure and style of the charts.
- `dash_app.py`: Defines the Dash application and its layout.
- `main.py`: The main application where the final charts are generated and displayed.

## How to Run the Application in Replit

To run this application in Replit, follow these steps:

1. Clone the repository in Replit.
2. Set your environment variable `RUN_SERVER` to true.
3. Click on the "Run" button at the top of the Replit IDE. This will launch the Dash app in a new browser window.
4. [Access the code on Replit](https://replit.com/@SecretSatoshis/Bitcoin-Chart-Library).

## Viewing the Charts on SecretSatoshis.com

All the charts generated by this application can also be viewed on the [SecretSatoshis.com](https://www.secretsatoshis.com/charts-promo) website.

## Automated Chart Updates with GitHub Actions

The charts in this project are updated daily using a GitHub Actions workflow. 

The workflow is scheduled to run every day at 16:00 UTC. It runs the `main.py` script, which generates the updated charts. After running the script, the workflow stages, commits, and pushes the changes to the main branch of the repository. This way, the charts in the repository are updated on a daily basis.

## Charts

The application generates a variety of charts to visualize Bitcoin data. Each chart is saved as an HTML file in the `Charts` directory of the repository. 

For a more detailed explanation of each chart, please refer to the comments in the `chart_format.py` file.

## License

This project is licensed under the terms of the GPLv3 license.
