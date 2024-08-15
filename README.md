# WHO Mortality Trends: 2017-2021

## Project Overview

This project includes data analysis with Python, Pandas, and Matplotlib for the World Health Organization (WHO) mortality data from 2017 - 2021.

- [Proposal Link (Google Docs)](https://docs.google.com/document/d/1WR-3B-1iszChYkx3cBd1c117qlKFfT9cM7boVALNFx0/edit)
- [Summary Presentation (Google Slides)](https://docs.google.com/presentation/d/1zDFOMUjt6WJLFuCOu5crLI_SgaHIN3Imq4bwdalwgR8/edit#slide=id.g2f251018676_0_55)

Key contributors: Jack Kuppuswamy, Jenn Allen, Rian King, Shyla Tatum, Vaughan Roberts

## In-Depth Analysis

All analysis looks closely at the association of ICD (International Classification of Diseases) codes to the WHO mortality data.

**List of workbooks**

- Gender Analysis, Shyla Tatum - View Juypter Notebook
- (Add Section Title Here), Rian King
- (Add Section Title Here), Jack Kuppuswamy
- (Add Section Title Here), Vaughan Roberts
- (Add Section Title Here), Jenn Allen

### Analysis: Gender Analysis, Shyla Tatum

View Jupyter Workbook

Gender was graphed by year as a side-by-side comparison. The data was grouped and then cleaned to the relevant data. Gender was also analyzed by grouping by country and then graphing female to the left and males to the right by total deaths during the 5 years.

#### Citations

- [turn off scientific notation](https://www.tutorialspoint.com/prevent-scientific-notation-in-matplotlib-pyplot)
- [colors](https://matplotlib.org/stable/gallery/color/named_colors.html)
- [matplotlib table types](https://matplotlib.org/stable/plot_types/index.html)
- [filter using OR](https://www.statology.org/or-operator-in-pandas/)
- [Changing the color](https://stackoverflow.com/questions/63460213/how-to-define-colors-in-a-figure-using-plotly-graph-objects-and-plotly-express)

### Analysis: (Add Section Title Here), Rian King

View Jupyter Workbook


### Analysis: (Add Section Title Here), Jack Kuppuswamy

View Jupyter Workbook

The Jupyter Notebook `mortality_agegroup_visualizations.ipynb` provides visualizations of mortality data across different age groups and ICD categories over the years. The visualizations help in understanding trends and patterns in mortality rates, especially within specific age groups and disease categories.

#### Key Features

- **Mortality by Age Group**: Visualizes mortality trends across different age groups over a set of years.
- **Mortality by ICD Category**: Visualizes mortality trends across various ICD categories, highlighting the leading causes of death.
- **Customization**: Includes features like color maps, labels, legends, and axis formatting to enhance the readability and presentation of the data.

#### Analysis Contents

##### Plotting Mortality by Age Group

- A line plot is generated to visualize mortality data for different age groups from 2017 to 2021.
- The plot includes labels for the axes, a title, a legend, and specific formatting to enhance readability.

##### Plotting Mortality by ICD Category

- A set of line plots is created to showcase mortality trends by ICD category over the same period for different age groups listed below.
  - 0-1 Year
  - 1-24 Years
  - 25-44 Years
  - 45-69 Years
  - 70-95+ Years

Similar customization features are applied, including setting axis limits, customizing tick marks, and positioning the legend.

## Customization

The plots can be customized further by modifying parameters in the plotting functions, such as changing the color map, adjusting axis labels, or adding additional data points.

### Analysis: (Add Section Title Here), Vaughan Roberts

View Jupyter Workbook

Overview goes here

### Analysis: (Add Section Title Here), Jenn Allen

View Jupyter Workbook

Overview goes here

## How to Run this Project

### Requirements

- Ensure you have Python installed (preferably version 3.6 or higher).
- Install the necessary Python packages by running the packages specified in the Notebook's imports section. For instance:
  
     ```bash
     pip install pandas matplotlib notebook
     ```

### Running the Notebooks

First, clone this repository and then open the notebook file you want to see the analysis for in VSCode or with Jupyter Server. See each analysis section above for the direct links to each exploration.

#### Run with VSCode

1. Open the notebook in VSCode.
2. Click `Run All` to run the analysis and view the visualizations.

#### Run with Jupyter Server

1. Open the terminal and navigate to the directory containing the notebook
2. Launch Jupyter Notebook by typing:

     ```bash
     jupyter notebook
     ```

3. Open the notebook (`woorkbook_name_here`) in the browser and run the cells.

## Contributing

Contributions, issues, and feature requests are welcome! Fork the repository, create a branch, make your changes, and submit a pull request.
