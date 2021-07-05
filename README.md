# jobs-frontend-dev
Repo for the Snapt frontend developer evaluation.

You may fork this repo and then submit your work when ready. The entire project should take you between 
2 and 6 hours depending on the effort required. 

Please note that we will only ask you to complete this if you are already in the late stages 
of our interview process.

## Avocado Prices

The Snapt development team has a keen interest in the price of avocados. 

We have provided a dataset in ```datasets/avocado.csv``` which will help you to analyze this avocado 
<del>robbery</del> price-fluctuation and it has the following fields:

```
Date - The date of the observation
AveragePrice - the average price of a single avocado
Total Volume - Total number of avocados sold
4046 - Total number of avocados with PLU 4046 sold
4225 - Total number of avocados with PLU 4225 sold
4770 - Total number of avocados with PLU 4770 sold
Total Bags
Small Bags 
Large Bags
XLarge Bags
type - conventional or organic
year - the year
region - the city or region of the observation
```

## The Task

The task is to create a dashboard to analyze the relevant data, specifically:
 - The price over time
 - How the volume affects the price
 - How conventional vs organic farming methods alter the price 
 - The various regions and their production

It should be interactive, graphical, and can be developed using any frontend stack you choose. We'll be looking for 
(among other things you decide to use): 
 - Interactive data selection, e.g. data tables, and so on.
 - Historical graphs and dashboard dials, metrics, etc. 


## Optional Extra Credit
These are entirely optional, but should you also feel the need to understand avocados like we do, you may also attempt to:  
 
 - Use the dataset provided to predict what the price of avocados is likely to be in the future.
 - Create a small backend to host the avocado dataset, and query it via API instead of directly from the csv.


### Credits

Dataset from Kaggle https://www.kaggle.com/smokingkrils/avacado-price-prediction
