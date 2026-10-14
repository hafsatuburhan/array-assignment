# Student Grade Management System

## Description
The Student Grade Management System is a Python application that uses a list (array-like data structure) to store and manage student grades. It allows users to add grades, view all grades, calculate the average, highest and lowest scores and search for a grade by index.

## Features
- Add student grades
- Display all grades
- Calculate average, highest, and lowest scores
- Search for grades using indexes
- Simple menu-driven interface

## Technologies Used
- Python
- Jupyter Notebook

## Concepts Demonstrated
- Lists (Array-like Data Structures)
- Functions
- Loops and Conditional Statements
- Indexing
- Basic Data Analysis

## How to Run the Program
1. Download or clone this repository.
2. Open `Student Grade Management System.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook cells in order.
4. The program displays a menu with five options:
   - **1. Add Grades:** Enter the number of students and their scores.
   - **2. View All Grades:** Display all stored scores with their indexes.
   - **3. Analyze Grades:** Calculate the total number of scores, average, highest score, and lowest score.
   - **4. Search by Index:** Enter an index to retrieve a specific score.
   - **5. Exit:** Close the program.
5. Enter your preferred option and follow the prompts.
6. Continue using the menu until you select **5 to Exit**.

## How the Array Works

The program uses a Python list called `grades` to store multiple student scores in one collection.

- **Creating the array:** `grades = []` creates an empty list.
- **Adding grades:** `grades.append(score)` adds each new score to the list.
- **Accessing grades:** Each score has an index starting from `0`. For example, `grades[0]` accesses the first score.
- **Displaying grades:** A `for` loop iterates through the list and displays each score with its index.
- **Analysing grades:** Functions such as `sum()`, `max()`, and `min()` calculate the total, highest, and lowest scores.
- **Searching by index:** The program uses the entered index to retrieve a specific score directly.

### Illustration 

If the user enters scores of `70, 85, 90, 65`, the list stores them as follows:

| Index | Score |
|---|---:|
| 0 | 70 |
| 1 | 85 |
| 2 | 90 |
| 3 | 65 |

For example, `grades[2]` returns `90`, because the third score is stored at index `2`.

**Note:** Python lists are dynamic, meaning they can grow as new scores are added. In this application, the scores remain in memory while the program runs and are not permanently saved.

## Data Storage
Grades are stored in a Python list while the program is running. The data is not permanently saved, so it will be lost when the program stops.

## Author
Burhandeen Hafsatu 
