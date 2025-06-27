# Task4_NotesApp

#  Java Notes App – File I/O Project

This is a simple text-based Notes Manager built using Java. It allows you to write and read notes from a file using **FileWriter** and **BufferedReader**. You can keep adding notes and view them anytime by running the program — just like a mini note-taking app in your terminal.

---

## Project Objective

This project is part of a Java Developer Internship focused on learning **File Input/Output (I/O)** in Java. It demonstrates how to persist user data into files using Java classes.

---

## Features

- Add notes through console input
- Save notes to a `.txt` file using `FileWriter`
- Read all saved notes using `BufferedReader`
- Automatically creates the file if it doesn't exist
- User-friendly menu-driven interface

---

##  Technologies Used

- Java (JDK 8 or above)
- `FileWriter` and `BufferedReader` classes
- `Scanner` for user input
- Command Line / Terminal

---

##  File Included

- `NotesApp.java` – A single file containing all logic

---

## How to Run

1. Open terminal in the project folder.
2. Compile the program:
   ```bash
   javac NotesApp.java
3. Run the program
    java NotesApp

## Sample Output 
 Welcome to Notes App (Java File I/O)

--- Menu ---
1. Add Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Finish internship task 4
Note saved successfully.

Enter your choice: 2
Your Notes:
- Finish internship task 4

