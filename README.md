## Python Toolbox

This repository is a collection of convenient methods and examples for novice data scientists or anyone who wants to use Python to analyse/visualize their data but found the abundance of libraries and functions a bit daunting. Here, we try to simplify the interface and provide some wrappers around existing libraries such as Pandas, Matplotlib, Seaborn, etc., setting the default values to the optimal and provide you more convenient options to manipulate the data and charts. With this little toolbox at hand, you would be able to easily:  

- Plot nice charts
- Get descriptive statistics
- More to come...

No more messy code! No more endless googling!
          
### Supported charts
Examples are shown in ![here](./notebook_examples/plotting.ipynb)
1. Histogram
`plot_hist(df.fare, x_label='Fare', y_label='Number of passengers', ub=200)`
![](./img/histogram1.png)

2. Cumulative Fraction Plot