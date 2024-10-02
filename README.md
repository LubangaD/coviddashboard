# COVID-19 Data Dashboard

This project is a simple interactive dashboard that visualizes COVID-19 data, using Dash, Plotly, and Pandas. The dashboard includes tables and visualizations for selected countries, displaying their respective COVID-19 case and death statistics.

## Project Structure

- **coviddashboard/** - The root directory for the project.
  - `app.py` - Main script containing the dashboard layout and callbacks.
  - `requirements.txt` - Lists the required Python packages.
  - **data/** - Directory containing the dataset file (`coviddata.xlsx`).

## Features

- **Data Table**: Displays a table of countries with total cases and deaths.
- **Line Chart**: A line chart to track COVID-19 cases or deaths over time for the selected countries.
- **Pie Chart**: A pie chart to show the proportion of cases or deaths for selected countries.

## Installation

### Prerequisites
1. Ensure you have Python installed.
2. You should also have `pip` or `pipenv` to manage Python packages.

### Steps to run the project:

1. Clone the project to your local machine:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the `coviddashboard` folder:

   ```bash
   cd coviddashboard
   ```

3. Create a virtual environment using `venv`:

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - **For Windows**:

     ```bash
     venv\Scripts\activate
     ```

   - **For macOS/Linux**:

     ```bash
     source venv/bin/activate
     ```

5. Install the required Python packages from the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

6. Ensure the COVID data file (`coviddata.xlsx`) is in the `data` folder.

7. Run the app:

   ```bash
   python app.py
   ```

## Dependencies

- **Pandas**: For data manipulation.
- **Plotly**: For creating interactive charts.
- **Dash**: For building the web application interface.

The full list of required packages is available in `requirements.txt`.

## Dataset

The data for this dashboard is stored in an Excel file (`coviddata.xlsx`) located in the `data` folder. The dataset contains COVID-19 statistics, including cases and deaths for different countries.

## Usage

1. Select countries from the table by clicking on the rows.
2. Use the dropdown menus to switch between 'Deaths' and 'Cases' for both the pie chart and the line chart.
3. The visualizations will update based on the selected countries and metrics.

