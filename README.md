# Factors Affecting Global Warming
Predicting if credit card request will approved for the customer given other attributes.

### Motivation
Over the past 50 years, the average global temperature has increased at the fastest rate in recorded history. And experts see the trend is accelerating: All but one of the 16 hottest years in NASA’s 134-year record have occurred since 2000.
Global warming occurs when carbon dioxide (CO2) and other air pollutants and greenhouse gases collect in the atmosphere and absorb sunlight and solar radiation that have bounced off the earth’s surface. Normally, this radiation would escape into space—but these pollutants, which can last for years to centuries in the atmosphere, trap the heat and cause the planet to get hotter. That's what's known as the greenhouse effect.

In the United States, the burning of fossil fuels to make electricity is the largest source of heat-trapping pollution, producing about two billion tons of CO2 every year. Coal-burning power plants are by far the biggest polluters. The country’s second-largest source of carbon pollution is the transportation sector, which generates about 1.7 billion tons of CO2 emissions a year.

In this project our group tried to study how various factors such as C02 emission, urbanization and depleting forest cover across top 5 most populas countries have impacted the change in temperature in these 5 countries.

### Libraries Used
  - pandas
  - numpy
  - matplotlib

To install the above packages using pip, use command
```$pip install package-name```

### Files Description
- CC_data.csv: This is the dataset file for the project
- Data is downloaded from http://archive.ics.uci.edu/ml/datasets/credit+approval
- CreditCardApproval.ipynb: The jupyter notebook which includes the analysis and modeling

### Usage
  - Run the jupyter notebook CredictCardApproval.ipynb

### Summary
In this project, I have tried to find out the factors that are most important for getting an 
approval for the credit card through the power of Data Analysis and Machine Learning. 
Though we have achieved 86% of accuracy, we also tried to check if we can improve the 
performance further and tried grid search. 
However, 86% is the best we could get from this data using both the model; 
logistic regression and random forest
