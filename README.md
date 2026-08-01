<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Event Registration</title>
</head>
<body>
<h1>Register for the Event</h1>
<form action="/register" method="POST">
<label for="name">Full Name:</label><br />
<input type="text" id="name" name="name" required /><br /><br />
<label for="email">Email:</label><br />
<input type="email" id="email" name="email" required /><br /><br />
<label for="phone">Phone Number:</label><br />
<input type="tel" id="phone" name="phone" /><br /><br />
<button type="submit">Register</button>
</form>
</body>
</html>
