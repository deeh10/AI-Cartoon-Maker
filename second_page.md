<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ToonTales Gallery</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Arial, sans-serif; /* Enhanced font family */
            color: #333;
            background: #fafafa; /* Light background to reduce glare */
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
            border-radius: 10px; /* Rounded corners for images */
        }
        .intro-text, .coming-soon {
            text-align: center;
            padding: 20px;
            background-color: #ffffff; /* Light background for contrast */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* Soft shadow for depth */
            margin: 20px 0; /* Added spacing */
        }
        footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
        /* New section for upcoming features */
        .coming-soon {
            font-size: 1.2em; /* Larger font size for emphasis */
            color: #007bff; /* Thematic color for this section */
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
    <p>More features coming soon - stay tuned!</p>
</div>

<footer>
    <p>Contact us at info@toontales.com</p>
    <p>&copy; 2024 ToonTales. All rights reserved.</p>
</footer>

</body>
</html>
