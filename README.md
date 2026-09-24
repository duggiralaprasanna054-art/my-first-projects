<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Project</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Welcome to My First Project! 🚀</h1>
        <p>This is a simple web page created and uploaded to GitHub successfully.</p>
        <button onclick="showMessage()">Click Me</button>
        <p id="msg"></p>
    </div>

    <script>
        function showMessage() {
            document.getElementById("msg").innerText = "Hello! Thanks for visiting my project.";
        }
    </script>
</body>
</html>
