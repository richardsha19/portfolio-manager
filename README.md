# portfolio-manager

This project is a robo-advising portfolio manager that selects stocks from a csv file for the user based on the safest portfolio present within the stock (that is, the value of the portfolio does not change much over time). 

To do this, we will taking data metrics from all the stocks in the csv file such as the correlation bewteen the stocks and the beta between the stocks and the market. The portfolio manager will then output the stocks that it chooses onto a csv file at the end so that the user can easily read the stocks that it chooses.