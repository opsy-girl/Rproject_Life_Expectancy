# Life Expectancy
Time Series Forecasting: ARIMA models

The South African Weather Service (SAWS) is a technology firm that specialises in providing services regarding weather, climate, and related products in South Africa. By enhancing observational data and communication networks to convert data into meaningful products and services for risk mitigation, advancing the science of meteorology and research. The SAWS research team is investigating the use of conventional and advanced machine learning technologies in predicting weather conditions. As a technical consultant for the company, you have been tasked with evaluating some ML techniques' performance to forecast daily minimum temperatures given historical data. (“saws_time_series_datasets.csv”).

1.1.    Using R, preload the SAWS datasets in the scientific environment and provide a plot for the time series.  
1.2.    Divide your datasets into training and test sets in a proportion of 20/80 and build an ARIMA (p,d,q) model for daily minimum temperature forecasting. Estimate the best model orders using Akaike Information Criterion (AIC) or AIC corrected.   
1.3.    Provide two time-series plots of the training set and test set, including the forecasted models, and provide the mean sum of squares error estimates for both forecasts.   



# Classification: Diabetes Expert System

Sediba MedResearch is a research company that focuses on the study of diseases aiming to provide accurate expert systems that can help medical practitioners treat patients within hospitals. Among the several diseases the research firm works on; you have been assigned as a data scientist to the niche group working on Diabetes detection and classification. Currently, the team is working on a dataset (“smr_diabetes.csv”) to predict, given a patient profile, the likelihood that the patient has Pima Indian diabetes. The team deem relevant to test several models and identify the model with the highest detection accuracy.

2.1.    Divide the datasets into 80/20 per cent of training and test sets and use 10-fold cross-validation during model training to minimize bias. Train the datasets using the classification algorithms learned: Logistic Regression, Naïve Bayes and Decision Trees.
2.2.    Using a properly labelled bar graph, plot the average classification accuracy (training and test sets) for each algorithm following the 10-fold cross-validation training process and advise on the most accurate model among the three. Also, provide the aggregated confusion matrices (training and test sets) for each algorithm after 10-fold cross-validation
2.3.    Develop an ensemble learning classification algorithm from the three models, compare its average classification accuracy (training and test set) against the initial three models, and comment on your findings. Elaborate on the implementation process of the ensemble learning algorithm designed.


# Word: Life Expectancy

Regression Analysis:  Word Life Expectancy

The World Health Organisation has surveyed demographic variables affecting people’s life expectancy across all countries in the world from a period of 2000 to 2015. The datasets ("Life_Expectancy_Data.csv") are described as follows:

Country:Country name
Year:Year of the data
Status:Country status of developed or developing
Life Expectancy:In age
Adult Mortality:Probability of dying between 15 and 60 years per 1000 population
Infant.deaths:Number of Infant Deaths per 1000 population
Alcohol:Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)
percentage.expenditure:Expenditure on health as a percentage of Gross Domestic Product per capita(%)
Hepatitis.B:Hepatitis B (HepB) immunization coverage among 1-year-olds (%)
Measles:number of reported cases per 1000 population
BMI:Average Body Mass Index of entire population under.five.deaths
Number of under-five deaths per 1000 population 
Polio:Polio (Pol3) immunization coverage among 1-year-olds (%)
Total.expenditure:General government expenditure on health as a percentage of total government expenditure (%)
Diphtheria:Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%) room
HIV.AIDS:Deaths per 1 000 live births HIV/AIDS (0-4 years)
GDP:Gross Domestic Product per capita (in USD)
Population:Population of the country
thinness..1.19.years:Prevalence of thinness among children and adolescents for Age 10 to 19 (% )
Income.composition.of.resources:Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
Schooling:Number of years of Schooling(years)

3.1.    Clean the dataset and provide a density function plot of the life expectancy across all countries. In addition. provide a box plot of the life expectancy data across countries and briefly describe the five-number summary statistics obtained. 
3.2.    Provide a bar chart of the average life expectancy across all countries in descending order of life expectancies.  
3.3.    Generate a correlation matrix using relevant correlation measures and hypothesis testing to select predicting variables that affect life expectancy and only consider statically significant variables. Which variables can contribute to life expectancy? Elaborate on the correlation measures used, the hypothesis tests performed and the relationship between each predicting variable and life expectancy.  
3.4.    Divide your data into 80/20 training and test sets and build a linear regression model to predict life expectancy based on the relevant predicting variables. Train your model using a 10-fold cross-validation scheme. Compute the coefficient of determination plots and R2 scores for the best model on both the training and test set.  
3.5.    Perform 2D clustering analysis using k-Means clustering and the silhouette method to find existing clusters based on their GDP and Life expectancy attributes. Present your data graphically and elaborate on your findings.   
                                                                                                
