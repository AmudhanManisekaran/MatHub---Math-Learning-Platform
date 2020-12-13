# MatHub - Math Learning Platform

## Features
- Interactive way to learn mathematics from level K-1 to K-8.
- Create, edit and remove student/parent/teacher profiles in database.
- Create assignment option and automated grading for teacher.
- Students can learn concepts such as:
	- Addition
	- Subtraction
	- Multiplication
	- Division
	- Power of n
	- Charts
	- Square root

## Basic System Requirements
- Programming Language: Python 3.5
- OS: Windows 10/Linux

## How to run?
- **Step 1:** `git clone https://github.com/san1197/MatHub-Math-Learning-Platform.git`
- **Step 2:** `pip install -r requirements.txt`
- **Step 3:** Start a terminal
- **Step 4:** In the terminal:
  - `cd MatHub-Math-Learning-Platform\src`
  - `python app.py`
- **Step 5:** Go to `localhost:3000`:
  - This will initialize the firebase based Database
  - Default admin username - `admin@mathub.com`
  - Default admin password - `admin` (SHA256 encrypted on firebase)
  - Example Student1:
    - Username: `yazhini@mathub.com`
    - Password: `s103_yazhini@mathub-com`to be updated
  - Example Student2:
    - Username: `sandya@mathub.com`
    - Password: `sandya@mathub-com`
  - When admin creates a new student, make sure to remember the ID displayed on creation, as that will be a part of the default password for that user. 
    - Default password format: `<lowercase ID>_<username, with -com replacing .com>`. See Example students for clarification.
