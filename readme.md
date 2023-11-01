##################
Password Validator
##################

This program checks if a password is according to a specific policy or not. It shows a message to tell you if there is a problem.

*************
How it Works:
*************

When you type your password, it runs the validatePassword() function. This checks somethings:

Is the password between 8 and 16 letters and numbers?
Does it have letters and at least one digit?
Is there a word you can find in the dictionary?
First it looks at the length of the password. If it's less than 8 or longer than 16, it gives an error in red text. Then it checks for letters and numbers using regex. If it's missing one, it gives another error. It splits the password into parts separated by digits. It sends the both sides of the digit to the dictionary API to see if it's a real word. If so, error message. At the end, if no problems, it shows a "Password is valid!" message in green.

***********
How to run:
***********

Open the password validator.html file in a web browser and type a password. if there is a red message, try another one.

