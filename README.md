# Password Manager

A simple password manager application built with Python and Tkinter. This app allows users to securely store their website credentials (including website URL, email/username, and password) and retrieve them when needed. It also provides a password generator feature to create strong and random passwords.

![pw-manager](https://github.com/szabolcsjenei/password-manager/assets/131205642/dcc2913e-c8e8-42e6-9845-48db821b115f)

## Features

- Store website credentials (URL, email/username, password).
- Generate strong passwords.
- Automatically copy passwords to the clipboard.
- Retrieve saved passwords for websites.

## How to Use

1. Clone this repository:
   
   `git clone https://github.com/szabolcsjenei/password-manager.git`

2. Navigate to the project directory:

   `cd password-manager`
   
4. Install dependencies:
   
   `pip install pyperclip`

5. Run the app:

   `python main.py`

6. Use the "Add" button to save website credentials.
7. Use the "Generate Password" button to create strong passwords.
8. Use the "Search" button to retrieve saved passwords for websites.


## Data Storage

The app stores website credentials in a JSON file named `data.json` in the project directory.

## Requirements

- Python 3.x
- Tkinter library (included in standard Python installations)
- Pyperclip module (for copying passwords to the clipboard)
