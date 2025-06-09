Cafeteria Management System – C++ Console Application
Overview
The Cafeteria Management System is a console-based application developed in C++ that simulates a real-world cafeteria environment. It allows customers to place orders, calculates itemized bills, records customer information, and generates sales reports. This project serves as a practical example for implementing fundamental C++ programming concepts and is ideal for academic use and beginner-level practice.

Features
Menu Display: Presents a list of food items with corresponding prices.

Multi-Customer Support: Handles multiple customers in one program execution.

Order Management: Accepts item selections and quantities from customers.

Dynamic Billing: Calculates the total bill based on item prices and quantities.

Sales Reporting: Generates detailed weekly and monthly sales reports including total revenue and item-wise sales counts.

Customer Data Handling: Captures and logs customer names and phone numbers.

System Flow
1. Initialization
The program begins by asking for the total number of customers to be served.

2. Customer Interaction
Prompts each customer to enter their name and phone number.

Displays a menu with food items and prices.

Accepts item selections and quantities.

Calculates and displays the customer's total bill.

Offers an option to place additional orders.

3. Sales Summary
At the end of each customer session, the user can generate a Weekly or Monthly sales report showing:

Items sold

Total earnings

4. Repeat or Exit
The system allows the admin to continue serving more customers or exit the application.

Menu Items & Pricing
Item ID	Item	Price (Rs.)
1	Burger	250
2	Pizza	800
3	Fries	150
4	Tea	100
5	Sandwich	130
6	Samosa	40
7	Coffee	150

Technologies Used
Language: C++

Compiler: Any standard C++ compiler (e.g., g++, Visual C++)

Core Concepts:

Functions

Arrays

Structures (struct)

Loops and Conditional Statements

Standard Input/Output Operations

Getting Started
1. Clone the Repository

git clone https://github.com/your-username/cafeteria-management-system.git
2. Compile the Program
Ensure a C++ compiler is installed, then run:

3. Run the Program

Example Session:
yaml
Copy
Edit
Enter total number of customers: 2

Customer 1:
Enter name: Ahmed
Enter phone number: 03123456789

Menu:
1. Burger - Rs.250
2. Pizza  - Rs.800
...

Enter item: 2
Enter quantity: 1

Do you want to order more? (y/n): y

Your total bill is: Rs.800
Use Cases
Student Projects: A great assignment or practice system for students learning the basics of C++.

Demonstration Tool: Useful for explaining structured programming and console-based application design.

Practice System: Helps reinforce concepts like loops, conditionals, arrays, and modular functions.

Limitations
No Data Persistence: Data is not saved between runs; everything resets when the program ends.

Console-Based Only: There is no graphical user interface (GUI).

Basic Error Handling: Assumes valid numeric input in most cases; minimal input validation.

Acknowledgments
This project was created as part of a programming fundamentals course. It demonstrates how basic programming structures can be applied to simulate real-world systems in a beginner-friendly and educational context.
