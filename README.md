NotesDisplay Component
The NotesDisplay component is a React component designed for managing notes within a web application. It allows users to create, view, edit, and delete notes, as well as search for specific notes by title.

Features
Create new notes with a title and content.
Edit notes by updating their title and content.
Delete notes individually.
View detailed content of each note.
Search for notes by title.
Installation
To use the NotesDisplay component in your React application, follow these steps:

Install React if you haven't already:

npx create-react-app my-app
cd my-app
npm start
Install the required dependencies:

npm install jspdf
Copy the NotesDisplay.js file into your React project.

Import the NotesDisplay component into your application:

import NotesDisplay from './NotesDisplay';
Use the NotesDisplay component in your application's JSX:

<NotesDisplay />

Usage
Once the NotesDisplay component is integrated into your React application, it provides the following functionality:

Users can create new notes by entering a title and content, then clicking the "Save" button.
Notes are displayed in a list format, showing only the title initially.
Users can click on a note to view its detailed content.
Users can edit a note by updating its title and content in the form fields and clicking the "Save" button again.
Users can delete a note by clicking the trash icon next to it.
Users can search for notes by entering a search query in the search input field and clicking the search button.
Dependencies
jspdf: A JavaScript library for generating PDF files in the browser.
Local Storage
The NotesDisplay component utilizes the browser's local storage to persist notes data across page refreshes. Notes are stored in the local storage under the key "notes".

Styling
The component utilizes CSS modules for styling. You can customize the styles by modifying the NotesDisplay.module.css file.
