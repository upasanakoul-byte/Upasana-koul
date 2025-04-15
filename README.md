<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Profile</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-pic">
    <h1>Upasana Koul</h1>
    <p>Hello! I'm a psychology graduate with a love for learning and technology. I enjoy helping others and exploring creative projects.</p>
    <p>Here are some of my hobbies:</p>
    <ul>
      <li>Reading novels</li>
      <li>Web designing</li>
      <li>Listening to music</li>
    </ul>
  </div>
</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
  padding: 20px;
}

.container {
  max-width: 500px;
  margin: auto;
  background-color: white;
  padding: 20px;
  text-align: center;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 15px;
}

h1 {
  margin-bottom: 10px;
  color: #333;
}

p, ul {
  color: #555;
  font-size: 16px;
  margin-bottom: 10px;
}

ul {
  list-style-type: disc;
  padding-left: 20px;
  text-align: left;
}