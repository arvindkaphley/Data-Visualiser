# Data Visualizer Web App

## Overview

The Data Visualizer Web App is a user-friendly tool designed to enable users to visualize their data with ease. Built using Streamlit, this web app allows users to upload CSV files, select columns for visualization, and generate various types of plots to analyze their data.

## Features

- **File Selection**: Users can select CSV files from a designated `data` folder.
- **Data Preview**: Displays the first few rows of the selected dataset.
- **Column Selection**: Allows users to select columns for the X and Y axes.
- **Plot Selection**: Supports multiple plot types including Line Plot, Bar Chart, Scatter Plot, Distribution Plot, and Count Plot.
- **Interactive Plots**: Generates plots dynamically based on user input.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or higher
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/data-visualizer-web-app.git
    cd data-visualizer-web-app
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Create a `data` folder**:
    ```bash
    mkdir data
    ```

4. **Add your CSV files to the `data` folder**.

### Running the App

Run the following command to start the Streamlit app:
```bash
streamlit run main.py
