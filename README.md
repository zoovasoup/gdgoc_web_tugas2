# Assignment 2 - GDGOC

## Description

Assigment 2 - Web Dev - GDGOC-Telkom Bandung - This assignment involves implementing a simple note-taking system in vanilla JavaScript without any frameworks. The system should support basic CRUD (Create, Read, Update, Delete) operations on a list of notes.

## Requirements

- Use only vanilla JavaScript (no frameworks or libraries).
- Implement the following functions:
  - `createNote(heading, description, created_by)`: Adds a new note to the `notes` array.
  - `readNote()`: Displays all notes in the `notes` array.
  - `updateNote(id, newHeading, newDescription)`: Updates the note with the given `id`.
  - `deleteNote(id)`: Deletes the note with the given `id`.
- Maintain the `created_at` timestamp for each note using `Date.now()`.

## Data Structure

The notes should be stored in the following format:

```js
let notes = [
  {
    id: 1,
    heading: "Mempelajari Javascript",
    description: "Lorem ipsum dolor sit amet consectetur adipisicing elit...",
    created_by: "John Doe",
    created_at: 1738146027613, // Timestamp
  },
];
```

## Notes

- Ensure that each new note has a unique `id`.
- Keep the implementation clean and readable.
- Do not modify the test code provided above.
