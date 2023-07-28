# Login_and_Registration_System_using_Python

## STAGE --> 1
### Registration:
### Email validation:
1) When the user chooses to Register
2) Email/Username should have "@" and followed by "."  eg:- 1] sherlock@gmail.com 2] nothing@yahoo.in
3) It should not be like this eg:- 1] @gmail.com
4) There should not be any "." immediate next to "@" eg:- 1] my@.in
5) It should not start with special characters and numbers
### Password Validation:
1) Password (5 < password length > 16).
2) Must have minimum one special character.
3) Must have minimum one numeric value.
4) Must have minimum one uppercase.
5) Must have minimumone lowercase character.
## Stage --> 2
1) Once the username and password are validated, store those values in a file.
## Stage --> 3
### Login:
1) When the user chooses to Login, check whether his/her credentials exist in the file or not based on the user input.
2) If doesn’t exist ask them to go for Registration or If they have chosen Forget password you should be able to retrieve their original password based on their username provided in the user input.
3) If nothing matches in your file you should ask them to Register.
