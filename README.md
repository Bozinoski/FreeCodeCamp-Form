<!DOCTYPE html>
<html lang="en">
<head>
    <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script> 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>FreeCodeCamp New Client Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 id="title">New Client Form</h1>
    <p id="descripyion">Please fill up the fields bellow, fields with * are requred.</p>
    <form action="/action_page.php" method="get" id="survey-form">
        <label for="name" id="name-label">Name</label>
        <input type="text" id="name" required placeholder="Enter your full name"><br>
        <label for="email" id="email-label">E-mail</label>
        <input type="email" id="email"required placeholder="Enter your E-mail"><br>
        <label for="number" id="number-label">Age</label>
        <input type="number" id="number" min="1" max="150" required placeholder="Enter your age"><br>
        <label for="dropdown">State</label>
        <select name="state" id="dropdown">
            <option value="Michigan">Michigan</option>
            <option value="Ohio">Ohio</option>
            <option value="Ilinois">Ilinois</option>
            <option value="Indiana">Indiana</option>
            <option value="Pensilvania">Pensilvania</option>
        </select>
        <fieldset>
            <legend>Choose your sex</legend>
            <label for="male">Male</label>
            <input type="radio" name="sex" id="male">
            <label for="Female">Female</label>
            <input type="radio" name="sex" id="female">
        </fieldset>
    </form>
</body>
</html>
