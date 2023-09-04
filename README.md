## Practical Application No. 2 Summary

#### Overview
What drives the price of a car?  It's not to predict the price but to understand how the price
can increase or decrease depending on the used car features.

#### Dataset
This data comes to us from Kaggle repository.  No URL or means of collection was provided. The original 
dataset contained information on 3 million used cars. The provided dataset contains information on 426K 
used cars to ensure speed of processing. 

#### Data
The data directory contains dataset csv file from the Kaggle used cars subset.

## Summary of findings
The study to determine what drives the price of a used car was conducted using data 
of over 500,000 used cars. The data detailed region, manufacture year, manufactuerer, 
model, condition, cylinders, fuel, type, size, drive, transmission, title status, 
paint color, state, odometer, and price. The data had many missing values that weren't 
impediment to conduct the study.

The study included the analysis of the data using three (3) different models to cross 
validate results. Also, the analysis was done twice using first cars priced up to $500,000
and second cars priced up to $60,000.  The findings were consistent among both studies.

The key findings are:

The key features that increase the price

- 4wd and Rwd drive cars
- Pickup and Truck type cars
- Diesel fuel
- 8 cylinder engines
- Good Title Status

The key features that decrease the price

- Fwd Drive cars
- Gas and Hybrid Fuel cars
- Sedan, Wagon, Mini-Van, SUV Type cars

There is a possible upward trend in price for coupe and convertible type, with electric fuel. 
Odometer and Condition have impact (increase and decrease with the value) on the price as it 
was possible expected but are not key features.

## Next steps
The initial study focused on the overall data. No clustering analysis was done. The data set 
has enough information to perform more specific analysis for specific used cars market that 
can vary by state, region, type and size. 

The large MSE for all models also indicates an opportunity to explore other estimators that 
in conjunction with the clustering could produce lower model errors.

### Notebook URL
Study for cars up to $500,000
https://github.com/aegonzalezp/PracticalApp_2/blob/main/prompt_II_AlvaroGonzalez_rev1.zip

Study for cars up to $60,000
https://github.com/aegonzalezp/PracticalApp_2/blob/main/prompt_II_AlvaroGonzalez_rev2.zip

The Jupyter Notebooks were zipped to avoid the GitHub file limit of 100MB. 


