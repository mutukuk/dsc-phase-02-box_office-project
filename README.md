# Microsoft Movie Studio Analysis

## Overview
This repository contains the final project submission for DSC-PT-09 Group 4, focusing on analyzing movie data to provide actionable insights for Microsoft's new movie studio. The project explores various datasets to understand what types of films are currently performing well at the box office and provides recommendations for Microsoft to create successful movies.

## Contributors
- Edel Lwoyelo: 
- Kelvin Mutuku: 
- Bertha Karuku: 
- Christine Kindena:
- Mercy Kangangi: 
- Bryan Njogu: 

## Business Problem
Microsoft is venturing into the movie industry and needs to understand what types of films are currently successful at the box office. The goal is to analyze existing movie data to provide insights that will help Microsoft decide what types of films to produce.

## Data Sources
The analysis uses datasets from:
- **Box Office Mojo**
- **IMDB**
- **TheMovieDB**
- **Rotten Tomatoes**
- **The Numbers**

## Research Questions
1. **Box Office Mojo Data**: What is the relationship between domestic and foreign gross earnings of movies? Does a particular genre perform better in domestic versus international markets?
2. **Rotten Tomatoes Reviews Data**: What is the correlation between review sentiment and movie earnings or genre? How are ratings and reviews distributed?
3. **IMDB Movies Data**: Which genres are popular in terms of vote averages, popularity, and their alignment with revenue performance?
4. **The Numbers Movie Budgets Data**: How do production budgets relate to worldwide and domestic gross earnings? Is there an ROI pattern?
5. **IMDb Movie Data**: How do IMDb user ratings correlate with a movie's overall success? Do higher-rated movies consistently perform better, and how do these ratings vary across genres or regions?

## Data Analysis
The analysis involves:
- **Data Cleaning**: Handling missing values, standardizing data formats, and removing outliers.
- **Data Merging**: Combining datasets from different sources to create a comprehensive dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizing data distributions, correlations, and trends.
- **Insights Generation**: Drawing actionable insights from the data to guide Microsoft's movie production strategy.

## Key Findings
1. **Domestic vs. Foreign Gross Earnings**: Strong positive correlation between domestic and foreign gross earnings. Action, Adventure, and Animation genres perform well in both markets.
2. **Review Sentiment and Earnings**: Higher Rotten Tomatoes scores correlate with higher box office earnings. Dramas and Documentaries receive higher critical ratings, while Action and Animation films receive higher audience ratings.
3. **Popular Genres and Revenue Performance**: Action, Adventure, and Animation are the most popular genres in terms of vote averages, popularity, and revenue performance.
4. **Production Budgets and ROI**: Higher production budgets generally correlate with higher earnings, but mid-budget films often achieve the best ROI.
5. **IMDb Ratings and Success**: Movies with IMDb ratings of 7.0 and above consistently perform better in terms of box office earnings and audience engagement.
6. **Runtime Optimization**: Movies with runtimes between 90 and 120 minutes tend to have the highest average ratings and profitability.

## Recommendations
1. **Focus on High-Performing Genres**: Prioritize Action, Adventure, and Animation films.
2. **Optimize Budget Allocation**: Focus on mid-budget films to maximize ROI.
3. **Aim for High Ratings**: Prioritize quality to achieve IMDb ratings of 7.0 or higher.
4. **Target Optimal Runtime**: Aim for a runtime of 90-120 minutes for mainstream releases.
5. **Build Franchise Potential**: Develop franchise opportunities within high-performing genres.
6. **Boost Audience Engagement**: Invest in robust marketing campaigns to drive pre-release buzz.
7. **Conduct Market Research**: Gather data on audience preferences and emerging trends.

## Repository Structure
- **zippedData/**: Contains the datasets used in the analysis.
- **notebooks/**: Jupyter notebooks for data cleaning, analysis, and visualization.
- **presentation_pdf/**: Contains the final project report and presentation.
- **README.md**: This file, providing an overview of the project.

## How to Use This Repository
1. Clone the repository:

   git clone https://github.com/mutukuk/dsc-phase-02-box_office-project.git
   
2. Navigate to the project directory:
   
   cd dsc-phase-02-box_office-project

3. Install the required dependencies:
   
   pip install -r requirements.txt
   
Open and run the Jupyter notebooks in the notebooks/ directory to explore the data analysis process.

 ## Dependencies

- **Python 3.x**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Jupyter Notebook**
   

  ## License
   This project is licensed under the MIT License. See the LICENSE file for details.

  ## Acknowledgments
   Moringa School for providing the platform and resources for this project.

  
   Instructor: Noah Kandie for guidance and support throughout the project.

   For any questions or further information, please contact any of the contributors listed above.

This `README.md` provides a comprehensive overview of the project, including the business problem, data sources, analysis process, key findings, and recommendations. 
It also includes instructions on how to use the repository and the necessary dependencies.
