# Log-in-Form

This is a stylish HTML login form template with accompanying CSS for a visually appealing design. The form includes fields for a username and password, along with a submit button.

## Table of Contents
- [Features](#features)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features
- Stylish and responsive design
- Background image for aesthetic appeal
- Easy integration into your web project

## Usage
1. Clone this repository or copy the HTML code from the `index.html` file.
2. Add the HTML code to your project where you want the login form.
3. Copy the provided CSS styles from the `style.css` file or customize the styles as needed.
4. Adjust the background image path in the CSS to your desired image.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="login-form">
        <h1>Login</h1>
         <form action="#" method="post">
            <p>Username</p>
            <input type="text" name="user" placeholder="Enter your username">
            <p>Password</p>
            <input type="password" name="password" placeholder="Enter your password">
            <br>
            <button type="submit">Login</button>
         </form>
    </div>
</body>
</html>
