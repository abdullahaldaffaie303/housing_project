# Project Description:


Analyzing house sales in King County to built a model to predict house values


## Data 


House Sales from:

1. King County house sale prices 
2. King county grade system

## Key Findings

### How renovation might affect the estimate value of a home 
### And by what dollar amount ?


Looked into the data from king county, built the first modle to predict house
prices using all the columns from the data as my base model.started cleaning 
the data by getting rid of outliers and got rid of some of the columns i thought 
not useful to answer my questions. R squared dropped significantly Pvalues we good. 
for my third model i made zipcode dummies and added back some of the columns i dropped for model2.The R squared now is more than 80% and it shows high coefficient between 
price and the condition of the home and renovation.

Here are our key findings:


- The better condition the home in the more value
- Renovation homes is highly recommended
- Renovation increased the value by $18,680

**recommendations**


- Renovate home before listing
- Consider adding a bathroom as part of renovating

![condition_price](c.png)

![condition&Price.png](attachment:condition&Price.png)

### How does the official king county home grade affect the value ?


Looked into the data from king county, built the first modle to predict
house prices using all the columns from the data as my base model.started 
cleaning the data by getting rid of outliers and got rid of some of the 
columns i thought not useful to answer my questions. R squared dropped 
significantly Pvalues we good. for my third model i made zipcode dummies 
and added back some of the columns i dropped for model2.The R squared now 
is more than 80% and it shows high coefficient between price and the grade
the home received through the county system.

Here are our findings:


- Higher grade increase home value.
- Homes with grade of 9 and above increased in value by ≥ $73,310

**Recommendation**


 Factor in the king county grade when pricing home because you can price 
the home higher based on a grade of 8 or above

![grade_price](g.png)

![Grade&price.png](attachment:Grade&price.png)

### How much will adding a bathroom increase the value?


Looked into the data from king county, built the first modle to predict
house prices using all the columns from the data as my base model.started 
cleaning the data by getting rid of outliers and got rid of some of the 
columns i thought not useful to answer my questions. R squared dropped 
significantly Pvalues we good. for my third model i made zipcode dummies 
and added back some of the columns i dropped for model2.The R squared now 
is more than 80% and it shows high coefficient between price and the number
of bathrooms the house has.

Here are our findings:


- Bathrooms has a positive correlation with the price
- Adding one bathroom increase home value by $17,820
- Homes with more than 6 bathrooms not desirable the price reflect that

***Recommendation***


- Renovate home before listing
- Consider adding a bathroom as part of renovating
- Factor in the king county grade when pricing home because you can price the 
  home higher based on a grade of 8 or above

![Bathroom&price.png](attachment:Bathroom&price.png)


```python

```
