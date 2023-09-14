# Supermarket sales Data Exploration


## Dataset

The growth of supermarkets in most populated cities are increasing and market 
competitions are also high. The dataset is one of the historical sales of 
supermarket company which has recorded in 3 different branches for 3 months 
data. Predictive data analytics methods are easy to apply with this dataset.

Source kaggle: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales


## Summary of Findings

In the univariate exploration i found that the unit price adn rating were both 
in a uniform distribution, the total and cogs and gross income were right skewed, 
i used the log scale on them, thir shape were unimodal with one peak in the middle. 
For the categorical variables of the data, Branch, City, Customer type, Gender, 
Product line, and payement methods, their types were just similar, females = males, 
member = normal, and so on...

In the Bivariate exploration i used the heatmap and the scatter plots for the 
numerical variables, there was different correlatiopns and patterns in the data, 
rating has a weak correlation with the other variables, so it doesn't impact 
the prices or the costs or the income, it doesn't impact the sales, the gross 
income, cogs, total and tax have a powerful correlation whic is 1, and they depend 
on quantity sold and price.Then i looked for the relationship between the numerical 
and the categorical variables, there was no differences they values were so 
close, only the Branch C has more profi a little bit.

In the Multivariate Exploration i made a visualization for the relationship between 
the quantity and the gross profit for each branch, the quantity as a positive impact 
on the gross profit for each Branch, since we are interessted more on the categorical 
variables i made a categorical visualization, In general Female gender seems profitable 
for all the branches, but there is not huge difference between the genders, the payement 
methods in the branch A are similar and the credit card and Ewallet are popular, however 
in the Branch C the credit card is not popular than Ewallet and cash, but in the Branch B 
the Credit card is popular and the Ewallet in not. For the customer type Member or Normal 
customer, both of them can realise huge profit for the branches, there is no huge difference 
but just a little bit, members can realise high profit in the Branch A and B.

And finally the main conclusion, The Health and Beaty, Home and life style realize 
the best sales for the Branch B, Food and beverages, sports and travel for the branch C, 
and Home and life style, fashion and accessories, sports and lifestyle for the branch A, 
however the sales of food and beverages are too small in the Branch A.


## Key Insights for Presentation

In this investigation i aimed to see the characteristics that can make sales 
and profit for each branch of the market, i'm interessted in the gross profit 
and it's relationships with the oher features, and the categorical features that
can make profit for each branch.

I started by introducig the variable of interest, i made a visualization of 
its distribution using the histogram to visualize both the raw and the log 
scale of the data, then i made a scatter plot to visualize the relationship 
between the gross income and the unit price and  the quantity for each branch,
after that i made a scatter plot to visualize the impact of the customer type
on the gross profit, then a pointplot to visualize the impact of the gender and 
the impact of the payement method on the gross income, finally i made a boxplot 
to visualize which product line is profitable for each branch.

