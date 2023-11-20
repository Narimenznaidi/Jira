# Jira
test genie logiciel 
<!DOCTYPE html>
<html>
<head>
    <title>Sign Up / Sign In</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
        }

        h2 {
            text-align: center;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 3px;
            font-size: 16px;
        }

        input[type="submit"] {
            background: #007BFF;
            color: #fff;
            border: 0;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background: #0056b3;
        }

        .switch-form {
            text-align: center;
        }

        .switch-form a {
            text-decoration: none;
            color: #007BFF;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Sign Up</h2>
        <form action="signup.php" method="post">
            <div class="form-group">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <input type="submit" value="Sign Up">
            </div>
        </form>

        <div class="switch-form">
            <p>Already have an account? <a href="signin.html">Sign In</a></p>
        </div>
    </div>

    <div class="container">
        <h2>Sign In</h2>
        <form action="signin.php" method="post">
            <div class="form-group">
                <label for="signin-username">Username:</label>
                <input type="text" id="signin-username" name="signin-username" required>
            </div>
            <div class="form-group">
                <label for="signin-password">Password:</label>
                <input type="password" id="signin-password" name="signin-password" required>
            </div>
            <div class="form-group">
                <input type="submit" value="Sign In">
            </div>
        </form>

        <div class="switch-form">
            <p>Don't have an account? <a href="signup.html">Sign Up</a></p>
        </div>
    </div>
</body>
</html>
