# Octagon_Challenge2020
Winter hackathon 


# Octagon data science challenge 2020
## Data Transformation portion
#### A study was conducted between 2016-2019 containing users of the drug sorafenib, a TKI generally used in treating hepatocellular carcinoma. The raw data contained 2379 rows of information that were grouped data. For example, the first row indicated that there were two members from Alberta, regardless if the patient used another anti-cancer therapy concurrently, regardless of sex, between the ages 18-19.
#### Given that the goal of this challenge was to conduct survival analysis, this data was not suitable for such an analysis and had to be transformed into a usable format. The function IndividualLevelData1 converts data into induvidual level information, giving information about each participants province, age, concurrent treatment status, sex, and outcome of the trail.