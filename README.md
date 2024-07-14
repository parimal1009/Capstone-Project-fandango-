Movie Review Bias Analysis
Overview
This project aims to investigate whether Fandango's movie ratings in 2015 exhibited a bias towards higher ratings, potentially influenced by their business model of selling movie tickets. We analyze data from a 538 article to compare Fandango's ratings with other movie rating platforms.

Project Goals
Determine if there is a bias in Fandango's movie ratings by comparing them with ratings from other sites.
Use pandas and visualization tools (matplotlib and seaborn) to analyze and visualize the data.
Identify movies with significantly higher ratings on Fandango compared to other platforms.
Explore the top 10 lowest-rated movies based on Rotten Tomatoes Critic Ratings and compare their normalized scores across all platforms.
Data Sources
The analysis uses data sourced from a 538 article on movie ratings in 2015, comparing Fandango's ratings with other prominent movie review platforms.

Analysis Results
Based on the analysis:

Fandango tends to rate movies higher compared to other sites, especially for movies that are considered poorly rated on other platforms.
Specific movies were identified where Fandango's ratings significantly deviated from those of Rotten Tomatoes and other critics.
Project Structure
Data Analysis Notebook: Contains detailed Python code using pandas for data manipulation, matplotlib and seaborn for visualization, and statistical analysis.
Visualizations: Includes visual outputs such as histograms, scatter plots, and bar charts used to illustrate rating comparisons.
README.md: This file, providing an overview of the project, its goals, data sources, analysis results, and how to navigate the repository.
Usage
To reproduce the analysis or explore the data further:

Clone this repository to your local machine.
Open the Jupyter Notebook file Movie_Review_Bias_Analysis.ipynb using Jupyter Notebook or Jupyter Lab.
Execute the cells in order to load, clean, analyze, and visualize the data.
Review the findings and visualizations to understand the comparison of Fandango's ratings with other platforms.
Dependencies
Ensure you have the following Python libraries installed:

pandas
matplotlib
seaborn
numpy
Future Work
Future enhancements to this project could include:

Incorporating more recent data to analyze if Fandango's rating behavior has changed over time.
Building predictive models to understand factors influencing movie ratings.
Conducting sentiment analysis on user reviews to complement rating comparisons.
