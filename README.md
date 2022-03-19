# Book Recommendations
Book recommendations for customers using the Bookshop dataset. 

The detailed visualizations and .twb files are also made available.

## Background:

I used the Bookshop dataset offered by Tableau to create a robust storyboard for identifying book recommendations, keeping the customer as the stakeholder.

The visualizations and storyboard were created using Tableau Desktop and published to Tableau Public.

* **Stakeholder:** Customers

* **Storyboard:** https://public.tableau.com/app/profile/viswanathan.jeyaraman.krishnamurthy/viz/shared/KBD422CKT

* **Data Source:** https://help.tableau.com/current/pro/desktop/en-us/bookshop_data.htm


## Points to Note:

1.	Used the appropriate Joins and Unions to form the relationships between the datasets and modelled according to the schema that was suggested in the dataset. 

2.	For the **Popularity** Dashboard, we use the **Most Popular Genre by Sales** visualization as a **Filter** to identify the most popular books in that specific genre. This allows customers to quickly identify the most popular books according to the genre they want to read.

![Popular Genre by Sales](/Diagrams/Most%20Popular%20Genres%20by%20Sales.jpg)

3.	Almost all the visualizations are filtered using the **Top N** parameter that allows the customer to filter out the Top 5 or Top 10, etc. in that specific dashboard/visualization as per their convenience. To accommodate the Top N parameter, we use multiple Title filters for enforcing this parameter. 

4.	The **Most Affordable Books by Price** visualization also categorizes the cheap books into the different formats (like Paperback, etc.) so as to get a better idea of the delivery format of the book. 

![Affordable by Price](/Diagrams/Most%20Affordable%20Books%20by%20Price.jpg)

5.	The **Most Popular Books by Checkout Trends** visualization uses **References Lines by Pane** to indicate the Average Checkouts for the specific month. 

![Popular by Checkout Trends](/Diagrams/Most%20Popular%20Books%20by%20Checkout%20Trends.jpg)


Extrapolating this using **Trend Lines**, we observe the R-squared and P-value for the Polynomial distribution seems to appropriately model the visualization. 

We are able to make this conclusion because of R-squared ~ 1 and the very low P-value (<0.001).