# Super-Market-Billing-System-Python-Project-P12


## Project Overview

The **Supermarket Billing System** is a Python-based application designed to streamline the billing process in a supermarket. It processes multiple items, calculates total prices, applies discounts based on predefined conditions, and generates an itemized receipt for the customer. This interactive system is built to ensure accurate and efficient billing.

Design and implement a supermarket billing system using Python that effectively handles multiple billing functionalities. The system should allow for the input of multiple items, process their individual prices, and apply discounts where applicable. Using conditional statements and loops, the program should calculate the total bill, including any applicable discounts, and generate an itemized receipt for the customer. The system should be interactive and capable of handling real-time input, ensuring accuracy and clarity in the final output.
 
**Key Requirements:**

1. The system must allow for multiple items to be processed in a single transaction.
2. Conditional statements should be used to apply discounts based on criteria (e.g., total amount, item type, or promotions).
3. The program should calculate and display the subtotal, any discounts applied, and the final total amount due.
4. The itemized bill should display the name, quantity, price of each item, and the final total after discounts.
5. Loops should be utilized to handle continuous input of items until the billing process is complete.


## Features

- **Multiple Item Processing:** Allows users to input multiple items with quantities in a single transaction.
- **Discount Application:** Automatically applies discounts based on the total amount:
  - 5% for totals up to ₹500
  - 7% for totals up to ₹1000
  - 15% for totals up to ₹5000
  - 20% for totals above ₹5000
- **Itemized Receipt:** Provides a detailed receipt showing each item, price, quantity, subtotal, discount, and final total.
- **Customer Details:** Captures and displays customer name and phone number for each transaction.
- **Continuous Input:** Processes multiple transactions for consecutive customers in a single run.

## How It Works

1. **Customer Information:**
   - The system prompts for the customer's name and phone number.
   
2. **Item Selection:**
   - A list of available products and prices is displayed.
   - Customers enter the item name and quantity. The system calculates the subtotal and adds the item to the cart.
   
3. **Discount Calculation:**
   - The system applies discounts based on the total bill amount:
     - 5% discount for totals up to ₹500
     - 7% discount for totals up to ₹1000
     - 15% discount for totals up to ₹5000
     - 20% discount for totals above ₹5000

4. **Receipt Generation:**
   - An itemized receipt is generated, displaying:
     - Store information, date, and time
     - Customer name and phone number
     - Itemized details (name, price, quantity)
     - Total bill, discount applied, and the final bill after the discount

5. **Multiple Transactions:**
   - The program can handle consecutive customers in a single run, asking after each receipt whether there is another customer in the queue.

## Technologies Used

- **Python 3.x** for the core logic and implementation.
- **Datetime Module** for generating the current date and time on receipts.


