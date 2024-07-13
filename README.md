<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Habit Tracker App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      line-height: 1.6;
      background-color: #f4f4f4;
    }
    h1, h2, h3 {
      color: #333;
    }
    code {
      background-color: #e8e8e8;
      padding: 2px 4px;
      border-radius: 4px;
    }
    pre {
      background-color: #e8e8e8;
      padding: 10px;
      border-radius: 4px;
      overflow: auto;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      background: #fff;
      margin: 5px 0;
      padding: 10px;
      border-radius: 4px;
      border: 1px solid #ddd;
    }
    .container {
      max-width: 800px;
      margin: auto;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Habit Tracker App</h1>
    <p>This is a simple habit tracker application built with React and Redux.</p>

    <h2>Installation</h2>
    <pre><code>
git clone https://github.com/yourusername/habit-tracker-app.git
cd habit-tracker-app
npm install
npm start
    </code></pre>

    <h2>Project Structure</h2>
    <ul>
      <li><code>src/store.js</code>: Configures the Redux store.</li>
      <li><code>src/App.js</code>: Sets up the routes and layout for the application.</li>
      <li><code>src/pages/Habits.js</code>: Displays the list of habits.</li>
      <li><code>src/pages/AddHabits.js</code>: Form to add new habits.</li>
      <li><code>src/components/HabitComponent.js</code>: Component to display individual habit details.</li>
      <li><code>src/components/HabitDetails.js</code>: Component to display and update habit status for each day.</li>
      <li><code>src/actions/habitActions.js</code>: Contains action creators for habits.</li>
      <li><code>src/constants/habitStatus.js</code>: Defines constants for habit statuses.</li>
    </ul>

    <h2>Usage</h2>
    <h3>Adding a Habit</h3>
    <ol>
      <li>Navigate to the "Add Habit" page by clicking "Add Habit" in the navigation bar.</li>
      <li>Fill out the form with the habit title and description.</li>
      <li>Click "Submit" to add the habit to the list.</li>
    </ol>

    <h3>Tracking Habit Progress</h3>
    <ul>
      <li>On the main page, you'll see a list of your habits.</li>
      <li>Click on the status icons to update the progress for each day:</li>
      <ul>
        <li><code>Hourglass</code>: Not done yet</li>
        <li><code>Done</code>: Completed</li>
        <li><code>Cancel</code>: Not completed</li>
      </ul>
    </ul>

    <h2>Dependencies</h2>
    <ul>
      <li>React</li>
      <li>Redux</li>
      <li>React-Redux</li>
      <li>React-Router-DOM</li>
      <li>@material-ui/core</li>
      <li>@material-ui/icons</li>
    </ul>

    <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
  </div>
</body>
</html>
