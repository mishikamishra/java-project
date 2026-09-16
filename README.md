# Library Management System

A simple console-based Library Management System written in Java. It lets users add, view, search, issue, return, and delete books through a menu-driven interface, using ArrayLists to store book data in memory.

## Features

- **Add Book** – Add a new book with ID, title, and author.
- **View Books** – Display all books along with their availability status.
- **Search Book** – Search for books by title (partial match supported).
- **Issue Book** – Mark a book as issued using its ID.
- **Return Book** – Mark a book as returned using its ID.
- **Delete Book** – Remove a book from the system using its ID.

## Tech Stack

- Java (uses `java.util.Scanner` and `java.util.ArrayList`)
- No external libraries or database — all data is stored in memory and resets when the program exits.

## How to Run

1. Make sure you have Java installed (JDK 8 or above).
2. Save the code in a file named `Main.java`.
3. Compile the program:
```bash
   javac Main.java
```
4. Run the program:
```bash
   java Main
```

## Usage

On running the program, you'll see a menu like this:

```
1. Add Book
2. View Books
3. Search
4. Issue
5. Return
6. Delete
7. Exit
```

Enter the number corresponding to the action you want to perform, and follow the prompts.

## Example

```
Enter your choice: 1
Enter id: 101
Enter title: The Alchemist
Enter author name: Paulo Coelho
Book Added
```

## Notes

- Book data is **not persisted** — all books are lost when the program is closed.
- Search is case-sensitive and matches partial titles.
- This project is intended as a beginner-friendly exercise in Java fundamentals: loops, conditionals, and collections.

## Possible Improvements

- Add file or database persistence.
- Make search case-insensitive.
- Add input validation for duplicate IDs.
- Add sorting/filtering options in the view.

## License

Free to use for learning and personal projects.
