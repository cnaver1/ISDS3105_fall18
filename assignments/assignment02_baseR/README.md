Assignment 2
================
Your name

The goal of this practice is to improve your understanding of vectors and how to manipulate them. The data we use are the prices of the [2017 Big Mac Index](http://www.economist.com/content/big-mac-index).

For each question, please create a new chunck with your reponse. Use narratives to comment the output whenever the question requires to do so.

1.  Edit the code below to assign country names to the vector `countries` and prices to the vector `prices`. Hide the code below when you knit (check the Rmarkdown cheatsheet to find the appropriate chunk option to hide code).

``` r
#countries
countries <- c("Argentina", "Australia", "Brazil", "Britain", "Canada", "Chile", "China", "Colombia", "Costa Rica", "Czech Republic", "Denmark", "Egypt", "Euro area", "Hong Kong", "Hungary", "India", "Indonesia", "Israel", "Japan", "Malaysia", "Mexico", "New Zealand", "Norway", "Pakistan", "Peru", "Philippines", "Poland", "Russia", "Saudi Arabia", "Singapore", "South Africa", "South Korea", "Sri Lanka", "Sweden", "Switzerland", "Taiwan", "Thailand", "Turkey", "UAE", "Ukraine", "United States", "Uruguay", "Venezuela", "Vietnam", "Austria", "Belgium", "Estonia", "Finland", "France", "Germany", "Greece", "Ireland", "Italy", "Netherlands", "Portugal", "Spain")

#prices in dollars
prices <- c(4.12553410932665, 4.527955, 5.10156757258139, 4.1114315, 4.6556967948218, 3.84409554461789, 2.9171270718232, 3.24360452925142, 4.00003493480292, 3.28139971386194, 4.60649054517816, 1.75398378529494, 4.4650245, 2.45791461307047, 3.20894752849616, 2.75723192502808, 2.40293204682299, 4.77333709927976, 3.36104723155846, 2.00302783277047, 2.75424026530641, 4.43226, 5.91416018925313, 3.56633380884451, 3.22927879440258, 2.64945182050953, 2.72339966564202, 2.27813538775693, 3.1998720051198, 4.06474559047688, 2.26073850791258, 3.84396977241952, 3.77297121483168, 5.81892070131244, 6.74168957112483, 2.26396522024444, 3.49624667636214, 3.00611009353896, 3.81159814865233, 1.69785838317577, 5.3, 4.52882773036056, 4.05555555555556, 2.63939293962389, 3.88263, 4.6248975, 3.5971425, 5.207292, 4.681995, 4.453605, 3.8255325, 4.6477365, 4.79619, 4.1224395, 3.7113375, 4.33941)
```

1.  Use `typeof()` to report the type of both vectors.

2.  Use `names()` to name the `prices` using `countries`. Show the first 5 values of your new vector

3.  Use `round()` to round the prices at the 3rd decimal. Overwrite `prices` with the rounded prices.

4.  Use indexing to report the prices for Canada, United States, Mexico

5.  Use inline code and the function `length()` to display the following sentence:

"The are x observations in the Big-Mac Index"

1.  Convert the prices from Dollar to Euro (1 Dollar = .83 Euro). In the narrative, comment about the property which allows you to combine a vector of length 1 (the exchange rate) with a vector of length 56 (the prices).

-   Could you use the vector `rep(.83, 28)` to do the same?
-   Could you use the vector `rep(.83, 112)` to do the same?
-   Would `rep(.83, 45)` also work? Why?

1.  In your narrative, mention that we are going to drop the 46th element. Use dynamic code to report the country that will drop.

2.  Overwrite the vector of prices with a new vector without observation 46. Use `length()` to make sure you have one observation less.

3.  Knit, commit and push to your GitHub repo `assignment`. Then submit the link to the *assignment folder* on Moodle.
