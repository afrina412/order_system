# order_system


# Food Ordering System

## Overview
This C++ program is a simple food ordering system that allows users to select items from a menu, specify quantities, and calculate the total cost. The program uses basic input/output operations and loops to manage user interactions.

## Features
- Displays a list of available food items with their prices.
- Allows users to select items by entering a corresponding number.
- Users can specify the quantity for each selected item.
- The program calculates and displays the total price.
- Provides input validation to ensure correct item selection.

## How It Works
1. The program starts by displaying a menu of food items along with their prices.
2. Users are prompted to enter the number corresponding to the food item they wish to order (1-5).
3. After selecting an item, users are asked to enter the quantity.
4. The selected item's price is multiplied by the quantity, and the total is updated.
5. Users can continue adding items or enter `0` to finish their order.
6. Once the order is complete, the program calculates and displays the total price.
7. The program formats the total price to two decimal places for clarity.

## Code Breakdown
### Menu Display
```cpp
cout << "Choose your food! " <<endl ;
cout << "chipsmore >> RM 3.00" <<endl ;
cout << "twisties >> RM 2.00" <<endl ;
cout << "potatoes >> RM 3.50" <<endl ;
cout << "milo >> RM 3.00" <<endl ;
cout << "twister orange >> RM 2.50" <<endl ;
