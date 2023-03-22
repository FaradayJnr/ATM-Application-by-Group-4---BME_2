# ATM-Application-by-Group-4---BME_2
Class Project ( Introduction to Programming(C)) - COE 251

The given C code contains a simple banking system that allows users to register, login, check balance, deposit, withdraw and transfer funds.

The program uses file handling to store user information in a text file named "users.txt". The user's information includes their username and password. A User struct is defined to store the username and password variables.

The global declarations of variables include balance, depositAmount, withdrawAmount, recipientNumber, amountToTransfer, choice, username and password.

The main function starts with a do-while loop which displays a menu of options to the user, including the ability to register, login or exit. If the user selects register, the program prompts the user to enter a username and password and stores the information in the "users.txt" file using the register_user function.

If the user selects login, the program prompts the user to enter their username and password. The authenticate_user function checks if the entered username and password match the information stored in the "users.txt" file. If the authentication is successful, the program displays a menu of options to the user. The user can choose to check their balance, deposit, withdraw or transfer funds. The login_user function handles these options.

The deposit function allows the user to deposit funds into their account, which increases their balance. The withDraw function allows the user to withdraw funds from their account, which decreases their balance. The transfer function allows the user to transfer funds to another account. If the user enters an amount greater than their balance, an error message is displayed.

The requestAmount function prompts the user to enter the amount they wish to withdraw and returns the amount.

Overall, the code provides a basic banking system that allows users to perform basic transactions.
