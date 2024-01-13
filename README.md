# CodeClauseInternship_Calculator_Task-2
"Calculator In Python Explanation"

1.Importing Libraries:
The code imports the Tkinter library for creating the GUI. The * in from tkinter import * imports all classes and functions from Tkinter.

2.Creating the Tkinter Root Window:
The Tk() function creates the main window. The title is set to "Simple Calculator", and the window size is set to 570x600 pixels with an offset of 100 pixels from the left and 200 pixels from the top.

3.Configuring Root Window:
This sets the window to be non-resizable and configures the background color.

4.Global Variables:
The variable equation is a global variable used to store the mathematical expression that the user inputs.

5.Functions:
This function is called when a numeric or operator button is pressed. It updates the equation variable and sets the text of the result label (label_result) accordingly.

6.clear() function:
This function is called when the "C" button is pressed. It clears the equation variable and updates the result label.

7.calculate() function:
This function is called when the "=" button is pressed. It attempts to evaluate the mathematical expression stored in equation using eval() and updates the result label. If an error occurs during evaluation, it sets the result to "error" and clears the equation.

8.Label Widget for Displaying Result:
A label widget is created to display the current mathematical expression or result. It is initially empty.

9.Creating Buttons:
Various buttons for digits, operators, and other functions are created using the Button widget and placed at specific coordinates within the window.

10.Running the Tkinter Event Loop:
This starts the Tkinter event loop, allowing the GUI to handle user inputs and events.
