# Modeling King County House Prices
## Flatiron Mod 2 Housing Price Project

**Authors**: Andy Peng

The contents of this repository detail an analysis of the module 2 project. This analysis is detailed in hopes of making the work accessible and replicable.


### Business problem:

The task is to investigate housing prices for a company that focuses on finding affordable family houses in the Kings County area. For this project we will be using the Kings County Housing Sales dataset to investigate different features that might affect the housing prices. By using the kc_house_data.csv dataset we will be trying to find certain features that we should keep our eyes out to get the best prices for family houses.


### Data
Data includes house prices and features of houses such as zip code, number of bedrooms, number of bathrooms, etc.


## Methods
- Descriptive Analysis
- Choices Made
- Modeling (Future work)
- Key relevant findings from exploritory data analysis

## Results


#### Visual 1
<img src=./Image/WaterFrontView.png width="770">
> Box plot graph of House Prices with and without Water Front View

#### Visual 2
<img src=./Image/zipcodes.png width="800">
> Zip Code's Average Housing Prices

#### Visual 3
<img src=./Image/InteractiveMapping3.png width="800">
> Interactive Mapping of Zip Code's Average Housing Prices

#### Visual 4
<img src=./Image/SqftLivingPrice.png width="800">
> Footage of the house vs Housing Prices


## Recommendations:

To summarize everything above, we created a model that manages to predict housing prices within a $80,000 range. We chose to explore the features waterfront view, zipcode and sqft_living. Below shows the exploration results from the code above.

1) Houses with no waterfront view have a lower average in housing prices.

2) Zipcodes around certain locations such as Mercer Island tend to cost more than houses away from Mercer Island.

3) The larger the footage of the home is the more expensive the housing price is.


## Limitations & Next Steps

Due to time constraint, there are many features that we haven't considered. For example schools in the area, crime rate, time of sale and picture of the house.


### For further information
Please review the narrative of our analysis in [our jupyter notebook](./Housing_Price.ipynb) or review our [presentation](Module2–Housing_Price_Project_Presentation_with_notes.pdf)

For any additional questions, please contact andypeng93@gmail.com)


##### Repository Structure:

Here is where you would describe the structure of your repoistory and its contents, for example:

```

├── README.md                       <- The top-level README for reviewers of this project.
├── Housing_Prices.ipynb             <- narrative documentation of analysis in jupyter notebook
├── presentation.pdf                <- pdf version of project presentation
└── images
    └── images                          <- both sourced externally and generated from code

```
