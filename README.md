# Devops
-------------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Registration Form</title>
</head>
<body>
<h2>User Registration Form</h2>
<form>
    <label for="name">Full Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>
    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required><br><br>
    <label for="phone">Phone Number:</label><br>
    <input type="text" id="phone" name="phone"><br><br>
    <label for="gender">Gender:</label><br>
        <input type="radio" name="gender" value="Male"> Male
        <input type="radio" name="gender" value="Female"> Female
        <input type="radio" name="gender" value="Other"> Other
        <br><br>
    <input type="submit" value="Register">
</form>
</body>
</html>
---------------------------
git config --list
git config --global --unset user.name
git config --global --unset user.email
git credential-manager reject
git config --global user.name "YourName"
git config --global user.email "your-email@example.com"
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<username>/<repo>.git
git branch -M main
git push -u origin main
-------------------------------------

