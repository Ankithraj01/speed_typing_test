# speed_typing_test

The Typing Speed Game is a Python program that measures the typing speed of a user. It generates a random sentence,
prompts the user to type it, and calculates the user's typing speed in words per minute (WPM). The program also
maintains a high score record for the user.

Explanation
The Typing Speed Game is a Python program that measures the typing speed of a user. It uses the tkinter module to
create a graphical user interface (GUI) with two windows. The first window prompts the user to start the game, while
the second window displays the sentence to type and the user's typing area.

The program reads a list of sentences from which it selects a random sentence. The user types the sentence in the
text area and clicks the "Submit" button to finish. The program calculates the user's typing speed in WPM and
compares it to the previous high score. If the user's score is higher, the program updates the high score record.

The program uses the timeit module to measure the time taken to type the sentence. It also uses the messagebox
module to display the user's score and the Label and Button classes to create the GUI.

