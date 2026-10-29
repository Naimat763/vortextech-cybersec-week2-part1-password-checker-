# Python Password Strength Checker

**Program:** Python Password Strength Checker  
**Learning Track:** Vortex Tech Academy — Cybersecurity Internship  
**Task:** Week 2, Project 1

## Overview

A beginner-level Python command-line project that evaluates sample passwords using a small set of defined rules.

## Features

- Checks whether the password has at least 8 characters.
- Checks uppercase and lowercase letters.
- Checks for digits and special characters.
- Flags sample common passwords such as `123456`, `password`, and `qwerty`.
- Assigns Weak, Medium, or Strong ratings according to the project's rules.
- Displays feedback for missing checks.
- Uses Python `getpass` to hide password input in an interactive terminal.

## Technologies

- Python 3
- Python standard library: `getpass`

## How to Run

1. Install Python 3.
2. Open a terminal in this project folder.
3. Run:

```bash
python3 password_checker.py
```

4. Enter a sample password when prompted.
5. Review the rating and feedback.

## Testing

Tested with sample inputs covering common passwords, short passwords, passwords missing special characters, and passwords that satisfy the basic checks.

## Security Note

This is an educational demonstration, not a production-grade password security system. Its common-password list is small, and its rating is based on simple rules. Do not use real account passwords for testing.

## Learning Outcome

Practiced Python functions, strings, conditional logic, password checks, hidden terminal input, and basic test-case validation.
