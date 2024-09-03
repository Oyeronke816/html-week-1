<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Title -->
    <title>Expense Tracker Application</title>

    <!-- Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Styles (Optional, for basic styling) -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        header {
            background-color: #f8f9fa;
            padding: 10px;
            text-align: center;
        }

        h1 {
            color: #343a40;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 8px;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        .form-container {
            margin-top: 20px;
        }

        .form-container input {
            margin-bottom: 10px;
            padding: 8px;
            width: 100%;
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <h1>Welcome to the Expense Tracker Application</h1>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Heading -->
        <h2>Track Your Expenses Effortlessly</h2>

        <!-- Paragraph -->
        <p>This application helps you manage and track your daily expenses efficiently. Get started by registering below.</p>

        <!-- Basic Registration Form -->
        <div class="form-container">
            <h3>Register</h3>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" placeholder="Enter your name" required><br>

                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br>

                <label for="phone">Phone Number:</label><br>
                <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required><br>

                <label for="password">Password:</label><br>
                <input type="password" id="password" name="password" placeholder="Enter your password" required><br>

                <button type="submit">Register</button>
            </form>
        </div>

        <!-- Table Displaying Common User Information -->
        <h3>User Information</h3>
        <table>
            <tr>
                <th>Name</th>
                <th>Email</th>
                <th>Phone Number</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>john.doe@example.com</td>
                <td>(123) 456-7890</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>jane.smith@example.com</td>
                <td>(987) 654-3210</td>
            </tr>
        </table>

        <!-- Image -->
        <h3>Our Application in Action</h3>
        <img src="https://via.placeholder.com/600x300" alt="Expense Tracker Screenshot" style="width:100%;height:auto;">

        <!-- External Link -->
        <p>Need more information? Visit <a href="https://google.com" target="_blank">Google</a>.</p>
    </main>

</body>

</html>
