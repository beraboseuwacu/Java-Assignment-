# Lab 1 Assignment - Java Programming

**Student Registration Number:** 225034054

---

## Problem 1: Bicycle Rental

### What the program does
This program calculates the total cost of renting a bicycle based on the starting hour and the ending hour entered by the user.

### How it works
- The user enters a **start time** (between 0 and 23) and an **end time** (between 1 and 24).
- The program loops through every hour of the rental.
- For each hour, it checks which rate range the hour falls into:
  - **0 – 7** and **21 – 24** → 500 RWF per hour
  - **7 – 14** and **19 – 21** → 1000 RWF per hour
  - **14 – 19** → 1500 RWF per hour
- It adds the correct rate to a running total.
- Finally, it displays the total rental cost.

### Key Concepts Used
- Loops (`for` loop)
- Conditional statements (`if-else if-else`)
- Methods (`getRate` method to return the rate per hour)
- Input validation using `Scanner`

### Sample Run
