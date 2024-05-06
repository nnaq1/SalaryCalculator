## Salary Calculator

This is a simple Java application that calculates the salary of an employee based on the hourly rate and hours worked.

## How it works

The application prompts the user to input their hourly rate and the number of hours they've worked. It then calculates the total salary based on these inputs. If the hours worked exceed 40, the exceeding hours are considered as overtime and are paid at a rate of 1.5 times the normal hourly rate.

## Code Structure

The main class of the application is `SalaryCalculator` located in the package `com.mycompany.salarycalculator`.

Here's a brief overview of the `SalaryCalculator` class:

- `main(String[] args)`: This method starts the application. It asks for user input (hourly rate and hours worked) and then calculates and prints the total salary.

- `calculateSalary(double hourlyRate, double hoursWorked)`: This method calculates the salary. It computes the base salary and adds any overtime pay if applicable.

## How to run the application

You can run the application by executing the `SalaryCalculator` class. Ensure you have Java installed in your system.
