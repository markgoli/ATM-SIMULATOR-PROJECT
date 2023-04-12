# bank-atm-system
Three-way modelling of a bank-Atm-system between a customer\user,a database and an operator.
I created it as a GUI app using tkinter with python.
works with python's tkinter from python version 3.0 above,not usable with python 2.x versions.

# how it operates (all files must be in the same directory)
The app is launched by running main.py file which in turn calls/executes other files. After launching this 
application, a GUI shows app, which prompts you to choose to continue either as "ADMIN" or "USER".
If you continue with "Admin(SysAdmin)", the admin root/default password is "1357", see through the database.txt file
which stores information concerning the bank, admin and normal users. 
# Note that this file is automatically created and updated when the admin runs the application to register new users.

This admin(SysAdmin)  is responsible for creating and adding in more users in the bank's database and each new user created is given a default password of "0000" which is changed or updated to a custom password when that particular user logs in to the system at the first time.

# The admin(SysAdmin) can do the following on a successful log-in.

    Deposit cash in ATM
    Check balance in ATM
    Register new user
    See user's infomation
    View all user's cash 
    Delete user Account 

# if you choose to continue with normal user.
The normal user is created by the admin(SysAdmin), and is given a default password which can be changed at first time to login to the system with their account_name and PIN as "0000". 

# On successful login, the normal user can do the following.

    Deposit Cash 
    Withdraw Cash 
    Balance inquiry
    Transfer Cash
    Change Pin
    Delete their account 
    Return Card 

# A few users were created including "User1":"1234", "User2":"2222", "User3":"3333" in the database.txt file during testing. Thank you. 

# ATM-SIMULATOR-PROJECT
