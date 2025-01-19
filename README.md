<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free CSS</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }

        /* Header */
        header {
            background-color: #f9f9f9;
            border-bottom: 1px solid #ccc;
            padding: 10px 150px;
            position: relative;
        }

        header .top-nav {
            display: flex;
            justify-content: flex-end;
            align-items: center;
        }

        header nav a {
            margin-left: 15px;
            text-decoration: none;
            font-size: 14px;
            color: #0073e6;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        header .title-row {
            margin-top: 15px;
        }

        header .title-row h1 {
            font-size: 28px;
            color: #555;
        }

        header .subtitle {
            font-size: 16px;
            color: #666;
            margin-top: 5px;
        }

        .elegant-banner {
            text-align: right;
            margin-top: 10px;
        }

        .elegant-banner img {
            width: 400px;
            height: auto;
            border-radius: 5px;
            border: 1px solid #ddd;
        }

        /* Navbar */
        .navbar {
            background-color: #201f1f;
            color: #fff;
            width: 80%;
            max-width: 1100px;
            margin: 0 auto;
            padding: 10px 0;
            text-align: center;
            border-radius: 5px;
        }

        .navbar a {
            text-decoration: none;
            color: #fff;
            font-size: 16px;
            margin: 0 15px;
        }

        .navbar a:hover {
            text-decoration: underline;
        }

        /* New Banner */
        .new-banner {
            display: flex;
            justify-content: center;
            margin: 20px auto;
        }

        .new-banner img {
            width: 90%;
            max-width: 1000px;
            height: auto;
            border-radius: 5px;
            border: 1px solid #ddd;
        }

        /* Main Container */
        .main {
            display: flex;
            flex-direction: column;
            max-width: 1100px;
            margin: 20px auto;
            gap: 20px;
            padding: 0 10px;
        }

        /* Left Section */
        .content {
            background: #fff;
            border: 1px solid #ddd;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .content h2 {
            font-size: 20px;
            margin-bottom: 15px;
        }

        .images-row {
            display: flex;
            justify-content: space-between;
            gap: 10px;
            margin-bottom: 20px;
        }

        .images-row img {
            flex: 1;
            width: 100%;
            max-width: calc(33.33% - 10px);
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        /* New Section */
        .offer-section {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 20px;
            background: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .offer-title {
            font-size: 20px;
            font-weight: bold;
            color: #333;
        }

        .offer-note {
            font-size: 16px;
            color: #666;
            margin-top: 5px;
        }

        .offer-column {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
            margin-top: 10px;
        }

        .offer-box {
            background: #f9f9f9;
            border: 1px solid #ddd;
            text-align: center;
            padding: 20px;
            font-weight: bold;
            border-radius: 5px;
        }

        .sponsor-section {
            text-align: center;
        }

        .sponsor-section img {
            width: 100%;
            max-width: 300px;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        .sponsor-row {
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .sponsor-row img {
            width: 100%;
            max-width: 145px;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        /* Line Navbar */
        .line-navbar {
            background-color: #333;
            color: #fff;
            padding: 10px;
            margin-top: 20px;
            text-align: left;
        }

        .line-navbar .title {
            font-size: 18px;
            font-weight: bold;
        }

        .line-navbar .note {
            margin-top: 5px;
            font-size: 14px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            font-size: 14px;
            margin-top: 20px;
        }

        footer a {
            color: #ffa500;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Copyright Section */
        .copyright {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px;
            font-size: 14px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="top-nav">
            <nav>
                <a href="#">Home</a>
                <a href="#">Submit a Template</a>
                <a href="#">Contact Us</a>
                <a href="#">Search</a>
                <a href="#">Advertise</a>
            </nav>
        </div>
        <div class="title-row">
            <h1>Free CSS</h1>
            <p class="subtitle">Free CSS Template, CSS Layout & More</p>
        </div>
        <div class="elegant-banner">
            <img src="c:\Users\user\Desktop\elegantthemes-468x60.gif" alt="Elegant Banner">
        </div>
    </header>

    <!-- Navbar -->
    <div class="navbar">
        <a href="#">Free CSS Templates</a>
        <a href="#">Premium CSS Templates</a>
        <a href="#">Free CSS Layouts</a>
        <a href="#">Free CSS Menus</a>
    </div>

    <!-- New Banner -->
    <div class="new-banner">
        <img src="c:\Users\user\Desktop\elegantthemes-900x120.jpg" alt="Elegant Themes Banner">
    </div>

    <!-- Main Section -->
    <div class="main">
        <!-- Left Content -->
        <div class="content">
            <h2>LATEST FREE CSS TEMPLATES</h2>
            <div class="images-row">
                <img src="C:\Users\user\Desktop\oxer.jpg" alt="Oxer Banner">
                <img src="C:\Users\user\Desktop\neogym.jpg" alt="NeoGym Banner">
                <img src="c:\Users\user\Desktop\carvilla.jpg" alt="CarVilla Banner">
            </div>

            <!-- New Section -->
            <div class="offer-section">
                <div>
                    <div class="offer-title">WHAT'S ON OFFER</div>
                    <div class="offer-column">
                        <div class="offer-box">
                            <div class="offer-title">SYLVESTER</div>
                            <div class="offer-note">sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                </div>
                        </div>
                        <div class="offer-box">
                            <div class="offer-title">SYLVESTER</div>
                            <div class="offer-note">sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                </div>
                        </div>
                        <div class="offer-box">
                            <div class="offer-title">SYLVESTER</div>
                            <div class="offer-note">sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                </div>
                        </div>
                        <div class="offer-box">
                            <div class="offer-title">SYLVESTER</div>
                            <div class="offer-note">sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                sylester you are the best students and the best and the best
                                </div>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="offer-title">OUR SPONSORS</div>
                    <div class="sponsor-section">
                        <img src="c:\Users\user\Desktop\elegantthemes-300x250.gif" alt="Desktop elegant-banner Sponsor img">
                        <div class="sponsor-row">
                            <img src="c:\Users\user\Desktop\advertise-here-125x125.png" alt="Desktp advertise images-row">
                            <img src="c:\Users\user\Desktop\1733301760-125x125-4.png" alt="Desktop img">
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Line Navbar -->
        <div class="line-navbar">
            <div class="title">Free CSS.com</div>
            <div class="note">Bringing you the best in CSS templates, layouts, and designs.</div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Free CSS. All Rights Reserved. | <a href="#">Terms of Use</a></p>
    </footer>

    </div>
</body>
</html>
