<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ToonTales - Your Memories Reimagined</title>
    <style>
        /* Your existing CSS styles */
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Arial, sans-serif;
            color: #333;
            background: #fafafa;
        }
        .video-container {
            width: 100%;
            height: 60vh;
            overflow: hidden;
            position: relative;
            background-color: black;
        }
        video {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .title-section, .content, h1, h2, .feature, .epic, .cta-button, footer {
            /* Your existing CSS styles */
        }
    </style>
</head>
<body>

<div class="video-container">
    <video autoplay muted loop>
        <source src="Cover video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<!-- Audio Element for Background Music -->
<audio autoplay loop>
    <source src="Cartoon Memory Melodies-1.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

<div class="title-section">
    <h1>ToonTales - Your Memories Reimagined</h1>
    <p>Transforming your memorable moments into engaging cartoon stories.</p>
    <a href="./second_page.html" class="cta-button">Get Started</a>
</div>

<div class="content" id="get-started">
    <!-- Your existing content -->
</div>

<footer>
    <!-- Your existing footer -->
</footer>

</body>
</html>
