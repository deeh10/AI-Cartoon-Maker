
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ToonTales - Your Memories Reimagined</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color: #333;
        }
        /* Adjusted to use video */
        .video-container {
            width: 100%;
            height: 60vh; /* Adjusted height */
            overflow: hidden;
            position: relative;
            background-color: black; /* Fallback color */
        }
        video {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Cover the container fully */
        }
        .title-section {
            text-align: center;
            padding: 20px;
        }
        .content {
            padding: 20px;
        }
        h1, h2 {
            text-align: center;
        }
        .feature, .epic {
            margin-bottom: 20px;
        }
        .cta-button {
            display: inline-block;
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }
        footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<!-- Video replaces the cover photo -->
<div class="video-container">
    <video autoplay muted loop>
        <source src="path_to_your_video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<div class="title-section">
    <h1>ToonTales - Your Memories Reimagined</h1>
    <p>Transforming your memorable moments into engaging cartoon stories.</p>
    <a href="./second_page.html" class="cta-button">Get Started</a>
</div>

<div class="content" id="get-started">
    <h2>How ToonTales Works</h2>
    <!-- Content sections remain unchanged -->
</div>

<footer>
    <p>Contact us at info@toontales.com</p>
    <p>&copy; 2024 ToonTales. All rights reserved.</p>
</footer>

</body>
</html>
