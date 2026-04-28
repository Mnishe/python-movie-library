# Python Movie Library Database

A console-based movie management application built with Python. This program allows users to interact with a local movie database stored in a `.csv` file. 

*Note: The application interface is currently in Polish.*

## Features
* **CRUD Operations:** Create, Read, Update, and Delete movie records directly from the console.
* **Data Parsing:** Reads, modifies, and saves data to a local `filmy.csv` file using Python's built-in `csv` module.
* **Search & Filter:** Find movies by title, director, actor, release year, or genre.
* **Sorting & Pagination:** Sort the library by various attributes and navigate through results using a custom pagination system.
* **Rating System:** Add user ratings and dynamically calculate the average score for each movie.
* **Error Handling:** Built-in safeguards for missing files, incorrect data types, and open-file conflicts.

## Technologies Used
* Python 3
* `csv` module (Data manipulation)
* `rich` library (Console progress bars)
