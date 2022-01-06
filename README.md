# Columbia_Fintech_Module2


# Project Title

This loan application program will create a list of qualifying banks that can provide loan

---

## Technologies

This project is written in python. The required libraries are as follows
fire ver 0.4, pathlib ver 2.3.6, sys version 20160418, questionary ver 1.10

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.

---

## Usage

This project has command line interface

Enter credit score, monthly debt and income, loan and market value when prompted. The program will identify of any available qualifying loans if any. Once identified, the program will prompt you to save the output. Enter the folder path only. In the folder path provided, the file named qualifying_loans.csv will be saved.

example 1

$ python app.py
? Enter a file path to a rate-sheet (.csv): C:\FinTech\Challenges\Columbia_Fintech_Module2\data\qualifying_loans.csv
? What's your credit score? 750
? What's your current amount of monthly debt? 2000
? What's your total monthly income? 7000
? What's your desired loan amount? 400000
? What's your home value? 600000
The monthly debt to income ratio is 0.29
The loan to value ratio is 0.67.
Found 1 qualifying loans
? Do you want to save the list of qualifying loans? Y
? Please enter folder for qualifying_loans.csv file? C:\FinTech\Challenges\Columbia_Fintech_Module2\data
(dev)
---

example 2
$ python app.py
? Enter a file path to a rate-sheet (.csv): C:\FinTech\Challenges\Columbia_Fintech_Module2\data\daily_rate_sheet.csv
? What's your credit score? 600
? What's your current amount of monthly debt? 3000
? What's your total monthly income? 7500
? What's your desired loan amount? 450000
? What's your home value? 600000
The monthly debt to income ratio is 0.40
The loan to value ratio is 0.75.
Found 0 qualifying loans
Sorry, but there are no qualifying loans
(dev)

example 3
$ python app.py
? Enter a file path to a rate-sheet (.csv): C:\FinTech\Challenges\Columbia_Fintech_Module2\data\daily_rate_sheet.csv
? What's your credit score? 750
? What's your current amount of monthly debt? 2000
? What's your total monthly income? 8000
? What's your desired loan amount? 400000
? What's your home value? 600000
The monthly debt to income ratio is 0.25
The loan to value ratio is 0.67.
Found 1 qualifying loans
? Do you want to save the list of qualifying loans? N
Thanks for your applicaiton. We look forward to serving you.
(dev)

example 4


## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
