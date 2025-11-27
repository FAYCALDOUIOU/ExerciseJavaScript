# JS Exercise – CRUD with Objects

## Overview

This is a beginner-friendly JavaScript exercise for practicing:

* Objects
* Arrays
* Loops
* Conditionals (`if`)
* Functions
* Basic DOM interaction (or prompts)

The exercise uses **objects with `name` and `Age` properties** and teaches CRUD operations: **Create, Read, Update, Delete**.

---

## Instructions

### STEP 1: Create an array

* Create an empty array called `items` to store student objects.

### STEP 2: Implement the functions

#### `addItem()`

* Ask the user for `name` and `Age` (using `prompt()` or input fields).
* Validate that both fields are not empty.
* Create an object: `{name: ..., Age: ...}`.
* Add the object to the `items` array.
* Alert a success message.
* If editing, update the existing object instead of adding a new one.

#### `showItems()`

* Loop through the `items` array and display each object.
* If the array is empty, alert `"No items yet"`.
* You can display the data in the console, using alerts, or in a table on the HTML page.

#### `editItem(index)`

* Fill the prompts or input fields with the selected object's data.
* Set a variable `editingIndex` to track which object is being edited.
* Change the add button text to "Update".

#### `deleteItem()`

* Ask the user for the index of the object to delete.
* Validate that the index is correct.
* Remove the object from the `items` array using `splice()`.
* Alert that the object has been deleted.

---

## Notes

* Use `if` statements for validation.
* Use `for` loops to iterate over the array.
* The exercise can be implemented using prompts/alerts or by manipulating HTML elements.
* Make sure the Add/Update functionality works correctly with the `editingIndex` variable.

---

This exercise is designed for **beginners** to practice object manipulation and CRUD logic in JavaScript.
