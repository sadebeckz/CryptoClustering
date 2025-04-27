This project uses K-Means clustering and PCA to explore how cryptocurrencies group together based on their 24-hour and 7-day price changes.

First, I scaled the data, found the best number of clusters using the elbow method, and visualized the results.
Then I used PCA to reduce the data into fewer dimensions, re-clustered the cryptocurrencies, and compared the new results.

The goal was to see how using fewer features impacts how the cryptocurrencies are grouped.

All work was done in Python using pandas, scikit-learn, and hvPlot.

