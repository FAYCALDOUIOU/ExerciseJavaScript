// JS EXERCISE – CRUD WITH OBJECTS + IF CONDITION + LOOP + FUNCTIONS
// -----------------------------------------------------------
// You must write code that interacts with the HTML buttons using onclick attributes.
// Each item will be an OBJECT with a name and a Age.
// -----------------------------------------------------------

// STEP 1: Create an empty array to store objects
var items = [];

// STEP 2: Write your functions

// addItem(): Ask the user for name and Age (prompt). If not empty → add an object to the array.
function addItem() {
    // TODO: Ask for name using prompt()
    // TODO: Ask for Age using prompt()
    // TODO: Check with IF that both name and Age are not empty
    // TODO: Create an object: var item = {name: ..., Age: ...}
    // TODO: Push it to items array
    // TODO: Alert success message
}

// showItems(): Loop through the array and show all objects
function showItems() {
    // TODO: If array is empty, alert "No items yet"
    // TODO: Loop using for (var i = 0; i < items.length; i++)
    // TODO: Show name and Age for each object
}

// editItem(index): Fill inputs or prompts with selected object data
function editItem(index) {
    // TODO: Get object at index
    // TODO: Fill name and Age in prompts or input fields
    // TODO: Set editingIndex = index
    // TODO: Change add button text to "Update"
}

// deleteItem(): Ask the user for index to delete. If valid → remove it.
function deleteItem() {
    // TODO: Use prompt() to ask for index
    // TODO: Check with IF index >= 0 && index < items.length
    // TODO: Use items.splice(index, 1)
    // TODO: Alert deleted
}

// -----------------------------------------------------------
// That’s it! Fill in the TODOs to complete the object-based exercise.
// -----------------------------------------------------------



