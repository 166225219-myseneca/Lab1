# Lab 1 repository

A function that takes an input from the user and calculate someone’s age.
```
import datetime

def calculate_age():
    current_year = datetime.datetime.now().year
    birth_year = int(input("Enter your birth year: "))
    age = current_year - birth_year
    return age

# Example usage
user_age = calculate_age()
print("Your age is:", user_age)
```
One more Function:
```
def helloWorld():
	print(‘Hello World’)


helloWorld()
```
Try and except statement to your script.
The except statement be for a type error and should say “Please enter an int”

```
try:
birth_year = int(input("Enter your birth year"))
current_year = 2023 # Replace with actual current year
age = current_year - birth_year
print("Your age is:", age)
except TypeError:
print("Please enter an integer for the birh year.")
```