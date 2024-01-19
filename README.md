# NU-aly6140-mini-project-parking-problem
Car Parking Slot Availability Checker

Develop a simple program to manage Car parking slot availability near Downtown Portland. The program should allow users to check whether a parking slot is available or not.

1. check_availability(available, slot_number): Check if the given slot_number is available. Return True if the slot is available, otherwise return False.

2. park_car(available, slot_number): If the given slot_number is available, mark it as occupied and return a message indicating successful parking. If the slot is not available, return a message indicating unavailability.

3. Create a ParkingArea class with a specified number of total parking slots. Implement a loop that repeatedly prompts the user for a slot number and performs the following: If the slot is available, ask the user if they want to park a car there. If yes, call the park_car method and print the corresponding message. If no, display a message indicating the slot is available. If the slot is not available, print a message indicating that the slot is occupied.
