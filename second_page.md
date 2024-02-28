<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ToonTales Gallery</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Arial, sans-serif; /* Enhanced font family for consistency */
            color: #333;
            background: #fafafa; /* Light background for a cohesive look */
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            object-fit: cover; /* Ensure images cover the area nicely */
        }
        .intro-text, .coming-soon {
            text-align: center;
            padding: 20px;
            background-color: #ffffff; /* Consistent background for text sections */
            margin: 20px 0; /* Add some margin for spacing */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* Soft shadow for depth */
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

<div class="intro-text">
    <h1>Welcome to the ToonTales Gallery</h1>
    <p>Explore a world of imagination with our AI-generated artwork.</p>
</div>

<div class="gallery">
    <!-- Example Image Placeholder -->
    <img src="https://i.imgur.com/XCoTNUA.jpg" alt="AI Generated Art 1">
    <img src="https://i.imgur.com/MDJXrmo.jpg" alt="AI Generated Art 2">
    <img src="https://i.imgur.com/9oFRibR.jpg" alt="AI Generated Art 3">
    <!-- Add more images as needed -->
</div>

<div class="coming-soon">
    <h2>More Features Coming Soon - Stay Tuned!</h2>
    <p>Our team is constantly working to bring you new and exciting features. Keep an eye on this space for updates!</p>
</div>

<footer>
    <p>Contact us at info@toontales.com</p>
    <p>&copy; 2024 ToonTales. All rights reserved.</p>
</footer>

</body>
</html>
