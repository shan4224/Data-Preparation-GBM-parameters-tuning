### Data-Preparation-GBM-parameters-tuning

##### Data preparation, munging . GBM parameters Tuning .

Train data consist of 87020 observations and 26 features.
Feature Engineering done to produce additional features.
Test data consist of 37717 observations.

Problem Statement: Digital arms of banks today face challenges with lead conversion, they source leads through mediums like search, 
display, email campaigns and via affiliate partners. Here Bank faces same challenge of low conversion ratio. 
They have given a problem to identify the customers segments having higher conversion ratio for a specific loan product so that 
they can specifically target these customers.

The points to be noted while working on this dataset :

1.	When a high-cardinality categorical variable like “city” or “state” is given, merge all rare levels.

2.	Label Encoding and One Hot encoding helps to extract latent features.

3.	Missing values can be imputed by median or other methods . Those observations can be tagged by creating new feature.

4.	Use dates to extract day, day of week, month, quarter, year and create new features from them.
