# portfolio-manager

This project is a robo-advising portfolio manager that selects stocks from a csv file for the user based on the safest portfolio present within the stock (that is, the value of the portfolio does not change much over time). 

To do this, we will taking data metrics from all the stocks in the csv file such as the correlation bewteen the stocks and the beta between the stocks and the market. To choose the stocks that will remain in the portfolio, a point-weighted distributed system was used taking into account the standard deviation and expected return of each stock and the correlation between the stocks. The stocks with the highest total point accumulation will then be added to the stock, taking into account basic portfolio theory, such as diversification amongst the stocks, to minimize total risk. The portfolio manager will then output the stocks that it chooses onto a csv file at the end so that the user can easily read the stocks that it chooses.

#Libraries and Dependencies
- NumPy and NumPy Financial
- Pandas
- yFinance
- MatplotLib
- Threads
