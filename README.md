# Lab-5-



When changing the value of top_k in Item_Name_reduced:
For top_k = 3, the model showed lower accuracy because many items were grouped into "Other".
For top_k = 5, the accuracy improved as more important item categories were preserved.
For top_k = 6, the accuracy slightly improved or remained stable.
In terms of feature importance:
Price-related features such as Total_Price and price_per_item remained among the most important.
Item_Name_reduced features became more influential as top_k increased.
