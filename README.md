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