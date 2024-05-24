# GEOG5990_final_project
The project aims to analyze two datasets: 1) Causes of Death in the United States, and 2) Household Income Ranges in Tempe, US, using spatial data. The first dataset provides age-adjusted death rates for the 10 leading causes of death in the US from 1999 onwards, while the second dataset contains information on household income ranges, families, married couple families, and non-family households in Tempe, US, based on the US Census American Community Survey (ACS) 5-year estimates.

The project aims to analyze two distinct datasets using spatial data analysis techniques:

## Causes of Death in the United States

This dataset provides age-adjusted death rates for the 10 leading causes of death across the United States from 1999 onwards. The analysis involves:

- Examining spatial and temporal patterns in mortality rates and causes across U.S. counties over time.
- Assessing the contribution of different causes of death to the excess mortality clusters.
- Visualizing the number in death in different years due to common causes such as 'Influenza and pneumonia', 'Heart disease', 'Cancer', 'Diabetes', 'Stroke' which might be a indication of the degrading lifestyles, climate change or other such factors. 

## Household Income Ranges in Tempe, US

This dataset contains information on household income ranges, families, married couple families, and non-family households in Tempe, US, based on the US Census American Community Survey (ACS) 5-year estimates. The analysis involves:

- Visualizing variables like 'Households_Total', 'Families_Total', 'Marriedcouple_families_Total', 'Nonfamily_households_Total', 'Households_Total_Less_than__10K', 'Households_Total_200K_or_more'.
- Integrating the Character Area Boundaries layer for Tempe to analyze income patterns across different neighborhoods.
- Performing K-means clustering and Spearman's rank correlation analysis on the income variables.
- Visualizing the concentration of household total income using the Getis-Ord Gi* algorithm for spatial hotspot analysis.

The analysis aims to uncover spatial patterns, inequalities, and hotspots in both mortality rates and household income ranges, while accounting for socioeconomic factors and neighborhood characteristics.


## Data and Code
  The GitHub repository contains the following:
    Datasets:
      Causes of Death in the United States (downloaded from https://catalog.data.gov/dataset/nchs-leading-causes-of-death-united-states)

Household Income Ranges in Tempe, US (downloaded from: https://catalog.data.gov/dataset/income-acs-2018-2022-tempe-tracts)

 Character Area Boundaries layer (for Tempe, US, downloaded from: https://catalog.data.gov/dataset/character-area-boundary-7f773.)

## Python Code:

  Data cleaning and pre-processing scripts
  
  Visualization code (bar graphs, pair plots, maps)
  
  K-means clustering implementation
  
  Spearman's rank correlation analysis
  
  Getis-Ord Gi* algorithm for spatial analysis
  

## Code Functionality

The code performs the following tasks:

  ### Causes of Death Dataset:
  
    Data cleaning and pre-processing
    
    Simple visualizations (bar graphs, pair plots)
###  Household Income Dataset:
  
    Data cleaning and pre-processing
    Visualization of variables like 'Households_Total', 'Families_Total', 'Marriedcouple_families_Total', 'Nonfamily_households_Total'
    Integration of Character Area Boundaries layer
    K-means clustering analysis
    Spearman's rank correlation analysis
    Visualization of household total income concentration using the Getis-Ord Gi* algorithm

## Running the Code

To run the code and reproduce the analysis, follow these steps:

1. Clone the GitHub repository to your local machine.
2. Install the required Python packages (e.g., pandas, matplotlib, seaborn, geopandas, etc.).
3. Download the datasets from the provided links (data.gov) and place them in the appropriate directory within the repository.

Run the Python scripts in the following order:

1. Data cleaning and pre-processing scripts
2. Visualization scripts
3. K-means clustering and correlation analysis scripts
4. Getis-Ord Gi* algorithm script

Note: Ensure that you have the necessary dependencies installed and adjust the file paths in the scripts according to your local setup.
