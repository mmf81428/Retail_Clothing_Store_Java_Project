# Retail_Clothing_Store_Java_Project

This is a console-based clothing store application built in Java using object-oriented programming (OOP) principles. Users can browse clothing items, add them to a cart, and simulate a checkout process. The application supports different customer types with varying benefits (e.g., Members and Guests).

---

## Features

- Object-oriented design using classes like `Customer`, `Shirt`, `Cart`, `Member`, and `Guest`
- `Member` customers receive special discounts or benefits
- `Cart` class manages shopping cart logic
- Inheritance and polymorphism used across customer types
- Simulates a basic checkout experience in the console

---

## Tech Stack

- Java 11+
- Console-based (no GUI)
- Pure object-oriented programming (OOP)

---

## File Overview

| File              | Description                                      |
|-------------------|--------------------------------------------------|
| `ClothingStore.java` | Main class that runs the application             |
| `Customer.java`      | Abstract base class for customers                |
| `Member.java`        | Extends `Customer`; represents store members     |
| `Guest.java`         | Extends `Customer`; represents guest users       |
| `Clothing.java`      | Base class for clothing items                    |
| `Shirt.java`         | Subclass of `Clothing`; represents shirts        |
| `Cart.java`          | Manages items added by the customer              |

---

## Getting Started

### Run the Program
1. Clone the repository
2. Open in Eclipse or your preferred Java IDE
3. Run `ClothingStore.java` as a Java application

---

## Sample Output

```bash

Menu:
1. View Clothing
2. View Cart
3. Exit
Select an option: 1

Select clothing type: 
shirts

Select color: 
red

Select size: 
medium

Select max price: 
30

Shirt 1:
Type: Shirt
Color: Red
Size: Medium
Price: $29.99

Would you like to add an item to the cart?
yes

Select item number: 
1

Item added to cart.

Would you like to return to the menu?
no

Would you like to proceed to checkout?
yes

Checkout: 
Do you want to checkout as a member or guest?
1. Member
2. Guest
2

Enter your first name:
Guest

Enter your last name:
One

Enter your address:
123 address

Enter your credit card number:
12345678

Your order details:

Items in Cart:
Type: Shirt
Color: Red
Size: Medium
Price: $29.99

Are you sure you want to purchase these items?:
yes

Order confirmed! Thank you for your purchase, Guest One
