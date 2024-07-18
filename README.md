
![Screenshot (215)](https://github.com/user-attachments/assets/fc736825-e267-45b6-98b3-c771c2a6808f)
![Screenshot (214)](https://github.com/user-attachments/assets/045302c1-ffdf-48b4-966a-a475f2f4ad1a)
![Screenshot (213)](https://github.com/user-attachments/assets/24eac3b0-85b7-4a70-af6a-f35bb69e48d1)
![Screenshot (212)](https://github.com/user-attachments/assets/4b461d95-7e88-4304-b316-41241943d50e)
![Screenshot (216)](https://github.com/user-attachments/assets/3e3ee2fb-032a-41ec-a82f-13516f8fb389)

**Word-searcher**
Imports:

The script imports necessary modules such as tkinter for GUI creation and messagebox for displaying messages. Tkinter Setup:

A Tkinter window named "Word Search Game" is created. Labels and entry widgets are used to prompt the user to enter the number of rows and columns for the word search grid. Solution Class:

The Solution class contains a method named exist, which searches for a given word in a 2D board (grid) of characters. This class uses a recursive depth-first search (DFS) approach to find the word. Grid Creation and Validation:

Functions are defined to create the word search grid based on the user's input for the number of rows and columns. Validation functions ensure that the user inputs valid row and column values. Word Search Functionality:

The search_word function is triggered when the user clicks the "Create Grid" button. It validates the grid dimensions and the entered word. It then searches for the word in the grid using the exist method from the Solution class. If the word is found, a message box displays a success message along with the path of the word in the grid. If not found, it displays a message indicating the absence of the word. GUI Layout:

The GUI elements are organized using labels, entry widgets, and buttons to create a user-friendly interface for the word search game setup. Main Loop:

The Tkinter event loop (mainloop()) is started to run the GUI application, allowing users to interact with the interface.
