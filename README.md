<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation Bar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Style the navigation bar */
        .navbar {
            background-color: #333;
            overflow: hidden;
        }

        /* Navigation links */
        .navbar a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 17px;
        }

        /* Change color on hover */
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Active link style */
        .navbar a.active {
            background-color: #4CAF50;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Navigation bar -->
    <div class="navbar">
        <a href="#file" class="active">File</a>
        <a href="#edit">Edit</a>
        <a href="#view">View</a>
    </div>

</body>
</html>
