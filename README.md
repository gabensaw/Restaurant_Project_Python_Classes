# Restaurant Table Class
This repository contains the implementation of the Table class in restaurant.py, which represents tables of diners at a restaurant. The class provides methods for ordering items, removing items, calculating the subtotal and total cost, and splitting the bill.

## Assignment Description
The Table class has the following requirements:

1. It should instantiate objects representing tables with a given number of diners.
2. Each table should have an instance variable called bill, which is a list.
3. The class should include the following methods:
- `order(item, price, quantity=1)`: Adds a menu item to the bill. If an item with the same name and price already exists in the bill, it updates the quantity.
- `remove(item, price, quantity)`: Removes the specified quantity of an item from the bill. If the quantity reaches zero, the item is completely removed from the bill.
- `get_subtotal()`: Returns the total cost for the table based on the prices and quantities in the bill.
- `get_total(service_charge_percentage=0.10)`: Returns a dictionary with the subtotal, service charge, and total cost. The service charge percentage can be optionally provided.
- `split_bill()`: Calculates the subtotal cost of the bill divided by the number of diners, rounded up to the nearest penny.

## Usage
To use the `Table` class:

1. Clone this repository to your local machine.
2. Open the restaurant.py file and implement the Table class according to the assignment description.
3. Use the class methods to interact with the table objects, such as ordering items, removing items, and calculating the total cost.
4. You can test the functionality by running the script or writing test cases.

## Author
Gabriel Sawicki
