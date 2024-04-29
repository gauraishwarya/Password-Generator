# Password Generator
![image](https://github.com/gauraishwarya/Project-Images/blob/main/Password%20Generator.jpg)
## Objective:-
- ##### To create a random password generator using Python. 
## Modules needed:-
##### I) string – For accessing string constants. The ones we would need are –
1) string.ascii_letters:- The concatenation of the ascii_lowercase and ascii_uppercase constants described below. This value is not locale-dependent.
2) string.digits:- The string '0123456789'.
3) string.punctuation:- String of ASCII characters which are considered punctuation characters in the C locale: !"#$%&'()*+,-./:;<=>?@[\]^_`{|}~.
##### II) random – 
This module implements pseudo-random number generators for various distributions.
## Tech Stack Used:-
![Techstack](https://github.com/gauraishwarya/Project-Images/blob/main/python%20logo.png)
## Code Implementation:-
1) Import modules string and random.
2) Create lists of Characters, Digits and Special characters using string module.
3) Create empty list to store the password.
4) Allow user to enter the number if characters, digits and special characters they want.
5) Select random character, digits and special characters from list using random.choice().
6) Append the random selected character, digits and special characters into password list.
7) Now shuffle the password list to increase the password strength.
8) Now using loop store convert the password list into string and print.
![Output](https://github.com/gauraishwarya/Project-Images/blob/main/Password%20Generator%20output.jpg.png)
