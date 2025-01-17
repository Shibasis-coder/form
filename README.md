# forms
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Credentials Form</title>
    <link rel="icon" href="https://th.bing.com/th/id/OIP.DUYeeVjprs2A4uZGq7D6IwHaHy?w=172&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" type="image/x-icon">
</head>
<body>
    <header style="background-color: hsla(0, 0%, 95%, 0.923); padding: 20px; text-align: center;"> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQlkkF2PpW0S514aY4cIg6DUKzieQnbwOhlJQ&s" alt="Header Image" style="width: 100%; max-width: 600px; height: auto;"> <h1>Welcome to My Website</h1></header>
    <h2>Enter Your Credentials</h2>
    <form action="/submit_credentials" method="POST">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br>
        <label for="gender">Gender:</label><br> <select id="gender" name="gender" required> <option value="">--Please choose an option--</option> <option value="male">Male</option> <option value="female">Female</option></select><br><br>
        
        <input type="submit" value="Submit">
    </form>
</body>
</html>
