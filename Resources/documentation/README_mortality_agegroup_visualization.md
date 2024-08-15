# Mortality Age Group Visualizations

## Overview

The Jupyter Notebook "mortality_agegroup_visualizations.ipynb" provides visualizations of mortality data across different age groups and ICD (International Classification of Diseases) categories over the years. The visualizations help in understanding trends and patterns in mortality rates, especially within specific age groups and disease categories.

## Key Features

- **Mortality by Age Group**: Visualizes mortality trends across different age groups over a set of years.
- **Mortality by ICD (International Classification of Diseases) Category**: Visualizes mortality trends across various ICD categories, highlighting the leading causes of death.
- **Customization**: Includes features like color maps, labels, legends, and axis formatting to enhance the readability and presentation of the data.

## Contents

### 1. **Data Import and Preparation**
   - The notebook begins with importing the necessary libraries (e.g., `pandas`, `matplotlib`) and loading the mortality data into a DataFrame.
   - Data is then processed and pivoted as needed for visualization.

### 2. **Plotting Mortality by Age Group**
   - A line plot is generated to visualize mortality data for different age groups from 2017 to 2021.
   - The plot includes labels for the axes, a title, a legend, and specific formatting to enhance readability.

### 3. **Plotting Mortality by ICD Category**
   - Set of line plots are created to showcase mortality trends by ICD category over the same period for different age groups listed below.
     - 0-1 Year
     - 1-24 Years
     - 25-44 Years
     - 45-69 Years
     - 70-95+ Years
   - Similar customization features are applied, including setting axis limits, customizing tick marks, and positioning the legend.

### 4. **Analysis and Insights**
   - The notebook provides brief observations and insights based on the generated visualizations.
   - It highlights significant trends, such as increases in mortality within certain age groups or categories over time.

## How to Run the Notebook

1. **Requirements**:
   - Ensure you have Python installed (preferably version 3.6 or higher).
   - Install the necessary Python packages by running:
     ```bash
     pip install pandas matplotlib notebook
     ```
    - The execution of the notebook `mortality_agegroup_visualizations.ipynb` depends on the output file `df_final.csv` from `who_mortality_cleaning_workbook.ipynb` notebook.

2. **Running the Notebook**:
   - Clone the repository or download the notebook file.
   - Open the terminal or Anaconda prompt.
   - Navigate to the directory containing the notebook.
   - Launch Jupyter Notebook by typing:
     ```bash
     jupyter notebook
     ```
   - Open the notebook (`mortality_agegroup_visualizations.ipynb`) in the browser and run the cells sequentially.

## Data Source

- The mortality data used in this notebook is generated from `who_mortality_cleaning_workbook.ipynb` notebook which utilized the World Health Organization's mortality and population datasets.

## Customization

- The plots can be customized further by modifying parameters in the plotting functions, such as changing the color map, adjusting axis labels, or adding additional data points.


## Contributions

Contributions, issues, and feature requests are welcome! Fork the repository, create a branch, make your changes, and submit a pull request.