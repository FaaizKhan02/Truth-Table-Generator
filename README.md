# Truth-Table-Generator
Its basically a truth table generator program in java which generate input truth table,Evaluate diffrent statement of diffrent truth table and truthtable quiz which ask questions and also give grading in end to check your knowledge.
CODE EXPLANATION:
This program is a Truth Table Generator that serves multiple purposes: displaying truth tables, evaluating logic gate operations, and running a logic gate-based quiz game. The program uses Java's Scanner class to handle user input and provides a console menu to navigate its three primary functionalities.

Printing Truth Tables: The program includes methods for each logic gate (e.g., And, Or, Not, etc.), which output a hardcoded truth table for the corresponding operation. The printTruthTable method presents a menu to select a logic gate and calls the respective method based on the user's choice using a switch statement.

Evaluating Logic Gates: The evaluateLogicGates method allows the user to interactively compute the output of various logic gates. Based on the user's menu selection, it prompts for input values (e.g., "True" or "False") and computes the result using conditional checks (if-else) to simulate gate behavior.

Truth Table Game: The truthTableGame method quizzes the user on logic gate operations. The game has three difficulty levels (Easy, Medium, Hard), each posing a set of predefined questions about the behavior of logic gates. The user's answers are checked against the expected results, and their score is displayed at the end of each round.

The main method serves as the entry point. It provides a top-level menu allowing users to select one of the three features or exit the program. The program uses try-catch to handle input exceptions, ensuring the user experience is robust. Methods like printTruthTable, evaluateLogicGates, and truthTableGame are called in response to the user's main menu selection. The program uses multiple switch statements and nested conditional checks for logic gate operations and menu navigation. Overall, the code combines hardcoded outputs, interactive evaluation, and a gamified quiz to educate users about logic gates and truth tables.
