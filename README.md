<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Picture</title>
    <style>
        /* CSS for overall page styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0; /* Light background */
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        /* Container to center image and heading */
        .container {
            text-align: center;
            background-color: #fff; /* White background for the box */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Soft shadow around box */
        }

        /* Heading styling */
        h2 {
            color: #333;
            margin-bottom: 20px;
        }

        /* Profile Picture CSS */
        .profile-pic {
            width: 150px; /* Image width */
            height: 150px; /* Image height */
            border-radius: 50%; /* Circle shape */
            border: 3px solid #333; /* Border around image */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Shadow effect around image */
            object-fit: cover; /* Ensure image fits without distortion */
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Your Profile Picture</h2>
        <!-- Image with CSS class applied -->
        <img src="file:///storage/emulated/0/HTML_Images/profile.jpg" alt="Profile Picture" class="profile-pic">
    </div>

</body>
</html>