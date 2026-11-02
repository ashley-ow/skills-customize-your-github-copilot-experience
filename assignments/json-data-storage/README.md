# 📘 Assignment: Persisting Data with JSON

## 🎯 Objective

Build a beginner-friendly Python program that saves a small collection of books to a JSON file and loads it again later. You will practice working with lists and dictionaries, reading and writing files, and using Python's built-in `json` module.

## 📝 Tasks

### 🛠️ Save a Book Collection

#### Description
Create a collection of books and save it to a file named `books.json` so the data can be used after the program exits.

#### Requirements
Completed program should:

- Store at least three books in a list of dictionaries, with each book containing a title and author.
- Use the built-in `json` module to write the collection to `books.json`.
- Open the file with a `with` statement and format the JSON with an indentation of at least two spaces.
- Create valid JSON that can be opened as a text file.

### 🛠️ Load and Display Saved Books

#### Description
Read the collection back from `books.json` and display each book's title and author in a readable format.

#### Requirements
Completed program should:

- Open `books.json` with a `with` statement and load its contents using `json.load()`.
- Display every saved book's title and author.
- Confirm the loaded collection contains the same books that were saved.

### 🛠️ Update and Save the Collection

#### Description
Add a new book to the saved collection, write the updated collection back to the file, and check that it is still there after restarting the program.

#### Requirements
Completed program should:

- Add a book with a title and author to the collection loaded from `books.json`.
- Save the updated collection to `books.json` using `json.dump()`.
- Load the file again after restarting the program and confirm the new book is present.
