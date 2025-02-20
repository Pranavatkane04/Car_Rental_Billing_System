# Car_Rental_Billing_System

## Overview
This program calculates the total rental fee for a car rental service. It considers different factors such as car type, number of rental days, membership discounts, optional insurance services, and late return penalties.

## Features
- Defines rental rates based on car type.
- Accepts user input for rental days.
- Applies membership discounts.
- Calculates additional service fees (insurance).
- Computes late return penalties.
- Generates a final rental summary with all calculations.

## How It Works
1. **Car Type Selection**
   - The user enters a car type: `Economy`, `Standard`, or `Luxury`.
   - The program assigns a daily rental rate based on the selection.

2. **Number of Rental Days**
   - The user inputs the number of rental days.
   - The program ensures that the value is a positive integer.

3. **Membership Discounts**
   - The user selects a membership type: `Premium`, `Standard`, or `None`.
   - Discounts are applied as follows:
     - Premium: 20%
     - Standard: 10%
     - None: No discount
   - The program calculates the adjusted fee after applying the discount.

4. **Optional Insurance Services**
   - The user chooses whether to add insurance (`yes` or `no`).
   - If `yes`, an additional $20 per day is added.

5. **Late Return Fees**
   - The user enters the number of days the car was returned late.
   - A late fee of $10 per late day is applied.

6. **Final Rental Fee Calculation**
   - The total rental fee is calculated as:
     ```
     Total Rental Fee = Adjusted Fee + Additional Services Fee + Late Penalty
     ```
   - A detailed rental summary is displayed.

## Example Output
```
Rental Summary
Car Type: Economy, Daily Rental Rate: $30/day
Rental Days: 2, Base Fee: $60.00
Membership: Premium, Adjusted Fee: $48.00
Additional Services Fee: $40.00
Late Penalty: $50.00
Total Rental Fee: $138.00
```

## Error Handling
- Invalid car types result in an error message and program termination.
- Rental days must be a positive integer.
- Invalid membership types result in an error message and program termination.
- Invalid responses for optional services result in an error message and program termination.

## Requirements
- Python 3.x

## How to Run
1. Save the script as `car_rental.py`.
2. Run the script in a terminal or command prompt:
   ```
   python car_rental.py
   ```
3. Follow the prompts to enter the required details.

## Author
Pranav Atkane

