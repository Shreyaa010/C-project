Approach:
Let's discuss the approach in detail, covering all the functions and their explanation in detail-

1.Create a Menu in the main function and create different functions for the Menu, which will be called using switch case statements. There are four different functions-
   1.account()- This function is used to create a new account.
   2.transfermoney()- This function is used to transfer money to the account
   3.checkbalance()- This function is used to check the balance in the account.
   4.login()- This function is used to login into the account.
   
2.First, create an account of our user by calling the account() function after the creation of an account, store all the data into a file using file handling functions.
3.Then the user is able to transfer the amount to other users, for that transfermoney() function is called, and for checking the current balance in the account call checkbalance() function.# C-project

Implementation:

1. Create a Bank Account-
Take all the input from the user and make a structure for it to store the data in a file.

2. Transfer Money-
Take the username of another user to whom we want to transfer the money and open his record in the file and write the amount to the file.

3. Check Balance-
Opening a file in which all the transfer records are written and read them one by one and match the username passed in the function to fetch the correct transfer records.

4. Login Functionality-
To add Login functionality, we are opening the file and matching the username provided by the user at the time of registration, and logging in to him if the username is correct and matches with the record present in our file.

🗂 Step-by-Step Instructions
1. Create a folder and file
 ~Create a folder, e.g. BankSystemC
 ~Open it in VS Code:
File > Open Folder > BankSystemC
 ~Create a new file: bank_system.c
 ~Paste your full C code into it

2. Add a tasks.json file (optional but recommended)
 ~If you want one-click build/run:
   1.Create a .vscode folder inside your project
   2.Create a tasks.json file inside .vscode with:


🟢 Program Starts:
                       WELCOME TO BANK ACCOUNT SYSTEM

          **********************************
                    DEVELOPER-Naman kumar

           1.... CREATE A BANK ACCOUNT
           2.... ALREADY A USER? SIGN IN
           3.... EXIT

ENTER YOUR CHOICE.. 1

🔹 If You Choose Option 1 (Create Account):

!!!!!CREATE ACCOUNT!!!!!

FIRST NAME.. John

LAST NAME.. Doe

FATHER's NAME.. Robert

MOTHER's NAME.. Linda

ADDRESS.. 45ParkStreet

ACCOUNT TYPE.. Savings

DATE OF BIRTH..
DATE- 12
MONTH- 11
YEAR- 1992

ADHAR NUMBER.. 123456789012

PHONE NUMBER.. 9876543210

USERNAME.. johndoe

PASSWORD.. ********


✅ 3. Account Created Message


PLEASE WAIT....

YOUR DATA IS PROCESSING....

          ACCOUNT CREATED SUCCESSFULLY....

Press enter to login


✅ 4. Login Screen


           ACCOUNT LOGIN
********************************************************************

               ==== LOG IN ====

USERNAME.. johndoe
PASSWORD.. ********

LOGIN SUCCESSFUL....
Press enter to continue


✅ 5. After Login – Dashboard & Account Info


             WELCOME, John Doe
             ..........................

                         ==== YOUR ACCOUNT INFO ====
                         ***************************
                         NAME..John Doe
                         FATHER's NAME..Robert Doe
                         MOTHER's NAME..Linda
                         ADHAR CARD NUMBER..123456789012
                         MOBILE NUMBER..9876543210
                         DATE OF BIRTH.. 12-11-1992
                         ADDRESS..45ParkStreet
                         ACCOUNT TYPE..Savings

 HOME 
******
 1....CHECK BALANCE
 2....TRANSFER MONEY
 3....LOG OUT
 4....EXIT

ENTER YOUR CHOICES.. 2


✅ 6. Transfer Money


          ---- TRANSFER MONEY ----
          ========================

FROM (your username).. johndoe

TO (username of person).. janedoe

ENTER THE AMOUNT TO BE TRANSFERRED.. 1000

------------------------------------------------------------
------------------------------------------------------------
transferring amount, Please wait..
**********************************************************************
          AMOUNT SUCCESSFULLY TRANSFERRED....


✅ 7. Check Balance


==== BALANCE DASHBOARD ====
***************************

S no.     TRANSACTION ID       AMOUNT
1         johndoe              1000

TOTAL AMOUNT
1000


✅ 8. Logout


please wait, logging out..........
          Sign out successfully..
press any key to continue..


📁 Files Created:

~username.txt – stores user account details

~mon.txt – stores money transfer records





Thanks a Lot,

Project Leader

Shreya Soarhiya
