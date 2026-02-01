# Ticket Booking Logic (Python)

A simple Python script that determines ticket eligibility and calculates the final price based on user age, membership status, seat type, and show time.

## 🚀 Features
* **Age Verification:** Checks if the user is old enough to book and attend evening shows.
* **Dynamic Pricing:** Calculates costs based on:
  * **Seat Type:** (Premium: 5, Gold: 3, General: 1)
  * **Extra Charges:** Added for evening shows or weekends.
  * **Discounts:** Applied for members over 21.

## 📊 Logic Flow
The program uses nested conditional statements to ensure a user only sees the final price if they pass all age and timing restrictions.



## 💻 Sample Calculation
**Inputs:** Base Price: 15, Age: 21, Seat: Gold, Time: Evening.  
**Result:** Final Price: 20
