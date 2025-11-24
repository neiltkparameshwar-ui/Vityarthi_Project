# Vityarthi_Project
# Project title: AIR TICKET RESERVATION

# Overview of the project: 
The main objective of the python project on Air ticket reservation is to manage the details of booking, payments, seats, and flights.
The project is totally built at administrative end and only administrator is guaranteed the access. 
The purpose of the project is to build an application program to reduce the manual work for managing the booking, discounts,  seats, and payments. 
It tracks all the details about seats,  flight, and payments; it also prints various reports as per input given by the 

# Features: 
1.	All the fields such as flight  payments discounts are validated and does not take invalid values.
2.	Each form of sales, discounts, bookings cannot accept the blank values.
3.	Avoiding errors in data.
4.	Controlling amount of input.

# Technologies/tools used: Python 3.x for the entire project, VS Code integrated, DBMS, Modular programming with multiple .py files for separation of concerns, Standard Python data structures                                      (dictionaries, lists) for in-memory storage

# Steps to install and run the project: 
1.Clone or download the repository to your local computer.
2.Ensure Python 3.13.7 and later version is installed. (Test with python --version)
3.Ensure DBMS app such as mysql is installed 
4.Navigate to the project directory in a terminal.

# Insturctions for testing: 
1. Environment Check
Ensure XAMPP/WAMP or MySQL server is running.
                            
Ensure you have installed the library: pip install mysql-connector-python or pip install pandas.

2. Test Case 1: User Registration
Action: Run the code. Select Option 1.

Input: Enter John Doe, New York, 12-12-2023, London, Paris.

Validation: Check your MySQL database (SELECT * FROM pdata;). You should see John Doe in the table.

3. Test Case 2: Booking a Ticket
Action: Select Option 3 (Ticket Price).

Input: Choose Class 1 (First Class), Passengers 2.

Validation: The system should print "Your Ticket Cost is = 12000".

4. Test Case 3: Ordering Food
Action: Select Option 5 (Order Food).

Input: Enter Choice 1 (Tea), Quantity 2.

Validation: The system should say amount is 20.

Action: Select Option 5 again. Enter Choice 5 (Sandwich), Quantity 1.

Validation: The system should add this to the total (Total food bill should now be 70).

5. Test Case 4: Luggage Calculation
Action: Select Option 6.

Input: Enter weight 5.

Validation: The system should calculate 5 * 1000 = 5000.

6. Test Case 5: Final Bill Generation
Action: Select Option 7.

Validation: verify the math.

Ticket (12000) + Food (70) + Luggage (5000).

Expected Output: Total Amount: 17070.





