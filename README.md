
<html>
<head>
    <title>User Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 40%;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: left;
        }
        h2 {
            text-align: center;
        }
        label {
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            background-color: #05A8AA;
            color: white;
            border: none;
            cursor: pointer;
            padding: 10px;
            font-size: 16px;
        }
        input[type="submit"]:hover {
            background-color: #048b8d;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>User Registration Form</h2>
        <form action="register.php" method="post">
            <label for="fullname">Full Name:</label>
            <input type="text" id="fullname" name="fullname" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            
            <label for="confirm_password">Confirm Password:</label>
            <input type="password" id="confirm_password" name="confirm_password" required>
            
            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone">
            
            <label for="address">Address:</label>
            <textarea id="address" name="address" rows="4"></textarea>
            
            <input type="submit" value="Register">
        </form>
    </div>
</body>
</html>
