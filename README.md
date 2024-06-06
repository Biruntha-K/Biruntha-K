create a web page for to-do app



<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TO-DO List</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- create a container for the todo list -->
    <div id="todo-container">
      <!-- todo list header -->
      <div id="header">
        <h1>To Do List</h1>
      </div>

      <!-- create input box -->
      <div id="todo-form">
        <input
          type="text"
          class="input-item"
          name="input_box"
          id="input-box"
          placeholder="Add Task"
        />

        <!-- add button -->
        <button id="input-button" onclick="addTask()">Add</button>
      </div>

      <!-- task list -->
      <h2>Task List</h2>
      <ul id="list-container"></ul>
    </div>

    <script type="text/javascript" src="script.js"></script>
  </body>
</html>
