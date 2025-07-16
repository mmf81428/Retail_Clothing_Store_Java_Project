# Retail_Clothing_Store_Java_Project

# 🛍️ Clothing Store Console App (Java OOP Project)

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
Welcome to the Clothing Store!
Please enter your name:
John Doe

Are you a member? (y/n):
y

Hello, John Doe! As a member, you receive a 10% discount.
Available items:
1. Shirt - Blue - $25.00
2. Shirt - Black - $30.00

Select items to add to your cart...
