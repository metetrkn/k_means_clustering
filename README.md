# CIA Country Analysis and Clustering

    This repository contains a Python script that analyzes and clusters countries based on various features obtained from the US government's CIA World Factbook. The goal is to gain insights into the similarities between countries and regions of the world by experimenting with different cluster amounts.

Source: The World Factbook

## Dataset

    The dataset CIA_Country_Facts.csv contains the following features:

        Country
        Region
        Population
        Area (sq. mi.)
        Pop. Density (per sq. mi.)
        Coastline (coast/area ratio)
        Net migration
        Infant mortality (per 1000 births)
        GDP ($ per capita)
        Literacy (%)
        Phones (per 1000)
        Arable (%)
        Crops (%)
        Other (%)
        Climate
        Birthrate
        Deathrate
        Agriculture
        Industry
        Service

## Project Overview

    Exploratory Data Analysis: Visualize data distributions and correlations between features.
    Data Preparation: Handle missing values, create dummy variables for categorical features, and scale the data.
    Model Discovery: Perform K-means clustering with different K values and analyze the results.

## Usage

    Clone this repository.
    Ensure that you have Python 3.x installed, along with the required libraries mentioned in the code (pandas, numpy, matplotlib, seaborn, sklearn).
    Run the Python script to perform clustering on the country data.

## Dependencies

    pandas
    numpy
    matplotlib
    seaborn
    sklearn


## Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


## Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
