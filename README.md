# Project Description:

## A jupyter notebook will focus mainly on the following parts:

<ol>
    <li>Create a Ticker class that represents a ticker, retrieves daily prices, and computes common indicators such as EMAs, MACD, signal lines, and RSI.</li>
    <li>Plot the prices and EMAs for analysis, as well as the MACD versus signal line, and the RSI.</li>
    <li>Develop a stochastic model class based on data and chart analysis.</li>
    <li>Run multiple Monte Carlo simulations using the stochastic model and perform a final analysis using statistics and indicators like the Sharpe ratio.</li>
</ol>

---

## To view the work open the monte_carlo_sim.ipynb notebook.
## In order to run your own testing on the notebook, follow the set up steps:

1.    Run the following command in the root of the project folder:  ```python -m venv venv ```


2.  Activate the newly created python venv: ```source .venv/Scripts/activate ```

3.  Install all required dependencies: ```pip install -r requirements.txt ```

4.    Set up Jupyter Notebook kernel: ```python -m ipykernel install --user --name=venv --display-name="Random Name Here"```

5.    Open Jupyter Notebook: ```jupyter notebook```

---

## To run your own ticker example, follow these three simple steps:


1. Add your ALPHA VANTAGE API KEY to a .env: ```cp .env.example .env ```

    Then replace the example string with your API key

2. Under the cell that has a #Set ticker symbol comment, change the ticker string to the ticker you want to run the analysis on. 

3. Run all cells and wait for the result.
