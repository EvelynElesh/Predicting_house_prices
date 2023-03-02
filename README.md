# Predicting_house_prices
The dataset used in this project is a housing dataset presented by De Cock (2011). The data came to him directly from the Ames City Assessor’s Office in the form of a data dump from their records system. The original Excel file contained 113 variables describing 3970 property sales that had occurred in Ames, Iowa between 2006 and 2010. However, so that the dataset could be used as a “layman’s” data set that could be easily understood by users at all levels he removed any variables that required special knowledge or previous calculations for their use. Most of these deleted variables were related to weighting and adjustment factors used in the city’s current modelling system.

The dataset contains 2930 records (rows) and 82 features (columns) and here, we find the description of the columns which will be used to predict our target column which is Sales Price i.e the amount the apartment or house sell for considering different conditions.

## Data Exploration
Firstly, we see the distribution of how homes are sold by neighbourhood versus the year it was sold.

This insight is also useful for home owners as well as Real Estate builders.
![image](https://user-images.githubusercontent.com/88746246/222375375-a8f2df47-26e5-46eb-836e-32ad39264189.png)
![image](https://user-images.githubusercontent.com/88746246/222375422-7760ddc2-dd25-444d-be8f-cb2fbc3ed941.png)

Here, we see a Histogram graph that shows the distribution of sale prices in the dataset. We can see from the plot that most house prices fall between 100,000 and 250,000.

Next we see the relationship between the size of the Living Area and the price of the property.

![image](https://user-images.githubusercontent.com/88746246/222375525-2a5bacd2-d986-4c85-96b3-e03483f608e1.png)

This plot shows that the larger the living area is, the higher the price of Sale.

To be able to understand the relationship between the columns, see below the plotted correlation map.

![image](https://user-images.githubusercontent.com/88746246/222375663-43581821-f08b-46a6-a2d4-e4d3d47a01c6.png)

There exist lots of positive and negative correlation. However, looking at the last row of the heatmap which is the target variable, it is highly positively correlated with Overall Qual and Gr Liv Area columns. It is also positively correlated with Year Built, Year Remod/Add, Mas Vnr Area, Total Bsmt SF, 1st Flr SF, Full Bath, Garage Cars, and Garage Area.

![image](https://user-images.githubusercontent.com/88746246/222375808-14cf06d1-af27-455c-b97d-00dd2d83bf99.png)

The plot above shows the relationship between the Year the property was built and how much it is selling for.


![image](https://user-images.githubusercontent.com/88746246/222375906-641ccea7-0925-40c1-a042-9cf81763d057.png)

The plot above shows the relationship between the Number of bedrooms and the sale price. This shows that more rooms do not necessarily mean more price.

Next, we query the dataset of the distribution of the overall quality of the property.

![image](https://user-images.githubusercontent.com/88746246/222375985-2281e881-98cd-43c5-bd69-4bb8584a6aae.png)

This plot shows that majority of the property has an overall quality of 4 to 8. This could also impart the price of sale.

![image](https://user-images.githubusercontent.com/88746246/222376278-4b9540c4-5202-4612-ba5a-2abc6366f504.png)

Querying the Garage type column in relationship with the Sale Price, we can see that an apartment/property having any type of garage increases the price. This insight is also good for intending property and real estate builders.




