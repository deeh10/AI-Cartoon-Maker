<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ToonTales - Your Memories Reimagined</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Arial, sans-serif; /* Enhanced font family */
            color: #333;
            background: #fafafa; /* Light background to reduce glare */
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
        .title-section {
            text-align: center;
            padding: 20px;
            background-color: #ffffff; /* Light background for contrast */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* Soft shadow for depth */
        }
        .content {
            padding: 20px;
            line-height: 1.6; /* Improved readability */
        }
        h1, h2 {
            font-family: 'Comic Sans MS', 'Arial', sans-serif; /* Playful font for titles */
            color: #007bff; /* Thematic color for headers */
        }
        .feature, .epic {
            margin-bottom: 20px;
        }
        .cta-button {
            display: inline-block;
            background-color: #ff5722; /* Brighter, more engaging button color */
            color: white;
            padding: 12px 24px; /* Slightly larger padding for better touch targets */
            text-decoration: none;
            border-radius: 8px; /* More pronounced rounded corners */
            transition: background-color 0.3s ease; /* Smooth transition for hover effect */
        }
        .cta-button:hover {
            background-color: #e64a19; /* Darker shade on hover for feedback */
        }
        footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
            font-size: 0.9rem; /* Slightly smaller font size for footer */
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

<!-- Embedding Audio File -->
<audio autoplay loop>
    <source src="Cartoon Dreamland.mp3" type="audio/mpeg">
    Your browser does not support the audio tag.
</audio>

<div class="title-section">
    <h1>ToonTales - Your Memories Reimagined</h1>
    <p>Transforming your memorable moments into engaging cartoon stories.</p>
    <a href="./second_page.html" class="cta-button">Get Started</a>
</div>

<div class="content" id="get-started">
    <h2>How ToonTales Works</h2>
    <p>Welcome to ToonTales 🌟, where your memories are transformed into captivating cartoon stories! Perfect for sharing on social media, our AI-powered platform makes it easy to bring your travel, personal milestones, and everyday adventures to life in animated form. Whether it's an unforgettable trip, a graduation ceremony, or just a coffee date, ToonTales turns these moments into engaging visual stories with minimal effort on your part. Dive in and start sharing your stories today! 🚀💖</p>
</div>

<footer>
    <p>Contact us at info@toontales.com</p>
    <p>&copy; 2024 ToonTales. All rights reserved.</p>
</footer>

</body>
</html>
