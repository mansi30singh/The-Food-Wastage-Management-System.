# The-Food-Wastage-Management-System.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Food Wastage Management System</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Food Wastage Management System</h1>
    <p>Minimizing food waste, maximizing impact</p>
  </header>

  <section id="about">
    <h2>About the System</h2>
    <p>
      The Food Wastage Management System is designed to connect food donors and recipients to ensure that edible food is redirected to those in need, minimizing waste and promoting sustainability.
    </p>
  </section>

  <section id="features">
    <h2>Key Features</h2>
    <div class="feature">
      <h3>Real-Time Tracking</h3>
      <p>Monitor food donations, pickups, and deliveries with live updates.</p>
    </div>
    <div class="feature">
      <h3>Eco-Friendly Disposal</h3>
      <p>Promote composting and other responsible disposal methods for waste.</p>
    </div>
    <div class="feature">
      <h3>Donor-Recipient Matching</h3>
      <p>Seamlessly connect food donors with shelters and food banks.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Get Involved</h2>
    <button id="donateButton">Become a Donor</button>
  </section>

  <footer>
    <p>&copy; 2024 Food Wastage Management System. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
/* General Styles */
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
  line-height: 1.6;
}

header {
  background: #48a868;
  color: #fff;
  padding: 20px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  font-size: 1.2em;
}

#about, #features, #contact {
  padding: 20px;
  background-color: #fff;
  margin: 20px 10px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
  color: #48a868;
  margin-bottom: 10px;
}

.feature {
  padding: 10px;
  border: 1px solid #48a868;
  border-radius: 5px;
  margin-bottom: 10px;
  transition: background-color 0.3s ease;
}

.feature:hover {
  background-color: #f0f9f0;
}

button {
  background-color: #48a868;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #3d7c5c;
}

/* Footer */
footer {
  background-color: #48a868;
  color: #fff;
  text-align: center;
  padding: 10px 0;
  position: fixed;
  bottom: 0;
  width: 100%;
}

// JavaScript code to handle the button click event
document.getElementById('donateButton').addEventListener('click', function() {
  alert('Thank you for your interest in becoming a donor!');
});
