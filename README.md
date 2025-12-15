# HTML-code-to-create-a-form
HTML code to create a form using text field, radio,check box ,email,password and submit
<!DOCTYPE html>
<html>
<head>
    <title>Sample Form</title>
</head>
<body>
    <form action="/submit_page" method="POST">
        <!-- Textfield (Text input) -->
        <label for="username">Username (textfield):</label>
        <input type="text" id="username" name="username"><br><br>

        <!-- Radio buttons -->
        <label>Choose a gender (radio):</label><br>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <!-- Checkbox -->
        <input type="checkbox" id="subscribe" name="subscribe" value="subscribed">
        <label for="subscribe">Subscribe to newsletter (checkbox)</label><br><br>

        <!-- Email input -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>

        <!-- Password input -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password"><br><br>

        <!-- Submit button -->
        <input type="submit" value="Submit">
    </form>
</body>
</html>
