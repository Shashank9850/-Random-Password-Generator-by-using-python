# Shielded-Key-Maker
Developed a Python script to generate strong, random passwords with customizable parameters such as length, inclusion of special characters, and avoidance of ambiguous characters.

* It starts by importing the random module, which will be used to generate random characters for the password.
* It then prints out a welcome message and a line of equal signs to separate the welcome message from the rest of the output.
* It defines a string called chars which contains all the possible characters that can be used in the password. This includes lowercase and uppercase letters, 
  digits, and special characters.
* It prompts the user to input the number of passwords they want to generate (number) and the length of each password (length).
* It converts the user input from strings to integers using the int() function.
* It then prints a message indicating that it's going to generate passwords.
* It enters a loop that will run number times, generating a new password each time.
* Inside this loop, it initializes an empty string called Passwords to store the generated password.
* It enters another loop that will run length times, each time choosing a random character from the chars string and adding it to the Passwords string.
* Once the inner loop finishes, it prints out the generated password.
* The outer loop repeats until it has generated the desired number of passwords.
