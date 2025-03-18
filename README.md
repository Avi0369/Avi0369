<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RoomsHub - Your Smart Living Companion</title>
  <link rel="stylesheet" href="../static/styles.css">
</head>
<body>
  <!-- Navbar for Navigation -->
  <div class="navbar">
    <div class="logo"> RoomsHub </div>
    <div class="menu-icons">
      <span class="menu-icon" onclick="toggleMenu()">☰</span>
    </div>
  </div>

  <!-- Sidebar Menu -->
  <div class="sidebar" id="sidebar">
    <h3>Menu</h3>
    <ul>
      <li><a href="#" onclick="showPage('welcome')">Home</a></li>
      <li><a href="#" onclick="showPage('signup')">Sign Up</a></li>
      <li><a href="#" onclick="showPage('login')">Login</a></li>
      <li><a href="#" onclick="showPage('profile')">Profile</a></li>
      <li><a href="#" onclick="showPage('rooms')">Manage Rooms</a></li>
      <li><a href="#" onclick="showPage('settings')">App Settings</a></li>
      <li><a href="#" onclick="showPage('notifications')">Notifications</a></li>
      <li><a href="#" onclick="showPage('terms')">Terms & Conditions</a></li>
      <li><a href="#" onclick="showPage('privacy')">Privacy & Security</a></li>
      <li><a href="#" onclick="showPage('developer')">About Developer</a></li>
    </ul>
  </div>

  <!-- Welcome Page -->
  <div class="container" id="welcome">
    <div class="tagline">Your Smart Living Companion – Redefining Spaces with AI.</div>
    <div class="auth-buttons">
      <button class="btn" onclick="showPage('signup')">Sign Up</button>
      <button class="btn" onclick="showPage('login')">Login</button>
    </div>
  </div>

  <!-- Sign-Up Page -->
  <div class="auth-container" id="signup">
    <h2>Sign Up</h2>
    <input type="text" placeholder="Name" required>
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <input type="password" placeholder="Confirm Password" required>
    <select>
      <option value="owner">Room Owner</option>
      <option value="finder">Room Finder</option>
    </select>
    <button class="btn">Sign Up</button>
    <p><a href="#" onclick="showPage('login')" style="color: white; text-decoration: none;">Already have an account? Login</a></p>
  </div>

  <!-- Login Page -->
  <div class="auth-container" id="login">
    <h2>Login</h2>
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button class="btn">Login</button>
    <a href="#" style="color: white; text-decoration: none;">Forgot Password?</a>
  </div>

  <!-- Profile Page -->
  <div class="profile-container" id="profile">
    <img src="https://via.placeholder.com/100" alt="Profile Picture">
    <h2>User Profile</h2>
    <p><strong>Name:</strong> John Doe</p>
    <p><strong>Email:</strong> john.doe@example.com</p>
    <p><strong>Role:</strong> Room Finder</p>
    <button class="btn">Edit Profile</button>
  </div>

  <!-- Room Owner Features -->
  <div class="room-container" id="rooms">
    <h2>Manage Rooms</h2>
    <table>
      <thead>
        <tr>
          <th>Room Type</th>
          <th>Location</th>
          <th>Price</th>
          <th>Action</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Single Room</td>
          <td>New York</td>
          <td>$500</td>
          <td>
            <button class="btn">Edit</button>
            <button class="btn">Delete</button>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <!-- Developer Introduction -->
  <div class="developer-container" id="developer">
    <img src="https://via.placeholder.com/150" alt="Developer Photo">
    <h2>Avinash Raj</h2>
    <p>Business Innovator & Strategist</p>
    <p>Transforming Spaces Through AI and Strategy</p>
    <p>Contact: avinash@example.com | +1234567890</p>
  </div>

  <footer>
    &copy; 2023 RoomsHub. All rights reserved.
  </footer>

  <script src="../static/script.js"></script>
</body>
</html>
