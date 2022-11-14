
# 3D printing cost calculator with automatic price list updating

A python program that calculates the costs and prices of different products made with a 3D FDM printer. 
Once finished the calculations, the product´s information can be saved in an excel file that contains a table with the list of products. Instead of updating every single good of
the list manually, the program has a menu with an option to update three differents lists (price list, raw materials list, supplies list). 
The update of the costs of the raw materials and supplies are made by scraping the prices from Mercadolibre or by getting the inflation rate of the previous month. When this is done, it updates
the price list.


## How it works
To determine the cost of a 3D print I take into consideration the following variables:

- 3D printing time.
- Material quantity. 
- Type of Material and brand.

![](costo-pieza.png)

There are some costs that rely on the previous variables and others that are independent.




 

 
