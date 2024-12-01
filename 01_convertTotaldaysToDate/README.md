Date Calculator in C++
This C++ program allows users to input a specific date (day, month, year) and calculate a new date by adding a specified number of days to it. It handles leap years, different month lengths, and provides the resulting date after adding the given number of days.

Features
Input: The program prompts the user to enter a specific date (day, month, year).
Leap Year Calculation: The program correctly accounts for leap years when calculating February days.
Date Calculation: The program can add a user-defined number of days to the input date and output the resulting date.
Month Days Handling: It correctly handles varying days in months, including February (28 or 29 days depending on the year).
How It Works
The user is asked to input a year, month, and day.
The program calculates the total number of days from the start of the year to the given date.
The user is then prompted to input the number of days to add.
The program computes the new date after adding the specified number of days, handling month changes and leap years as needed.
Finally, it displays the new date in the format DD/MM/YYYY.
Requirements
A C++ compiler (such as GCC or Clang)
Basic C++ standard libraries
How to Use
Clone this repository to your local machine.
Compile the program using your preferred C++ compiler.
bash
Kodu kopyala
g++ -o date_calculator main.cpp
Run the compiled program:
bash
Kodu kopyala
./date_calculator
Follow the prompts to input the date and the number of days you wish to add.
Example
Sample Run:
yaml
Kodu kopyala
Enter a Day: 15
Enter a Month: 8
Enter a Year: 2023
Enter total days to add : 
100

Date for [100] is: 24/11/2023
Functions
readYear(): Reads a year from the user and returns it as a short integer.
readMonth(): Reads a month from the user and returns it as a short integer.
readDay(): Reads a day from the user and returns it as a short integer.
isLeapYear(short year): Checks if a given year is a leap year.
numberDaysInMonth(short month, short year): Returns the number of days in a given month and year.
totalDaysFromTheBeginYear(short day, short month, short year): Calculates the total number of days from the start of the year to a given date.
addDayToDate(short totalDays, stDate date): Adds a given number of days to a specific date and returns the new date.