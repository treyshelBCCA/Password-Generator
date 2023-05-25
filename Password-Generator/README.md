### Password Generator

I wanted to start making some practices to have a bit more of a real world feel. Most likely with any job you get, you will be working in an existing code base. I am hoping to start making small projects with the majority of the code written and have you complete bits and pieces of the code to make it work properly.

In this exercise, you will be asked to implement code to fix the mainLoop() function in the Generator.java file. Add your solution below the comment I left for you on line 20.

You will need to implement the code that calls the existing functions to make the program run properly. I have attached a screenshot of the flow of the program within the images folder of the project. Goodluck!


## Functionalities

### 1. Generating a Password:

- The user answers with "Yes" or "No" to questions about using uppercase letters, lowercase letters, numbers, or symbols.
- The user then enters the desired length of the password.
- A password alphabet is generated based on the user's answers, which is a string containing the chosen characters.
- Random characters from the password alphabet are selected and combined to form a completely random string according to the user's preferences.
- The randomly generated password is then displayed on the console.

### 2. Checking a Password's Strength:

The strength check is based on the following criteria:
- The password uses uppercase letters.
- The password uses lowercase letters.
- The password uses numbers.
- The password uses symbols.
- The length of the password is 8 or more (8 is often the minimum required length for a decent password).
- The length of the password is 16 or more (16 is considered to be the minimum length for a good password).

These criteria are used to calculate a score for the password, which determines the message displayed to the user indicating the strength of the password (weak/medium/good/great).

### 3. Displaying Useful Information:

This is a minor feature that displays information for the user on the console about password security, such as avoiding using the same password twice, avoiding character repetition, keyboard patterns, dictionary words, letter or number sequences, etc.