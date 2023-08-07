# Markdown Note Taking App

A simple and efficient markdown-based note-taking app built using React. This application allows users to create, edit, and delete notes while visualizing markdown syntax on-the-go.

## Components

### Sidebar.jsx
- Displays a list of all the notes.
- Shows the note's title extracted from the first line.
- Click on a note to edit.
- Delete note functionality with a trash button.
- '+' button to create a new note.

### Editor.jsx
- A markdown editor powered by `ReactMde` and `Showdown`.
- Toggle between `write` and `preview` modes.
- Provides various markdown formatting options.

### App.jsx
- The main component combining `Sidebar` and `Editor`.
- Manages notes and the currently selected note state.
- Saves and retrieves notes from local storage.
- Uses `react-split` for a split view UI.

## Dependencies
- `React`
- `ReactMde`
- `Showdown`
- `nanoid`
- `react-split`

## Setup
1. Clone the repo: `git clone [your-repository-link]`.
2. Move to the directory: `cd [project-directory-name]`.
3. Install dependencies: `npm install`.
4. Start the server: `npm start`.
