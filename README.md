# Communicate Data Findings (Data Exploration & Visualization)
Udacity Project
# Child Mortality Rate Exploration

## Dataset
The data was a set if information gathered from 167 countries between 2000 and 2017. It consisted data of child mortality rate, basic sanitation access, life expectancy, immunization reach, adolescent fertility rate, and so on. The final data had 2987 rows and 11 columns. The data consisted of three parts: one gotten from an earlier project (originally from gapminder.org), additional datay downloaded from gapminder and the third from Kaggle. They were merged toform a final dataframe. The data used for this project can be found here: [https://classroom.udacity.com/nanodegrees/nd002-ent/parts/c785f82a-bb1d-471e-91a1-3ddb0851db3d/modules/df3ef87d-55e5-4461-a743-323c8a9a8911/lessons/6b41e57c-9270-413b-b713-c6b2ec207b04/concepts/642ab657-197e-4beb-afd6-4494e6da490b],
[https://www.gapminder.org/data/], [https://www.kaggle.com/taniaj/world-bank-country-and-lending-groups]

## Summary of Findings

In the exploration, I found that Child mortality rate had a strong positive relationship with adolescent fertility rate and a strong negative relationship with life expectancy, sanitation, and immunization. Urban population had a moderate negative correlation while employment rate had a very weak correlation with child mortality rate.

For the categorical variables, I observed that income category had a negative relationship with child mortality. Child mortality was high in low income areas and low in high income areas. I also noticed certain regions largely had high child mortality rates and interestingly these areas were low income regions. High income regions experienced the reverse.


## Key Insights for Presentation

For the presentation, I tried to display plots from the three different section that could better present the relationships I observed. I started by displaying the histogram distribution of the principal variable - child mortality rate on a log transformed axes.

Next, I presented plots of the numericalvariable with categorical variables. The trend could easily be observed from it.The ordinal variable had a negative relationship with child mortality rate. Also, the sub-Saharan Africa Region for instance, associated with the low income category had high mortality rate. the reverse was for North America.

Finally the plot of life expectancy, sanitation, and child mortality rate plotted on a log transformed scale depicted well the observed trend. Appropriate labels and titles were attaged to the plots.


## References

[https://classroom.udacity.com/nanodegrees/nd002-ent/parts/c785f82a-bb1d-471e-91a1-3ddb0851db3d/modules/df3ef87d-55e5-4461-a743-323c8a9a8911/lessons/6b41e57c-9270-413b-b713-c6b2ec207b04/concepts/642ab657-197e-4beb-afd6-4494e6da490b]
[https://www.gapminder.org/data/]
[https://www.kaggle.com/statchaitya/country-to-continent]
[https://www.kaggle.com/taniaj/world-bank-country-and-lending-groups]
[https://www.kaggle.com/burhanykiyakoglu/infant-mortality-fertility-income-eda]
[https://www.geeksforgeeks.org/log-transformation-of-an-image-using-python-and-opencv/]
[https://stackoverflow.com/questions/52024425/how-to-do-antilog-in-numpy]
[https://stackoverflow.com/questions/48734388/valueerror-cannot-index-with-multidimensional-key]
[https://stackoverflow.com/questions/52024425/how-to-do-antilog-in-numpy]
