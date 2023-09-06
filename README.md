# BMR Calculator

A simple javascript app to estimate Basal Metabolic Rate (BMR)

### Features

- [x] Calculate BMR by weight, height, age and gender.
- [x] Display daily calorie needs based on activity level.

### Activity Levels

- **Sedentary** - Little to no exercise
- **Lightly Active** - Exercise 1-3 days/week
- **Moderately Active** - Exercise 4-5 days/week
- **Very Active** - Hard exercise 6-7 days/week
- **Super Active** - Very hard exercise or physical job

### BMR Formula (Mifflin-St Jeor Equation)

**For Men:**
BMR = 10W + 6.25H - 5A + 5

**For Women:**
BMR = 10W + 6.25H - 5A - 161

Where:

- `BMR` is the Basal Metabolic Rate.
- `W` is the weight in kilograms.
- `H` is the height in centimeters.
- `A` is the age in years.

These formulas estimate the number of calories your body needs to maintain basic functions at rest. The result is used to calculate daily calorie needs based on activity level.
