Experiment No. 5

Aim : To study and implement decision-making statements in C++.

Tools Required : Visual Studio Code (VS Code)

Theory:

Decision-making statements allow the program to make decisions and execute different code blocks based on conditions.

Types of Decision-Making Statements in C++:

1.if Statement:

Executes code if a condition is true.

syntax:

if (a > b) { cout << "a is greater"; }

2.if...else Statement:

Executes one block if condition is true, another if false.

syntax:

if (num % 2 == 0) { cout << "Even"; } else { cout << "Odd"; }

3.else if Ladder

Multiple conditions can be checked in sequence.

syntax:

if (marks >= 90) { cout << "Grade: O"; } else if (marks >= 80) { cout << "Grade: A+"; } else { cout << "Fail"; }

4.Nested if Statement

An if or else if inside another if.

syntax:

if (a > b) { if (a > c) { cout << "a is greatest"; } }

5.switch Statement

Replaces multiple if...else for checking a single variable.

synatx:

switch(day) { case 1: cout << "Monday"; break; case 2: cout << "Tuesday"; break; default: cout << "Invalid"; }

6.break Statement

Used to exit from a loop or switch block.

7.default Keyword

Executes when no case in switch matches.

Conclusion:

By completing this experiment:

You learned to control the flow of execution in a C++ program using if, else, else if, and switch statements.

You implemented condition-based logic to check for even/odd, maximum number, and menu selections.

These decision constructs are essential for implementing logic in real-world applications.
