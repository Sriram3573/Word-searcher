
![Screenshot (212)](https://github.com/user-attachments/assets/bbb7eb8e-2518-4983-8ff8-136c3c836b10)
![Screenshot (213)](https://github.com/user-attachments/assets/fc528fc5-e89e-43d1-8050-2029cace7983)
![Screenshot (214)](https://github.com/user-attachments/assets/005c8fb2-d75d-4071-ab5c-1878a8ccd7ba)
![Screenshot (215)](https://github.com/user-attachments/assets/853a2e1b-5bd1-4378-bcf1-80ffcd658d99)
![Screenshot (216)](https://github.com/user-attachments/assets/32414606-57ef-48b2-a37e-aa4e779cfc62)


**Word-searcher**

Imports:

The script imports necessary modules such as tkinter for GUI creation and messagebox for displaying messages. Tkinter Setup:

A Tkinter window named "Word Search Game" is created. Labels and entry widgets are used to prompt the user to enter the number of rows and columns for the word search grid. Solution Class:

The Solution class contains a method named exist, which searches for a given word in a 2D board (grid) of characters. This class uses a recursive depth-first search (DFS) approach to find the word. Grid Creation and Validation:

Functions are defined to create the word search grid based on the user's input for the number of rows and columns. Validation functions ensure that the user inputs valid row and column values. Word Search Functionality:

The search_word function is triggered when the user clicks the "Create Grid" button. It validates the grid dimensions and the entered word. It then searches for the word in the grid using the exist method from the Solution class. If the word is found, a message box displays a success message along with the path of the word in the grid. If not found, it displays a message indicating the absence of the word. GUI Layout:

The GUI elements are organized using labels, entry widgets, and buttons to create a user-friendly interface for the word search game setup. Main Loop:

The Tkinter event loop (mainloop()) is started to run the GUI application, allowing users to interact with the interface.
