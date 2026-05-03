# student-tracker
Mental‑health &amp; study‑tracker web app.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Student Mental Health Notes</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <main class="container">
    <h1>Student Mental Health Tracker</h1>
    <p>This is a simple page to track how you feel today.</p>

    <h2>How I feel today:</h2>
    <ul>
      <li class="mood good">Good – I feel calm and motivated.</li>
      <li class="mood neutral">Neutral – It’s just okay.</li>
      <li class="mood bad">Bad – I feel stressed or low.</li>
    </ul>

    <p>Remember: it’s okay not to be okay. Talk to someone you trust.</p>
  </main>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f4f8fb;
  margin: 0;
  padding: 20px;
}

.container {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
  background: white;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h1 {
  color: #2c66b3;
  text-align: center;
}

ul {
  margin: 10px 0;
  padding: 0 20px;
}

.mood.good {
  color: #00b894;
}

.mood.bad {
  color: #d63031;
}

.mood.neutral {
  color: #74b9ff;
}
