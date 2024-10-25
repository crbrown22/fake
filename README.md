#Dragon Game

Simple Python program that allows you to create csv of fake random data to test in database

#Features:
Run Program /
Open csv file folder to retrieve data

#Usage:
To run the program: python fake.py

#Installation: 
git clone https://github.com/crbrown22/faker.git

#Contributing: 
If you want to contribute, please follow these steps:

Fork the repository 
Create a new branch 
Make your changes 
Submit a pull request

#Issues:
Will pull data and update data, however it does provide a error msg after pull.

created csv file:4.309304475784302
Traceback (most recent call last):
  File "C:\Users\User\OneDrive\Desktop\GitHub\faker\fake.py", line 57, in <module>
    qty_total, amount_total = get_totals()
                              ^^^^^^^^^^^^
  File "C:\Users\User\OneDrive\Desktop\GitHub\faker\fake.py", line 38, in get_totals
    with open('./files/invoices.csv', 'r', newline='') as csvfile:
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

FileNotFoundError: [Errno 2] No such file or directory: './files/invoices.csv'

#License:
 This project is licensed under the MIT License - see the LICENSE file for details.

#Acknowledgments: 
Thanks to everyone has contributed to make this project more fun and engaging

#Contact Information:
Christopher Brown - swolecode@gmail.com
