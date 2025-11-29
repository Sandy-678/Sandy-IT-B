<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blood Donation System</title>
    <style>
        body { margin: 0; font-family: Arial, sans-serif; background: #f7f7f7; }
        header { background: #b30000; color: white; padding: 20px; text-align: center; }
        nav { background: #800000; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        nav a:hover { text-decoration: underline; }
        section { padding: 30px; background: white; margin: 20px; border-radius: 10px; }
        h2 { color: #b30000; }
        button { background: #b30000; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; }
        button:hover { background: #800000; }
        .footer { background: #b30000; color: white; padding: 10px; text-align: center; margin-top: 30px; }
    </style>
</head>
<body>

<header>
    <h1>Blood Donation System</h1>
    <p>Save Lives • Donate Blood • Be a Hero</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#donor">Donor Registration</a>
    <a href="#search">Search Blood</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Welcome to Blood Donation System</h2>
    <p>Our platform connects donors, hospitals, blood banks, and recipients to make blood availability easier and faster. Join us in saving lives by becoming a donor or requesting needed blood units.</p>
    <button>Become a Donor</button>
</section>

<section id="about">
    <h2>About the System</h2>
    <p>This Blood Donation System helps manage donors, recipients, hospitals, and blood bank inventories. It enables:</p>
    <ul>
        <li>Donor Registration & Profile Management</li>
        <li>Blood Search by Group and Location</li>
        <li>Request Blood Units</li>
        <li>Donation Event Management</li>
        <li>Inventory & Reports for Admin</li>
    </ul>
</section>

<section id="donor">
    <h2>Donor Registration Form</h2>
    <form>
        <label>Full Name:</label><br>
        <input type="text" style="width: 300px; padding: 8px;"><br><br>

        <label>Age:</label><br>
        <input type="number" style="width: 300px; padding: 8px;"><br><br>

        <label>Blood Group:</label><br>
        <select style="width: 300px; padding: 8px;">
            <option>Select Group</option>
            <option>A+</option>
            <option>A-</option>
            <option>B+</option>
            <option>B-</option>
            <option>O+</option>
            <option>O-</option>
            <option>AB+</option>
            <option>AB-</option>
        </select><br><br>

        <label>Phone Number:</label><br>
        <input type="tel" style="width: 300px; padding: 8px;"><br><br>

        <label>Email ID:</label><br>
        <input type="email" style="width: 300px; padding: 8px;"><br><br>

        <button type="submit">Register</button>
    </form>
</section>

<section id="search">
    <h2>Search Blood Availability</h2>
    <label>Select Blood Group:</label><br>
    <select style="width: 300px; padding: 8px;">
        <option>Select Group</option>
        <option>A+</option>
        <option>A-</option>
        <option>B+</option>
        <option>B-</option>
        <option>O+</option>
        <option>O-</option>
        <option>AB+</option>
        <option>AB-</option>
    </select><br><br>

    <button>Search</button>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Email:</strong> support@blooddonation.org</p>
    <p><strong>Phone:</strong> +91 98765 43210</p>
    <p><strong>Address:</strong> Blood Bank Center, India</p>
</section>

<div class="footer">
    <p>&copy; 2025 Blood Donation System | All Rights Reserved</p>
</div>

</body>
</html>
