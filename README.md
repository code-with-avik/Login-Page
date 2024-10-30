# Login Page

This repository contains a simple login page built with HTML and CSS.

## Project Structure

**forms.html**

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <h2>Login Now</h2>
    <form action="post">
        <div>
            <label for="username">Name</label>
            <br>
            <input type="text" id="username" name="username" placeholder="Enter your name" autofocus>
        </div>
        <div>
            <label for="roll no">Roll No</label>
            <br>
            <input type="text" id="roll no" name="roll no" placeholder="Enter your roll no" autofocus>
        </div>
        <div>
            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
        </div>
        <div>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
        </div>
        <br>
        <div>
            <input type="checkbox" id="subscribe" name="subscribe" value="yes">
            <label for="subscribe">Subscribe to newsletter</label>
        </div>
        <br><br>
        <div>
            <label for="comment">Enter your comment</label>
            <br>
            <textarea id="comment" name="comment" rows="4" cols="50"></textarea>
        </div>
        <br>
        <div>
            <select name="states">
                <option value="West Bengal">West Bengal</option>
                <option value="Mumbai">Mumbai</option>
                <option value="Punjab">Punjab</option>
                <option value="Delhi">Delhi</option>
                <option value="Karnataka">Karnataka</option>
                <option value="Rajasthan">Rajasthan</option>
                <option value="Kerala">Kerala</option>
                <option value="Assam">Assam</option>
                <option value="Goa">Goa</option>
                <option value="Gujarat">Gujarat</option>
                <option value="Haryana">Haryana</option>
                <option value="Himachal Pradesh">Himachal Pradesh</option>
                <option value="Jammu and Kashmir">Jammu and Kashmir</option>
                <option value="Jharkhand">Jharkhand</option>
                <option value="Madhya Pradesh">Madhya Pradesh</option>
                <option value="Maharashtra">Maharashtra</option>
                <option value="Manipur">Manipur</option>
                <option value="Meghalaya">Meghalaya</option>
                <option value="Mizoram">Mizoram</option>
                <option value="Nagaland">Nagaland</option>
                <option value="Odisha">Odisha</option>
                <option value="Pondicherry">Pondicherry</option>
                <option value="Sikkim">Sikkim</option>
                <option value="Tamil Nadu">Tamil Nadu</option>
                <option value="Telangana">Telangana</option>
                <option value="Tripura">Tripura</option>
                <option value="Uttar Pradesh">Uttar Pradesh</option>
                <option value="Uttarakhand">Uttarakhand</option>
        </select>
        </div>
        <br>
        <input type="submit" value="Login">
    </form>
</body>

</html>

**style.css**

/* style.css */

/* General styles */
body {
    font-family: Arial, sans-serif;
    background-color: #bea278;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100vh;
}

/* Styling the heading */
h2 {
    color: rgb(170, 121, 31);
    font-size: 24px;
    margin-top: 20px;
}

/* Centering the form container */
form {
    background-color: #ecbd24;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(97, 54, 10, 0.1);
    width: 90%;
    max-width: 400px;
    margin-top: 20px;
}

/* Styling form labels */
label {
    display: block;
    margin-bottom: 5px;
    color: #555;
    font-weight: bold;
}

/* Styling form inputs */
input[type="text"],
input[type="password"],
textarea,
select {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #0d0e04;
    border-radius: 4px;
    box-sizing: border-box;
}

/* Styling checkbox */
input[type="checkbox"] {
    margin-right: 10px;
}

/* Styling radio buttons container */
.radio-group {
    display: flex;
    align-items: center;
    margin-bottom: 15px;
}

.radio-group label {
    margin-right: 15px;
    margin-left: 5px;
    display: flex;
    align-items: center;
}

.radio-group input[type="radio"] {
    margin-right: 5px;
}

/* Styling the submit button */
input[type="submit"] {
    width: 100%;
    padding: 10px;
    background-color: #4CAF50;
    color: rgb(31, 24, 3);
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
}

input[type="submit"]:hover {
    background-color: #45a049;
}

/* Responsive design */
@media (max-width: 600px) {
    form {
        padding: 15px;
    }

    h2 {
        font-size: 20px;
    }

    input[type="text"],
    input[type="password"],
    textarea,
    select {
        padding: 8px;
    }

    input[type="submit"] {
        padding: 8px;
        font-size: 14px;
    }
}


- **forms.html**: Contains the HTML structure of the login page.
- **style.css**: Contains the CSS styles for the login page.
- **.gitattributes**: Configures Git to handle line endings properly.

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/login-page.git
    ```

2. Open `forms.html` in your web browser to view the login page.

## Features

- Responsive design
- Styled form elements
- Includes fields for username, roll number, password, gender, subscription, comments, and state selection.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

