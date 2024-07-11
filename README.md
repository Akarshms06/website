<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MyPlanner</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>MyPlanner</h1>
  </header>
  <main>
    <section id="task-form">
      <input type="text" id="task-input" placeholder="Enter a new task">
      <button id="add-task-button">Add Task</button>
    </section>
    <section id="task-list">
      <h2>Task List</h2>
      <ul id="tasks"></ul>
    </section>
  </main>
  <script src="script.js"></script>
  <div class="datetime-container">
    <div id="current-date"></div>
    <div id="current-time"></div>
  </div>
</body>
</html>
