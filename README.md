# Fleet Energy Analysis

## Overview

This project focuses on analyzing the energy performance of two cruise ships—**Vessel 1** and **Vessel 2**. The analysis covers key areas such as efficiency, propulsion, and power generation. Separate analyses have been conducted for each vessel, with detailed graphs and visualizations provided to illustrate the findings.

The goal is to understand the performance trends of each vessel and identify opportunities for improvement, aligning with international regulatory requirements for shipping.

## Data Exploration and Preprocessing

- **Initial Data Analysis (EDA)**:
  - Explored the dataset to understand its structure and content.
  - Reviewed the provided `schema.pdf` to comprehend data fields and their significance.

- **Handling Missing Values**:
  - Identified null values specific to each vessel.
  - Applied **linear regression** to estimate and fill missing values, ensuring a complete dataset for analysis.

## Analysis

### Power Consumption Analysis

- **Separate Analyses for Each Vessel**:
  - Conducted individual analyses for Vessel 1 and Vessel 2.
  - Generated graphs to visualize power consumption patterns over time.
  - Identified trends and anomalies in power usage.

- **Key Observations**:
  - Noted periods of high and low power consumption.
  - Examined factors influencing power consumption, such as vessel speed and operational conditions.

### Power Generation Analysis

- **Stationary vs. Moving Vessel**:
  - Analyzed power generation when vessels were stationary versus when they were moving.
  - Created separate graphs for each vessel to illustrate power generation differences.

### Fuel Efficiency Analysis

- **Calculated Fuel Efficiency**:
  - Computed the fuel efficiency for each vessel on a monthly basis.
  - Analyzed how sea temperature and speed over ground affect fuel efficiency.
  - Provided a comparative analysis between Vessel 1 and Vessel 2.

## Tools and Technologies

- **Environment**: Visual Studio Code with Jupyter Notebook extension.
- **Programming Language**: Python.
- **Key Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for data visualization.
  - `scikit-learn` for linear regression modeling.

## How to Use This Project

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/fleet-energy-analysis.git
   ```

2. **Install Required Libraries**:

   Ensure you have Python 3 installed. Then, install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks**:

   - Navigate to the `TUI_Cruises/` directory.
   - Open the Jupyter Notebook for analyses.
   - Execute the cells to view the analyses and generated graphs of **Vessel 1** and **Vessel 2**.

## Project Structure

- `data/` - Contains the `data.csv` dataset.
- `docs/` - Includes documentation and the `schema.pdf` file.
- `notebooks/` - Jupyter Notebooks with separate analyses for each vessel.
- `requirements.txt` - List of Python libraries required to run the project.
- `README.md` - Project documentation (this file).
