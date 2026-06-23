# Password Strength Checker

## Overview

This project is a Password Strength Checker developed using Python. It evaluates the strength of a password based on various security criteria and classifies it as Weak, Medium, or Strong.

## Features

- Checks password length
- Detects uppercase letters
- Detects lowercase letters
- Detects numbers
- Detects special characters
- Provides password strength rating

## Technologies Used

- Python 3
- Regular Expressions (re module)

## How It Works

The program analyzes a password using the following criteria:

1. Minimum length of 8 characters
2. At least one uppercase letter
3. At least one lowercase letter
4. At least one numeric digit
5. At least one special character

Based on these checks, the password is classified as:

- **Weak Password** (0-2 criteria met)
- **Medium Password** (3-4 criteria met)
- **Strong Password** (5 criteria met)

## Installation

1. Install Python 3.
2. Download the project files.
3. Open the project folder in VS Code.

## Run the Program

```bash
python password_checker.py
```

## Sample Output

### Example 1

**Input:**
```
12345
```

**Output:**
```
Password Strength: Weak Password
```

### Example 2

**Input:**
```
Password123
```

**Output:**
```
Password Strength: Medium Password
```

### Example 3

**Input:**
```
P@ssw0rd123
```

**Output:**
```
Password Strength: Strong Password
```

## Project Objective

The objective of this project is to help users create secure passwords and understand the importance of password security in cybersecurity.

## Author

Nikhita Kubade

CodeAlpha Cyber Security Internship