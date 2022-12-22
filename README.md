# SI100b-Python-Statistics-Project

# Relationship between Economics and Food industry
## Background
### Food industry shed light on the Economy
> There is a Chinese idiom saying '民以食为天'. The price of food can somehow show the **living standards** of the mass. How much are they related to a country's **economic** condition or the people's living condition? Different institutes have published many indices based on different products, finding the most proper item to indicate the social development. Such as **Tall Latte index** from Starbucks coffee, **Big Mac Index** from the McDonald's. Later there are **iPod index**, **IKEA's Billy bookshelf Index** etc.

### Big Mac Index
> The Big Mac Index is a price index published since 1986 by The Economist as an informal way of measuring the purchasing power parity (PPP) between two currencies and providing a test of the extent to which market exchange rates result in goods costing the same in different countries. It "seeks to make exchange-rate theory a bit more digestible." The index compares the relative price worldwide to purchase the Big Mac, a hamburger sold at McDonald's restaurants.<sup>1</sup>
### 10 Most valuable quick service restaurant brands worldwide
In the late 2021, these are the most valuable quick service restaurant brands worldwide.<sup>2</sup>
And without losing universality, we choose the first 6 brands whose values are more than 10 billion U.S. dollars. 
| Rank    |       Brand name      | Value  (billion $)  |
|  ----   | ----                  | -----               |
| 1       |     McDonald's        |       15.4921       |
| 2       |        Starbucks      |        6.0267       |
| 3       |        KFC            |        1.8189       |
| 4       |       Subway          |       1.4762        |
| 5       |     Domino's Pizza    |       1.2397        |
| 6       |        Chipolto       |       1.1996        |
    
## Introduction
From the table above we can see McDonald's is absolutely the most competitive. The price of Big Mac is choosen to reflect the Theory of Purchasing Power Parity(PPP). That is the purchasing Power can be shown by particular item's price. Is the Big Mac the best one that fit the theory. We decide to try other items in McDonald's and try to find how other food agree with the GDP.

There are drawbacks of the Big Mac Index since it is a lighthearted guide of economy:
(1) People in different countries or regions has different eating habits, so we cannot just focus on one single item.
(2) The price of Big Mac is affected by the **price law**, **tariffs**, **taxes** etc. In addition, pricing may also vary due to **trade barriers** between countries. Hence the index cannot be regarded as an accurate economic indicator.

To tackle the problem, we target at the United States only, and research on the index of each **State**. This method abates the influence mentioned in (1), and can somehow show the living standards among America. 

### Research Method
We have apply a spider to help us to get the data. And plot them by python package.


## Body
### The McDonald's Index
Now, let us begin the journey! 
 
Though the Big Mac Index always serves as a indicator of the purchasing power of a country's currency, we can still use the information to analysis the food cost in different States.  
In this period, we have crawled the regular recipe in whole U.S.A.(Happy Meals,$1$2$3 Menu, Sauces, Limited Time Offers are not included) <sup>3</sup>
And choose some of them to take the place of Big Mac. Making index by new food and compare them with the GDP of each state.

Regarding the popularity, and from the 10 Bestselling McDonald’s Menu Items, we choose these items to be index. <sup>4</sup>

Double cheeseburger(2 cheeseburger)

Filet-O-Fish

Bacon Ranch Salad

Apple slices

French Fries

Premium McWrap Chicken & Bacon (Grilled or Crispy)

Shake (Chocolate, Vanilla, or Strawberry)

Cone (Vanilla)

McFlurry

And do not forget our hero---the **Big Mac**
### The PPP of each State

Here we plot the scatter plot with the x-axis showing the price of the goods and y-axis showing the GDP of each states. It is obvious that the more a point adjacent to the bottom left corner, the more difficult people in this state to afford to buy this food. In the opposite, the life tend to be easier for the people who live in the State whose point is near the top right corner.

### The Relationship with the Election Results

Can the Index somehow show the States' political stance? May "Red" or "Blue" have some similarities with the index? With the Midterm election coming to an end, we have the data about how much a party controls a State---the approval ratings of the candidates from different parties. We plot the results in the form of quotient of the proportion of the Democrats(D) and the Republican(R). The information was provided by the Associated Press(AP).and we have it from the Guardian.<sup>5</sup>  

## Conclusion 


## Reference 

<sup>1</sup> [Wikipedia](https://en.wikipedia.org/wiki/Big_Mac_Index)

<sup>2</sup> [Statista] (https://www.statista.com/statistics/273057/value-of-the-most-valuable-fast-food-brands-worldwide/)

<sup>3</sup> [Fastfood/McDonald's] (https://www.fastfoodmenuprices.com/mcdonalds-prices/)

<sup>4</sup> [McDonald's Best Selling] (https://www.rd.com/list/bestselling-mcdonalds-menu-items/)

<sup>5</sup> [2022 Midterm Statemap](https://www.theguardian.com/us-news/ng-interactive/2022/nov/15/house-election-results-2022-live-senate-us-midterm-state-map-latest-winners-congress))
