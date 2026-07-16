Personal Information Manager Project Description 

This is my first Python project! It's a program that stores and displays personal information. 
What I Learned 
1. Variables: How to store different types of data
 2. Input/Output: Getting user input and displaying results
 3. String Formatting: Using f-strings to create nice output 
4. Error Handling: Basic validation for user input


Features 

•	Stores static information (name, age, city, hobby) 
•	Gets dynamic information from user (favorite food, color) 
•	Displays all information in a formatted way 
•	Basic input validation 
•	Age calculation in months


Setup Instructions

# Installation and Usage Guide

## Prerequisites

Before running this project, make sure you have the following installed:

- Python 3.10 or later
- A code editor (Visual Studio Code is recommended)
- Git (optional, for cloning the repository)

## Installation

### Option 1: Clone the Repository

```bash
git clone https://github.com/your-username/week1-personal-info.git
cd week1-personal-info
```

### Option 2: Download ZIP

1. Open the GitHub repository.
2. Click **Code**.
3. Select **Download ZIP**.
4. Extract the ZIP file.
5. Open the extracted folder.

## Project Structure

```
week1-personal-info/
│── personal_info.py
│── README.md
│── test_inputs.txt
└── .gitignore
```

## Running the Project

Open a terminal in the project folder and run:

```bash
python personal_info.py
```

If your system uses `python3`, run:

```bash
python3 personal_info.py
```

## Expected Output

```
Name: John Doe
Age: 22
City: Pune
```

## Using the Project

1. Open `personal_info.py`.
2. Edit the personal information if required.
3. Save the file.
4. Run the program using the Python command.
5. Verify that the output matches the expected result.

## Troubleshooting

### Python is not recognized

Check whether Python is installed:

```bash
python --version
```

If Python is not found, install it from the official Python website and ensure it is added to your system's PATH.

### File Not Found Error

Make sure you are in the correct project directory before running:

```bash
cd week1-personal-info
```

### Permission Denied

On Linux or macOS, you may need to use:

```bash
python3 personal_info.py
```

## Requirements

- Operating System: Windows, Linux, or macOS
- Python Version: 3.10+
- Internet Connection: Not required

# Siddharth Babu Mudul
# This is my first python project that stores and display personal information
# Welcome message
print("=" * 40)
print("    PERSONAL INFORMATION MANAGER")
print("=" * 40)
print()

# Store static information
name = "Alex Johnson"
age = 22
city = "San Francisco"
hobby = "playing guitar"

# Get user input
print("Please tell me about yourself:")
print("-" * 30)

favorite_food = input("What's your favorite food? ")
while favorite_food == "":
    print("Please enter a valid food!")
    favorite_food = input("What's your favorite food? ")

favorite_color = input("What's your favorite color? ")
while favorite_color == "":
    print("Please enter a valid color!")
    favorite_color = input("What's your favorite color? ")

# Calculate age in months
age_in_months = age * 12

# Display all information
print()
print("=" * 40)
print("        YOUR INFORMATION")
print("=" * 40)
print()

print(f"Name: {name}")
print(f"Age: {age} years ({age_in_months} months old)")
print(f"City: {city}")
print(f"Hobby: {hobby}")
print()
print(f"Favorite Food: {favorite_food}")
print(f"Favorite Color: {favorite_color}")
print()

# Goodbye message
print("=" * 40)
print("Thanks for using this program!")
print("=" * 40)

Algorithm flow of project

## Objective
Display the user's personal information on the screen.

## Algorithm Steps
1. Start the program.
2. Store the user's personal information (such as name, age, city, and email) in variables.
3. Read the values stored in the variables.
4. Display each piece of information in a clear and readable format.
5. End the program.

Flow

Start
   ↓
Initialize personal information
   ↓
Print Name
   ↓
Print Age
   ↓
Print City
   ↓
Print Email
   ↓
End





 



