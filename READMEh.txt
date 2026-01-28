1.Project Title and Goal
Password Strength Regex Tester- A python utility that validates password complexity using security-focused rules and reports pass/fail results.

2.Setup Instructions
#No external libraries required
python main.py

3.The Logic

Why did i chose this approach
I used a function-based approach with regular expessions because regex is ideal for enforcing security rules like character types and length.It keeps the validation logic compact,readable,and easy to extend

Hardest Bug I faced and,How did I fix it
The trickiest part was correctly detecting special characters without accidently including letters or numbers.I fixed this by explicitly defining a regex character class that matches only non-alphanumeric symbols

4.Output Screenshots

password validation output
output screenshots in screenshots file


5.Future Improvements

If I had 2 more days i would
1.Add uppercase and lowercase requirements
2.Convert the script into a CLI tool that accepts user input
3.Generate a detailed failure reason for each invalid password
4.Add unit tests forautomated verification