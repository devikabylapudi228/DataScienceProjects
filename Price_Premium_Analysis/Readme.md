SUMMARY:


Use case for housing data is to assess how individual property features, such as a garage, contribute to property value. Approach is to evaluate the impact of these features across various locations and neighbourhood contexts i.e;By adding a garage for the non-garage house and predicting the resale value of that house in each area by location.


The benefit is it provides real estate stakeholders with insights to better understand and capitalize on features that add premium value.


Process:

l Calculated Price per sqft and converted them into 20 bins.

l Then applied KNN classifier with longitude and latitude as inputs.

l Accuracy with KNN classifier is 90.78%.

l Then converted bedrooms and bathrooms as rooms.

l Plotted Scatter plot showing the Average Sale Price by Longitude and Latitude. By the we can say that most houses are concentrated in one particular area.

l In those houses we can see there are less houses without garages.

l If we add a garage to the house and see how much resale value increases for that house.


KNN Regressor:

l Model: Use KNN regression with garage, longitude,latitude,lot_acres,rooms,category_price_per_sqft,year_built as features.

l Goal: Quantify the average price premium added by a garage across different neighborhoods.

l By KNN regressor calculated R2 and MAE errors.

l We get R2 best output.

l Plotted the Learning Curve for the KNN Regressor with eta=1e-6 and epochs=3e5.
