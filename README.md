"# pattyhumemills.github.io" 
Purpose of this repository: To collect Patricia AH Mills' code to create a data science portfolio.

Programs and their Descriptions

1) SQL
  SQL_Database_Girl_Scout_Troop: This code is repeatable and contains both DDL and DML language. I created a database for the Girl Scout Troop I lead. This version has names, phone numbers, and email addresses changed for privacy. On the database that I maintain and is set to private, the information is accurate so as to be useful. This version also is not updated with newer events and badges.

2) R
  Airline_Satisfaction_DataAnalysis_R: Originally this was a group project for my IST687 Intro to Data Science course. Given a sample set of airline satisfaction surveys for fictitious airlines, my team ran a random forest to determine which variables were most important. We ran several data analysis visualizations as well to determine any interactions. My portion of the project was to read in the data, do some of the early data cleaning, create and analyze several prediction model types: linear regression with a parsimonious model, neural network, and support vector machine. All prediction models were analyzed by finding the root mean square error. I also created a set of association rules with a confidence of 95% and a lift greater than 3.5.
  
  Lake_BouyData_Visualization_R: This code was written as the start of a viz-a-thon. It focuses on the descriptive analytics to determine what was important to visualize. The libraries used were: ggplot2, ggthemes, and ggcorrplot.
  
  Immunization_Visualization_R: The first 1338 lines are from the Centers for Disease Control to read in and format their National Immunization Survey data. My code starts on line 1339. Using the National Immunization Survey data, I subset the data to look at immunization rates for 0-3-year-olds in Texas. I then used the following libraries to create plots: RColorBrewer, plotrix, dplyr, ggplot2, lattice, alluvial, treemap. To get a comparison on where the immunization rates were by the time children entered kindergarten, I used data from the Department of State Health Services in Texas. I used the libraries: maps, mapproj, ggmap, usmap, plotly, and choroplethr to create a choropleth map of the counties in the state with the darker counties reporting lower percentages of students with all of their immunizations.
  
3) Python
  MLB_castastrophe_effects_Python: This program analyzes the effect of catastrophic events on pitching, hitting, scoring, and wins/losses. The FEMA disaster list from fema.gov was used to find events during the 2012-2017 MLB season for select teams -- Houston Astros, Texas Rangers, Miami Marlins, Boston Red Sox, Colorado Rockies, New York Yankees, and New York Mets. Neither the Mets nor the Yankees had any FEMA declared disasters between 2012 and 2017 during the baseball season. For the purposes of this task, only disasters affecting the county where the team played were used. Numpy, Pandas, and Matplotlib were used to create this analysis.
