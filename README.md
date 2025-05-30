<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Study Tracker</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #f9d423, #ff4e50);
      margin: 0;
      padding: 0;
    }
    header {
      text-align: center;
      padding: 1rem;
      background: white;
      color: #333;
      font-size: 2rem;
      font-weight: bold;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }
    .container {
      max-width: 1200px;
      margin: 20px auto;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    }
    .section {
      margin-bottom: 30px;
    }
    h2 {
      margin-bottom: 10px;
      color: #333;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 20px;
    }
    table, th, td {
      border: 1px solid #ccc;
    }
    th, td {
      padding: 8px;
      text-align: center;
    }
    .bar {
      height: 20px;
      background-color: #4CAF50;
    }
    .tracker-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      background: #f0f0f0;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
    }
    input[type="text"], input[type="number"] {
      width: 100%;
      padding: 5px;
      margin: 4px 0;
    }
  </style>
</head>
<body>
  <header>📘 Study Tracker</header>
  <div class="container">
    <div class="section">
      <h2>Date & Study To-Do List</h2>
      <input type="date" />
      <table>
        <tr><th>Task</th><th>Status</th></tr>
        <tr><td><input type="text" placeholder="Chapter 1 Revision" /></td><td><input type="checkbox" /></td></tr>
        <tr><td><input type="text" placeholder="Maths Assignment" /></td><td><input type="checkbox" /></td></tr>
      </table>
    </div><div class="section">
  <h2>Study Time Table</h2>
  <table>
    <tr><th>Time</th><th>Activity</th></tr>
    <tr><td>6:00 AM</td><td><input type="text" placeholder="Wake up" /></td></tr>
    <tr><td>7:00 AM</td><td><input type="text" placeholder="Study Science" /></td></tr>
    <tr><td>8:00 AM</td><td><input type="text" placeholder="Breakfast" /></td></tr>
  </table>
</div>

<div class="section">
  <h2>Social Media Use (Hours)</h2>
  <input type="range" min="0" max="6" step="1" />
</div>

<div class="section">
  <h2>Consistency Tracker</h2>
  <table>
    <tr><th>Habit</th><th>M</th><th>T</th><th>W</th><th>T</th><th>F</th><th>S</th><th>S</th><th>Goal</th></tr>
    <tr><td>Study</td><td>✔️</td><td>✔️</td><td>✔️</td><td>❌</td><td>✔️</td><td>✔️</td><td>❌</td><td>5/7</td></tr>
  </table>
</div>

<div class="section">
  <h2>Subject Wise Study Time Tracker (Minutes)</h2>
  <table>
    <tr><th>Subject</th><th>Time</th></tr>
    <tr><td>Math</td><td><input type="number" placeholder="30" /> mins</td></tr>
    <tr><td>Science</td><td><input type="number" placeholder="45" /> mins</td></tr>
  </table>
</div>

<div class="section">
  <h2>Self Study vs Tuition</h2>
  <table>
    <tr><th>Type</th><th>1hr</th><th>2hr</th><th>3hr</th><th>4hr</th><th>5hr</th></tr>
    <tr><td>Self Study</td><td>✔️</td><td>✔️</td><td>✔️</td><td></td><td></td></tr>
    <tr><td>Tuition</td><td>✔️</td><td>✔️</td><td></td><td></td><td></td></tr>
  </table>
</div>

<div class="section">
  <h2>Topper’s Formula (Super 5)</h2>
  <table>
    <tr><th>Task</th><th>Status</th></tr>
    <tr><td>Mirror Practice</td><td><input type="checkbox" /></td></tr>
    <tr><td>No Phone Use</td><td><input type="checkbox" /></td></tr>
    <tr><td>Teach a Friend</td><td><input type="checkbox" /></td></tr>
    <tr><td>Daily Test</td><td><input type="checkbox" /></td></tr>
    <tr><td>Physical Activity</td><td><input type="checkbox" /></td></tr>
  </table>
</div>

<div class="section">
  <h2>Rate Your Day</h2>
  <label>1 Thing I'm Proud of:</label>
  <input type="text" placeholder="Completed Physics revision" />
  <br>
  <label>Rate (1-5):</label>
  ⭐ ⭐ ⭐ ⭐ ⭐
  <br><br>
  <label>Sleep (8 Hours?)</label>
  <input type="checkbox" /> Yes
</div>

  </div>
</body>
</html>
