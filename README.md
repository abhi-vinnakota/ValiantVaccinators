# Team: Valiant Vaccinators
# Members: Abhi Vinnakota, Jasmine Trapier
# Mentor: Dr. Kanampiu
# Co-Mentors: Dr. Caldwell, Mr. Belton

## Background
Many individuals in the United States have still chosen not to get vaccinated. This
analysis of Covid-19 data might help change their minds. If not, it is only intended for 
educational purposes only. 

## Goal
Valiant Vaccinator's overall goal was to investigate Covid-19 trends in comparison 
with vaccination rates. More specifically, we wanted to compare the correlation between the number of vaccinations and the death/infection rate in America.

## Technologies Used
- Google Colab (HPC)
- Jupyter Notebook
- Python
- Pandas
- Sci kit learn
- Matplotlib
- NumPy
- SciPy
- Linear Regression
- KNeighbors Regression

## Process
To begin, we scraped data from https://ourworldindata.org/explorers/coronavirus-data-explorer. This dataset was then broken down and we created our own set of data 
from what was already given. We decided to focus our investigation on Covid-19 in the United States from March 3rd, 2020 to July 3rd, 2021. We then read the data file using Jupyter Notebook in Google Colab. After the data was cleaned, we used python libraries to visualize multiple 
sets of graphs. Included we have Covid Deaths in America Over Time, Covid Vaccinations in America Over Time, Covid Cases in America Over Time, Rate of Infection in America Over Time, and Covid Death Rate in America Over Time. We then used Linear Regression models to visualize Death Rate vs. People Vaccinated in America, and Infection Rate vs. People Vaccinated in America. By calculating linear regression, we were able to prove that there is a significant relationship between death/infection rate vs. vaccinations in America, with an R^2 value of .61 and .63 respectively. Afterward, we used machine learning techniques to predict the number of new deaths by training a KNeighbors Regression Model on the number of vaccinations, infection rate, and positivity rate over the time period. We were able to train a model to predict the death rate within a mean average error of 169.

## Conclusion
We are satisfied and fascinated with our results from this project. It was interesting to see the strong correlation between death rates and vaccinations, and infection rate and vaccinations. With these results, we hope to dispel any disbelief in the effectiveness of the vaccines and help encourage anyone who has chose not to vaccinate to go get vaccinated. By taking a step back and analyzing the entire pandemic thus far, we were able to prove that the vaccinations significantly improved the state of the pandemic by leading to a lower death and infection rate. If the United States continues getting people vaccinated at the same rate, we will likely be able to flatten out the death and infection rates. With new variants on the horizon, it is increasingly important for people to understand the importance of getting vaccinated. If we were to continue this project in the future, we would like to analyze Covid trends at the state level, and also compare how vaccination has improved death/infection rate in other countries. In addition, we would also like to use more advanced machine learning techniques to be able to visualize a future projection of death/infection rate based on the data collected thus far.
