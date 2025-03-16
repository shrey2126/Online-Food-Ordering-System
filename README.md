# ONLINE FOOD ORDERING SYSTEM

## Description:
- A `Python-based` system to order vegetarian food with ease.
- Features: Menu browsing, order placement, cart management, and payment processing.

## Technology Stack:
- Programming Language: Python
- Libraries Used:  
`matplotlib`:  For visualizations (pie chart, bar chart).  
`datetime`:  For order date and time.  
`random`:  For generating order IDs.  
`os`:  For file handling (users and order history).
`re`:  For password validation.

- Data Storage:  
Text files (users.txt and order_history.txt) for storing user data and order history.

## Library Installation:
- matplotlib
```bash
pip install matplotlib 
```
## Essential Importing:
```bash
import matplotlib.pyplot as plt
import numpy as np
from datetime import datetime
import random
import string
import re
import os
```

## How it Works??
- `User Registration & Login`:  
-> Register with a username and strong password.  
-> Log in to access the system.

- `Menu & Ordering`:  
-> Browse the menu, search for items, and add them to the cart.

- `Checkout`:  
-> Apply discounts, choose a payment method, and generate a bill.

- `Order History`:  
-> View past orders and visualize spending patterns.
