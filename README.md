
# 3D printing cost calculator with automatic price list updating

A python program that calculates the costs and prices of different products made with a 3D FDM printer. 
Once finished the calculations, the product´s information can be saved in an excel file that contains a table with the list of products. Instead of updating every single good of
the list manually, the program has a menu with an option to update three different lists (products list, raw materials list, supplies list). 
The update of the costs of the raw materials and supplies is made by scraping the prices from Mercadolibre or by getting the inflation rate of the previous month. When this is done, it updates
the price list.


## How it works

### Menu
Everytime the python script (costo_piezas.py) is run, the following menu will show:

![](https://github.com/ferbonve/3D-Printing-Project/blob/main/images/menu.jpg)





### Costs calculations
To determine the cost of a 3D print I take into consideration the following variables:

- 3D printing time.
- Material quantity. 
- Type of Material and Brand.

![](https://github.com/ferbonve/3D-Printing-Project/blob/main/images/costo_pieza.jpg)


There are some costs that rely on the previous variables and others that are independent. 

Types of costs:

- Electricity cost (Depends on "3D printing time")
- Supplies costs (Supplies used for each print)
- Hotend lifetime cost (Depends on "3D printing time")
- Material cost (Depends on "Material quantity" and "Type of Material and Brand") 
- 3D printer amortization cost (Depends on the printer usage per year)
- Other costs (Light consumption, office cleaning, etc)

Return: 

![](https://github.com/ferbonve/3D-Printing-Project/blob/main/images/costo_pieza_return.jpg)

### Adding products to products list 

Menu


 
