# S&P 500 Stocks | Time Series Prophet Forecast Model

This program reads downloaded S&P 500 Stocks Data that you can find in the `archive` folder as `sp500_index.csv`. 
The dataset includes the stocks daily closing price for the last 10 years(`2013-2023`).

## Time Series Data Exploration 
Data is explored and analyzed per year `2022` and `2023`, it is also grouped by the last 5 years from `2018` to `2023`.

![bokeh_plot](https://github.com/Gespinoza10/time-series-data-sp500/assets/81205562/6827521a-a745-4be4-b558-06d37ba4de31)

![bokeh_plot (1)](https://github.com/Gespinoza10/time-series-data-sp500/assets/81205562/747a210f-dd49-45e1-850f-ba906ad79095)

![bokeh_plot (2)](https://github.com/Gespinoza10/time-series-data-sp500/assets/81205562/8e92aa74-a482-4ca5-b62f-f0569efd7bbd)

Data is also used to create a new feature in our dataframe `Return` that represents the stocks daily return. The program used `pandas` library `.diff()` function to calculate the daily retruns. 

![bokeh_plot](https://github.com/Gespinoza10/time-series-data-sp500/assets/81205562/3eecd2b8-4f0a-4ea4-b74e-949bb04208f0)

## Creating a Time Series Model with Prophet
