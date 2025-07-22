📌 Features
Takes user's name and age (in years) as input

Calculates:

Total months lived

Total days lived (including leap years)

Outputs the results in a readable format

Uses the built-in time and calendar modules

📂 How It Works
Prompts the user for their name and age.

Determines the current date using the time module.

Calculates the total number of:

Years (direct input)

Months = years × 12 + current month

Days = sum of days in all years and months lived

Leap years are handled accurately using calendar.isleap.

Make sure you have Python 3 installed. Then run:
python calculator.py
🧠 Notes
This script does not use the exact birthdate; it assumes you were born on the same day and month as today.

The calculation is an approximation for days, based on whole years and months.
