# User System with JSON Storage

A Python program for user registration and login with data saved in JSON file.

## Features
- Register new users with:
  - Username
  - Password
  - Country (Canada, USA, Italy)
  - Random 4-digit User ID
- Login system with password check
- 3 attempts allowed for password
- If password fails 3 times, user must reset password
- Data stored persistently in `users_json.json`

## How to Run
1. Make sure you have Python installed (3.x).
2. Run the program in your terminal:

```bash
python user_system.py
Choose action:1_Register 2_Login 3_Exit: 1
Enter username: Arad
Enter password: 1234
Available countries: ['Canada', 'USA', 'Italy']
Enter country: Canada
Thanks
Registration successful!

Choose action:1_Register 2_Login 3_Exit: 2
Enter your username: Arad
Enter your password: 1234
Login successful!
