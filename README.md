# Data-Store-Task

This program is a Python application built using the Tkinter library. It provides a graphical user interface (GUI) for storing and displaying user data (Name and Age) in a table format. The data is also saved persistently in an Excel file using the openpyxl library.

Features:
Input Name and Age through a user-friendly GUI.
Display entered data in a table format using ttk.Treeview.
Save data persistently in an Excel file.
Automatically initialize an Excel file if it does not exist.

Usage:
Enter the Name and Age in the provided text fields.
Click the Save button to add the data to the table and save it to the Excel file.
View the stored data in the table displayed in the application.

File Handling:
The program uses class_work2.xlsx as the default file for storing data.
If the file does not exist, the program initializes a new Excel file with the required structure.

Code Explanation:
The initializeExcel function checks for the existence of the Excel file and creates it if not found.
The save_data function retrieves user input, adds it to the table, and appends it to the Excel file.
The tableInsert function inserts the input data into the table widget.
The GUI is built using Tkinter widgets like Label, Entry, Button, and Treeview.

Example Workflow:
Launch the program.
Enter Name: John Doe, Age: 25.
Click Save. The data will appear in the table and will be saved in class_work2.xlsx.
