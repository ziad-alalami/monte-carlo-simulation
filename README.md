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

<ol>
    <li>Run the following command in the root of the project folder
        ```bash
            python -m venv .venv 
        ```
    </li>
    <li>
        Activate the newly created python venv
        ```bash
            source .venv/Scripts/activate
        ```
    </li>
    <li>
        Install all required dependencies:
        ```bash
            pip install -r requirements.txt
        ```
    </li>
    <li>
        Set up Jupyter Notebook kernel:
        ```bash
            python -m ipykernel install --user --name=.venv --display-name="Random Name Here"
        ```
    </li>
    <li>
        Open Jupyter Notebook:
        ```bash
            jupyter notebook
        ```
    </li>
</ol>
---

## To run your own ticker example, follow these three simple steps:

<ol>

<li>Add your ALPHA VANTAGE API KEY to a .env:
    ```bash
        cp .env.example .env
    ```
    Then replace the example string with your API key
</li> 

<li>
    After almost 4 cells in the notebook, change the ticker string to the ticker you want to run the analysis on. 
</li>

<li>
Run all cells and wait for the result.
</li>

</ol>

