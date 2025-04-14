# Advanced HTML5 Elements and Forms
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 8px;
        }
        table {
            width: 100%;
            margin-bottom: 20px;
        }
        form {
            max-width: 400px;
        }
    </style>
</head>
<body>

    <h1>Welcome to the Sample Page</h1>

    <h2>Ordered List (Roman Numerals)</h2>
    <ol type="I">
        <li>Introduction</li>
        <li>Features</li>
        <li>Contact List</li>
        <li>Gallery</li>
        <li>Registration</li>
    </ol>

    <h2>External Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Sample from Pexels" width="600">

    <h2>Contact List</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Elm Street, Nairobi</td>
            <td>+254700123456</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Maple Avenue, Nairobi</td>
            <td>+254711654321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>David Kimani</td>
            <td>789 Pine Lane, Nairobi</td>
            <td>+254722334455</td>
            <td>david@example.com</td>
        </tr>
        <tr>
            <td>Grace Wanjiru</td>
            <td>321 Oak Road, Nairobi</td>
            <td>+254733998877</td>
            <td>grace@example.com</td>
        </tr>
        <tr>
            <td>Kevin Otieno</td>
            <td>654 Cedar Blvd, Nairobi</td>
            <td>+254744556677</td>
            <td>kevin@example.com</td>
        </tr>
    </table>

    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="fullname">Full Name:</label><br>
        <input type="text" id="fullname" name="fullname" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="mobile">Mobile:</label><br>
        <input type="tel" id="mobile" name="mobile" required><br><br>

        <label for="address">Address:</label><br>
        <input type="text" id="address" name="address"><br><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br><br>

        <input type="submit" value="Register">
    </form>

</body>
</html>
