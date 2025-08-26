Student Management System
Overview
This is a simple, console-based Student Management System built in Java. It allows users to manage student records by performing operations such as adding, editing, removing, searching for, and displaying students. The system uses file I/O to save and load student data, ensuring that the information persists between sessions.

Features
Add Student: Add a new student with their name, roll number, and grade.

Edit Student: Update the name and grade of an existing student using their roll number.

Remove Student: Delete a student record using their roll number.

Search Student: Find a student's details by their roll number.

Display All Students: View a list of all students currently in the system.

Data Persistence: Student data is automatically saved to a file (students.dat) and loaded when the program starts.

How to Run
Compile: Compile the Java files.

javac StudentManagementSystem.java StudentManager.java Student.java

Note: If the code is in a single file, just compile StudentManagementSystem.java.

javac StudentManagementSystem.java

Run: Execute the main class.

java StudentManagementSystem

Class Structure
StudentManagementSystem.java: Contains the main method and the console-based menu interface.

StudentManager.java: Manages the collection of Student objects and handles file I/O for data persistence.

Student.java: A class representing a student with attributes like name, roll number, and grade. It implements Serializable for file I/O.

Number Guessing Game
Overview
This is a classic console-based number guessing game written in Java. The computer generates a random number between 1 and 100, and the user's goal is to guess the number in as few attempts as possible.

How to Play
The program will ask you to guess a number between 1 and 100.

Enter your guess at the prompt.

The game will tell you if your guess is "Too low!" or "Too high!".

Keep guessing until you correctly identify the number.

Once you guess correctly, the game will display a congratulatory message and show you how many attempts it took.

How to Run
Compile: Compile the Java file.

javac NumGame.java

Run: Execute the main class.

java NumGame

Student Grade Calculator
Overview
This is a simple Java program that calculates the total marks, average percentage, and final grade for a student based on their subject scores. It's a command-line tool that takes user input for the number of subjects and the marks for each.

How to Use
The program will first ask you to enter the number of subjects.

For each subject, it will prompt you to enter the marks.

After all marks are entered, the program will display:

Total Marks

Average Percentage

Final Grade (based on a simple grading scale)

Grading Scale
90-100: A

80-89: B

70-79: C

60-69: D

Below 60: F

How to Run
Compile: Compile the Java file.

javac StudentGradeCalculator.java

Run: Execute the main class.

java StudentGradeCalculator

ATM System
Overview
This is a basic console-based ATM (Automated Teller Machine) system developed in Java. It simulates common ATM operations such as checking the balance, depositing cash, and withdrawing funds.

Features
Check Balance: View the current account balance.

Deposit: Add a specified amount to the account.

Withdraw: Withdraw a specified amount, with validation to ensure sufficient funds.

User-friendly Interface: A simple menu-driven console interface for easy interaction.

How to Run
Compile: Compile the Java file.

javac ATMSystem.java

Run: Execute the main class.

java ATMSystem

Currency Converter
Overview
This Java application is a simple currency converter that uses a set of pre-defined, static exchange rates to convert an amount from one currency to another. It's a console-based tool that takes the base currency, target currency, and amount as input from the user.

Features
Static Exchange Rates: Uses a HashMap to store a few popular currency exchange rates (USD, EUR, GBP).

User Input: Prompts the user to enter the base currency, target currency, and the amount to convert.

Input Validation: Handles invalid inputs and unsupported currency pairs.

Formatted Output: Displays the converted amount with a clean, easy-to-read format.

How to Run
Compile: Compile the Java file.

javac CurrencyConverter.java

Run: Execute the main class.

java CurrencyConverter
