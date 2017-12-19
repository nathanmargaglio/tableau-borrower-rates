
# Exploring Borrower Rates in Tableau

## Summary

https://public.tableau.com/profile/nathan.margaglio#!/vizhome/BorrowRates_v2/InfluencesofBorrowRates

We will be exploring and explaining borrower rates for loans using Tableau in order to show how variables related to individuals can increase or decrease the interest rates of loans they for which they apply.  This data set contains 113,937 loans with 81 variables on each loan, out of which we will be examining a small subset.  We used Tableau to create visualizations to clarify which variables might affect the borrower rate of a loan as well as to what degree.

## Design

Since our exploration focuses on borrower rates, the decision to limit the variables per point in our story to one or two was important.  This lets the reader clearly see how some factor influences the borrow rate without seeing unneccessary information.  When more variables are present, it is done in order to guide the reader to the possibility of multiple variables interacting simultaneously to affect the borrower rate.

In our exploration, we sometimes use categorical varibles to filter and color plots.  In order to reduce complexity of graphs and present the reader with only what is necessary, we limit these categories appropriately.  This not only makes the plots much easier to read, but also helps convey important insights into how those categories affect the borrower rate of a loan.

An important feature of this dataset is the number of variables present for each loan.  This comes at a cost of simplicity.  In order to properly convey the ideas that may be present in any particular variable, we have to take into account what data is actually present and how it trends.  This is why most of the charts are scatter plots with trend lines versus line charts.  This allows us to see not only how data trends in relation to a variable, but also the scarcity of data points in any given interval.  This makes many of the plots less misleading, especially towards outliers.

## Feedback

Originally, our visualization looked considerably different to what the final result is.  I offered the visualization to others and used their feedback to improve the workbook.  The original version can be found here:

https://public.tableau.com/profile/nathan.margaglio#!/vizhome/BorrowRates_v1/InfluencesofBorrowRates

One point of feedback was to consilidate the map of the United States to focus on the continental US and add Hawaii and Alaska afterwards.  This made the visualization much clearer and easier to use the hover feature to find specific borrower rates of states.

Another point of feedback was limiting categorical filters on plots to make them less messy and easier to read.  Some of the plots use various categories to color lines or points in order to convey the idea of these variables working in conjunction to influence the borrower rate.  By limiting these filters, and thus the colors, a much cleaer relationship can be seen between the variables as well as distinct differences between the categories that are being filtered against.

The biggest point of feedback that was recieved for these visualizations was the use of scatter plots and trend lines over line plots.  Although not appropriate in every scenario, replacing line plots with scatter plots provided much clearer insights for the same sets of variables.  Line plots tended to mislead the reader into thinking that some variables became more volatile and less predictable as you moved towards outliers.  By replacing these plots with scatter plots, the reader was able to see that it wasn't that these relationships became more volatile, but instead more scarce.  The addition of trendlines then helped reinforce the overall direction of the plots and relationships.

## Resources

Prosper Loan Data - Variable Definitions

https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0
