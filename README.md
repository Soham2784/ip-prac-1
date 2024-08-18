<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Around - Your Gateway to Adventure</title>
</head>
<body>
    <header>
     <img height="150px" src="Screenshot 2024-08-12 190215.png">
        <h1>Travel Around</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home">
            <h2>Welcome to Travel Around!</h2>
            <p>Your gateway to unforgettable adventures and breathtaking destinations.</p>
            <video width="360" controls>
                <source src="https://videos.pexels.com/video-files/3135808/3135808-sd_640_360_24fps.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>

            <br>

            <audio controls>
                <source src="Audio 2024-08-18 at 12.14.25_7fb2edb6.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </section>
        
        <section id="about">
            <h2>About Us</h2>
            <table border="1" cellpadding="10" cellspacing="0">
                <tr>
                    <th>Company Name</th>
                    <td>Travel Around</td>
                </tr>
                <tr>
                    <th>Founded</th>
                    <td>2005</td>
                </tr>
                <tr>
                    <th>Contact</th>
                    <td>Email: info@travelaround.com</td>
                </tr>
                <tr>
                    <th>Contact</th>
                    <td>Email: @travelaround.com<br>Phone: +1200302238</td>
                </tr>
            </table>
        </section>
        
        <section id="destinations">
            <h2>Featured Destinations</h2>
            <table border="1" cellpadding="10" cellspacing="0">
                <tr>
                    <th>Destination</th>
                    <th>Description</th>
                </tr>
                <tr>
                    <td>Paris, France</td>
                    <td>Experience the romance and charm of the City of Light. From the Eiffel Tower to the Louvre, Paris is a dream come true.</td>
                </tr>
                <tr>
                    <td>Maui, Hawaii</td>
                    <td>Discover the stunning beaches, lush landscapes, and vibrant culture of Maui. Perfect for a tropical getaway.</td>
                </tr>
                <tr>
                    <td>Kyoto, Japan</td>
                    <td>Immerse yourself in the rich history and serene beauty of Kyoto. Explore ancient temples, gardens, and traditional tea houses.</td>
                </tr>
            </table>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form action="/submit-form" method="post">
                <table border="0" cellpadding="10" cellspacing="0">
                    <tr>
                        <td><label for="name">Name:</label></td>
                        <td><input type="text" id="name" name="name" required></td>
                    </tr>
                    <tr>
                        <td><label for="email">Email:</label></td>
                        <td><input type="email" id="email" name="email" required></td>
                    </tr>
                    <tr>
                        <td><label for="message">Message:</label></td>
                        <td><textarea id="message" name="message" rows="4" cols="50" required></textarea></td>
                    </tr>
                    <tr>
                        <td colspan="2" style="text-align: center;"><input type="submit" value="Submit"></td>
                    </tr>
                </table>
            </form>
        </section>
    </main>
    
    <footer>
        <p>Follow us on:
            <a href="https://www.facebook.com/TravelAround" target="_blank">Facebook</a> |
            <a href="https://www.twitter.com/TravelAround" target="_blank">Twitter</a> |
            <a href="https://www.instagram.com/TravelAround" target="_blank">Instagram</a>
        </p>
    </footer>
</body>
</html>
