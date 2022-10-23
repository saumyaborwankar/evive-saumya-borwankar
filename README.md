# evive-saumya-borwankar
# **Menu Ordering System**

This repository contains code for Evive Engineering Take Home Assignemnt. Used Python to make the menu ordering system. Every file contains comments for better understanding.
I have included a few of my rules to the existing rules:
1. For Dinner you cannot order more than 1 side   
2. For Dinner you cannot order more than 1 main  
3. For Dinner you cannot order more than 1 dessert  
4. For Dinner you cannot order more than 1 drink  

## Requirements
1. Python3.6 or higher
2. Unittest: Unittest module used for testing python code. Inbuilt in python3
3. Pyinstaller: If you want to convert py files to executables on your end ```pip3 install pyinstaller``` (The executable is already provided in dist/menu/)

## Source Code:
1. menu.py: This python file contains the entire source code for the menu ordering system

If you want to run the code:  ```python3 menu.py```

If you want to use the executable file:  ```./dist/menu/menu```

The executable was made with the help of Pyinstaller using: ```pyinstaller menu.py```

## Tests:
1. test.py: This python file contains 16 test cases for the source code.

To run this ```python3 -m unittest test.py```



