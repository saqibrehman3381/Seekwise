
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SeekWise AI</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>SeekWise: AI-Powered Quranic Science Explorer</h1>
    <button onclick="startResearch()">Start Auto-Research</button>
    <p id="status">Awaiting command...</p>
    <canvas id="graph" width="300" height="300"></canvas>
  </div>
  <script src="app.js"></script>
</body>
</html>body {
  font-family: sans-serif;
  background: #f4f7fa;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}
.container {
  text-align: center;
  background: white;
  padding: 2em;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
button {
  padding: 1em 2em;
