# Electric-Vehicles-Analysis
A python data analysis project to identify trends in market sales, laws, and policies related to EVs in the U.S.
# Evolutionary Drive

Welcome to our project on electric vehicles! This repository contains the Jupyter Notebook "EvoultionaryDrive.ipynb," which explores the purpose, background, data collection, analysis, key findings, and implications for the future of electric vehicles.

## Table of Contents

- [Introduction](#introduction)
- [Data Collection, Cleaning, and Preparation](#data-collection-cleaning-and-preparation)
- [Visual Representation and Analysis](#visual-representation-and-analysis)
- [Main Focus of Data Analysis](#main-focus-of-data-analysis)
- [Conclusion and Recommendations](#conclusion-and-recommendations)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Since their inception in the late 19th century, automotive vehicles have faced significant innovation, notably shifting from oil and gas to electric power sources. This transition has accelerated in the last decade, peaking in March 2022 during the COVID pandemic. The appeal of electric vehicles has led to potential bans on traditional engines and incentives for electric vehicle adoption.

Our aim is to reveal key insights by analyzing data and identifying trends in market sales, laws, and policies related to EVs.

## Data Collection, Cleaning, and Preparation

### Sources of Data

We gathered data from reliable sources, including government reports, industry databases, and research papers.

### Cleaning and Filtering Data

We ensured data accuracy by removing duplicates, handling missing values, and filtering irrelevant information.

### Data Analysis and Visualization

We explored the data through descriptive statistics and created insightful visualizations for better understanding.

### Data Cleaning and Preparation Details

- Replacing missing electric ranges data to determine their Alternative Fuel Vehicle Eligibility using external data through web scraping.
- Splitting law and incentive categories into sub-categories with dummy variables.
- Organizing the columns of the data frames for the analysis:
  - Deleting redundant observations and columns with major missing values.
  - Assigning appropriate data types.
  - Splitting the columns for smoother data handling.

## Visual Representation and Analysis

### Maps and Heatmaps

Visualize the geographic distribution and intensity of electric vehicle adoption and its correlation to the Laws/Incentives provided by the government.

### Bar and Pie Charts

Present statistical insights on electric vehicle sales, market share, and classification of laws and incentives.

### Line Plots

Examine the progression of sales in the electric vehicle (EV) industry over time and investigate the correlation between CO2 emissions and the sales of EVs throughout the same period.

[Line Plot of EV Sales and CO2 Emissions](https://github.com/arhabhasan/Electric-Vehicles-Analysis/blob/main/dynamic_EV_map.html)

### Interactive Plot

Explore the interactive plot to visualize data dynamically:

[Interactive Plot](https://github.com/arhabhasan/Electric-Vehicles-Analysis/blob/main/dynamic_EV_map.html)

## Main Focus of Data Analysis

### Charging Infrastructure

Analyze the distribution and accessibility of charging stations in the US.

### Market Trends

Identify patterns and trends in electric vehicle sales and market growth.

### Environmental Impact

Assess the environmental advantages of electric vehicles in terms of reduced emissions.

### Laws and Incentives

Provide evidence of a high positive relationship between laws and incentives and charge stations.

## Conclusion and Recommendations

The imminent rise of Electric Vehicles (EVs) has traditional manufacturers like Toyota concerned about potential production output reduction due to increasing demand for raw materials. Despite rising material costs, EV sales have been increasing since 2021. The EV industry's resilience is evident in the correlation between the population of EVs, charging stations, and state laws and incentives. Tesla's market share is declining as more EV manufacturers emerge and traditional ones shift focus. However, law inconsistencies across states show that local governments need to do more. The rise of EVs, crucial for reducing CO2 emissions, calls for state governments to encourage the EV transition and support manufacturers for a sustainable future.

## Installation

To run this notebook, you need to have the following software and libraries installed:

- Python 3.7 or later
- Jupyter Notebook
- Required Python libraries (see below)

You can install the required Python libraries using the following command:

```bash
pip install -r requirements.txt
requirements.txt
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/arhabhasan/Electric-Vehicles-Analysis.git
```

2. Navigate to the project directory:

```bash
cd Electric-Vehicles-Analysis
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the "EvoultionaryDrive.ipynb" notebook and run the cells to explore the evolutionary algorithms.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.


