# Sales Prediction Project
## Prediction of various food items sold at numerous outlet stores.

**Author**: Martisha Owens

### Business problem:

Help retailers understand the properties of products and outlets that play crucial roles in increasing sales.


### Data:
Big Mart Sales Prediction data from datahack.analyticsvidhya.


## Methods
- Followed along the model pipeline:
  - Dropped the Outlet_Size column due to an excessive amount of missing data.
  - Also dropped the Item_Identifier column do to it negatively affecting the OneHotEncoder result.
  - Used the median Simple Imputer to fill in the missing data for Item_weight.

## Results

#### Item Maximum Retail Price (MRP) v. Outlet Sales 
![sample image](https://github.com/Martishamao/Sales_predictions/blob/626a763dec7b85409ddacf50f3d48c0cd8272955/Item%20Maximum%20Retail%20Price%20(MRP)%20v.%20Outlet%20Sales.png)

> A couple take aways can be made, the first being the items with higher MRP has higher Sales. Also, the medium sized outlet have higher sales for each item while the Large outlets have lower sales for the similar item prices.

#### Average Revenue by Item

![sample_image](https://github.com/Martishamao/Sales_predictions/blob/626a763dec7b85409ddacf50f3d48c0cd8272955/Average%20Revenue%20by%20Item.png)

> The item with the highest average sales is Starchy Foods with an average Sale of $2,374.
## Model

  - Used Decision Tree to model data.

  - Report the most important metrics

## Recommendations:

![sample_image](https://github.com/Martishamao/Sales_predictions/blob/e33e4ae316a4968bdc5dd155f4dfbb53849c1512/Sales%20Heatmap.png)

> According to the heat map above, there are not much correlation between Item Sales and the other independent features. At most, a correlation could be evaluated for Item MRP. The regression tree also observed underfitting the data.  


### For further information


For any additional questions, please contact MartishaOwens@gmail.com
