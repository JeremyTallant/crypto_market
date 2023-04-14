# Exploring the Bitcoin Cryptocurrency Market
## Description
To better understand the growth and impact of Bitcoin and other [cryptocurrencies](https://en.wikipedia.org/wiki/Cryptocurrency) we will, in this project, explore the market capitalization of different cryptocurrencies.

**Warning: The cryptocurrency market is exceptionally volatile, and any money you put in might disappear into thin air. Never invest money you can't afford to lose.**
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **Bitcoin and Cryptocurrencies: Full dataset, filtering, and reproducibility:** Load the saved CSV file and select relevant columns.
2. **Discard the cryptocurrencies without a market capitalization:** Filter out the coins with no known market capitalization.
3. **How big is Bitcoin compared with the rest of the cryptocurrencies?:** Visualize the market capitalization of the top 10 cryptocurrencies.
4. **Making the plot easier to read and more informative:** Make the plot from the last task more informative with colors and a nice log scale.
5. **What is going on?! Volatility in cryptocurrencies:** Create a DataFrame that contains volatility information on cryptocurrencies.
6. **Well, we can already see that things are *a bit* crazy:** Make a bar plot that shows the biggest gainers and the biggest losers.
7. **Ok, those are... interesting. Let's check the weekly Series too.:** Call the function we created in the last task above, but with the weekly data.
8. **How small is small?:** Use the `.query()` method to select all large cap coins in cap.
9. **Most coins are tiny:** Group *large*, *mid* and *small* cap coins into a group called *biggish* and make a barplot of counts of *biggish*, *micro* and *nano* coins.