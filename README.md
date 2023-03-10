# Skills Tracker

This repository (skills-tracker-01) is the same project as skills-tracker. The difference being that the latter was created first and started working on it with React. With this new version, the objective is to create an entire MERN (MongoDB, Express, React, Node.js) and will begin with the backend portion.

## Obstacles

- Getting to add a list element to the list from the form in ToDoList.js

  - Used useState to declare to variables (text and listItems) to store the values from the textarea and the unordered list.
  - Made a function that onClick() updates both values.
  - Rendered to JSX the textarea value, the onclick() to the button, and a map function to the unordered list.

- Implementing a way for the user to add the skills involved for each task.

  - Came up with an idea to do it with checkbox, in the same form that's used to add the list element.

- How to store the value of the checkboxes inside each item.

  - Made a boolean state for each checkbox.
  - Modified addToList(), instead of text, the function adds an object "newTask" with a task element that equals text, and a skills object with all the checkboxes boolean values.

- Rendering the skills value for each item

- Decided at this point to work first on the backend portion of the app.

  - Asked ChatGPT how to create a MERN app. The first steps are working with the backend, specifically initialize it with npm.
  - ChatGPT guided me through the hole process of 'npm init' and creating the 'package.json' file.

- Can't find the dependencies in the package.json file. Don't know how to and which ones to download. Apparently 'npm install' didn't work correctly.

  - The reason was skipping the part about specifying the dependencies in the package.json folder.
  - Found a great guide in the MongoDB website for creating a MERN Stack Application. It organizes the directory in two parts: server and client. Found this an excellent way to organize the project, to do so I will have to create a new repository (skills-tracker-02). Since I'm only in the setting up part, it won't be to much trouble.
