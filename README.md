# EDA on the performance of a Flyball dog race team

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Breezeflyballtraining.JPG/1920px-Breezeflyballtraining.JPG" width="300"/>
</p>

## 1) Project background

This analysis is based on a fictional data, but with real background and situation.

Flyball is a relay team competition for dogs where participants jump obstacles to retrieve a ball from a special box. The competitions are run in teams of four dogs, as a relay. If you want to know more information about the Flyball sprt, [visit this Wikipedia page](https://en.wikipedia.org/wiki/Flyball)).

<p align="center">
  <img src="https://cdn.shopify.com/s/files/1/0866/0808/files/photo_480x480.jpg?v=1673882092" width="400"/>
</p>

The data imitates that the fictional Flyball team's (Wild Runners Flyball Team – or WRFT) coach hired me to analyze their last year's dataset from different races. The overall goal is to find insights that will help to improve their performace.

The analysis was originally made for the in-house competition of the [Data36.com](https://data36.com) data science club, where I ranked at first place with this EDA.

## 2) Project Objective and Results

### *Objective*

**Processing** the WRFT flyball team's competition data from the past year **to build up a comprehensive picture**, which will also help them **to achieve even higher levels of performance** in the future.

*Main contributions:*

- Data preprocessing and cleaning
- Basic EDA
- Advanced EDA (with collecting data from external sources)
- Team composition optimization

*Dataset:* 
- Table 1: results of the Czech national competition related to the WRFT team
- Table 2: results of the Czech international competition related to the WRFT team
- Table 3: base data of the racing dogs

The description of the dataset variables is available [here](https://github.com/roland045/flyball_race_analysis/tree/main/data).

### *Results*

In the analysis, I have **identified and communicated the key factors** that are critical to race results. I communicated the **recommendations for changes** that would help the team achieve better results and continue to operate.

- Database cleaning and exploratory analysis
- Obtaining missing data from external sources (API)
- Identification of the key factors that determine race results and dog performance
- Recommendations for training plan and competitions to achieve better placings, thus ensuring the sustainability of the team
- Optimisation of team composition
- Presentation of results to stakeholders


 **Methods Used**
* Data Cleaning
* Data Exploration
* Investigate Statistical Metrics
* Data Visualization
* Feature Importance analysis with Machine learning
* Optimization with Machine learning
* API usage
* Presentation of found insights

**Tools**
* Python
* Excel


## 3) Detailed description

### Data preprocessing and cleaning

- Read different non-standard format Excel tables to Python
- Ensuring data integrity
  - Handling of outliers
  - Handling missing rows and cells
  - Correction of inconsistent datapoints
- Providing basic statistical metrics

### Basic EDA

- Reading Excel metadata (cell color codes) into Python
- Answering the coach's questions (based on the coach's previous experience, he had a subjective opinion, he was curious if this was supported by the data).
- Summaries and visualizations
- Creation of external pivot tables for data aggregation

### Advanced EDA

- Preparation of further advanced level analyzes according to club owner and coach questions
 - Many transformations and formatting on data tables
- Examination of the effect of weather
 - Geocoding of competition locations
 - Download historical weather data via API connection
 - Analysis of weather effects, visualization

### Team composition optimization

- Development of a machine learning model
  - To predict the team performance
  - To check the variable importances (using SHAP method)
- Model relevance check
- Optimization of team composition using Partial Dependence method

### Presentation of results

- In-person presentation of results to a jury of recognized senior data scientists

### Origanized by

[Data36.com](https://data36.com)
