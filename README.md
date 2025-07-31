# bikeshowroom
//here is the code




<!DOCTYPE html>
<html>
<head>
    <title>Welcome to My Bike Showroom</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(to right, #000000, #434343);
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 32px;
        }

        .offer-banner {
            background-color: #ff4d4d;
            color: white;
            padding: 10px;
            text-align: center;
            font-weight: bold;
            font-size: 18px;
        }

        section, form, video, audio {
            max-width: 900px;
            background-color: white;
            padding: 25px;
            margin: 30px auto;
            box-shadow: 0 0 12px rgba(0,0,0,0.2);
            border-radius: 10px;
        }

        img {
            display: block;
            margin: 20px auto;
            border-radius: 10px;
        }

        h2, h3 {
            color: #2c3e50;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th {
            background-color: #222;
            color: white;
        }

        th, td {
            padding: 10px;
            text-align: center;
        }

        button, input[type="submit"] {
            background-color: #27ae60;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s ease;
        }

        button:hover, input[type="submit"]:hover {
            background-color: #1e8449;
        }

        select, input[type="text"], input[type="password"], textarea {
            padding: 8px;
            width: 100%;
            box-sizing: border-box;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .gallery {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .gallery img {
            width: 180px;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        .reviews {
            background-color: #f1f1f1;
            border-left: 5px solid #27ae60;
            margin: 10px 0;
            padding: 10px;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>

    <header>🏍️ Welcome to My Bike Showroom 🏍️</header>

    <div class="offer-banner">
        🔥 Limited Time Offer: Get up to ₹10,000 off on selected bikes! 🔥
    </div>

    <img src="bike.jpeg" alt="Main Bike Image" width="400">

    <section>
        <h2>Bike Introduction</h2>
        <p>This is a powerful and stylish bike suitable for all types of riders.</p>

        <h3>Select Bike Color:</h3>
        <input type="radio" name="color" value="Red"> Red<br>
        <input type="radio" name="color" value="Blue"> Blue<br>
        <input type="radio" name="color" value="Black"> Black<br><br>

        <h3>Select Bike Model:</h3>
        <select>
            <option value="r15">Yamaha R15</option>
            <option value="duke">KTM Duke 200</option>
            <option value="classic">Royal Enfield Classic 350</option>
        </select>

        <h3>Bike Specifications:</h3>
        <table>
            <tr><th>Feature</th><th>Details</th></tr>
            <tr><td>Engine</td><td>155cc</td></tr>
            <tr><td>Top Speed</td><td>140 km/h</td></tr>
            <tr><td>Mileage</td><td>45 km/l</td></tr>
        </table>
        <br>
        <button>Book Test Ride</button>
    </section>

    

    <section>
        <h2>Customer Reviews</h2>
        <div class="reviews">
            <strong>Ravi Kumar:</strong> "Amazing performance and stylish looks. Loved the smooth ride!"
        </div>
        <div class="reviews">
            <strong>Meena Sharma:</strong> "Great mileage and comfort. Perfect for daily commuting."
        </div>
    </section>

    <section>
        <h2>Watch Bike Video</h2>
        <video width="100%" controls>
            <source src="d:/Downloads/5198954-uhd_2160_4096_25fps.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

    <section>
        <h2>Listen to Bike Sound</h2>
        <audio controls>
            <source src="bike (1).mp3" type="audio/mpeg">
            Your browser does not support the audio tag.
        </audio>
    </section>

    <section>
        <h2>Login Form</h2>
        <form action="/submit-login" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password"
                   minlength="8"
                   pattern="(?=.*\d)(?=.*[a-z])(?=.*[A-Z])(?=.*[@$!%?&])[A-Za-z\d@$!%?&]{8,}"
                   title="Password must include uppercase, lowercase, number, and special character"
                   required><br><br>

            <input type="submit" value="Login">
        </form>
    </section>

    <section>
        <h2>Contact Us</h2>
        <form>
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label>
            <input type="text" id="email" name="email" required><br><br>

            <label for="message">Your Message:</label>
            <textarea id="message" rows="4" required></textarea><br><br>

            <button type="submit">Send Inquiry</button>
        </form>
    </section>

    <footer>
        &copy; 2025 My Bike Showroom | Call: +91-9876543210 | Email: info@mybikestore.com
    </footer>

</body>
</html>
