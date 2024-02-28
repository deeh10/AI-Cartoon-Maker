<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ToonTales Gallery</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Arial, sans-serif; /* Enhanced font family for a modern look */
            color: #333;
            background: #fafafa; /* Consistent background color for reduced glare */
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
            background-color: #ffffff; /* Light background for the gallery for contrast */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* Soft shadow for depth, similar to title-section */
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px; /* Rounded corners for images */
            object-fit: cover; /* Ensure images cover the space nicely */
            transition: transform 0.3s ease; /* Smooth transition for hover effect */
        }
        .gallery img:hover {
            transform: scale(1.05); /* Slight scale up on hover for an interactive feel */
            cursor: pointer;
        }
        .intro-text {
            text-align: center;
            padding: 20px;
            font-family: 'Comic Sans MS', 'Arial', sans-serif; /* Keeping the playful font for headings */
            background-color: #ffffff; /* Consistent styling with the title-section */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
            font-size: 0.9rem; /* Consistent footer styling with previous enhancements */
        }
    </style>
</head>
<body>

<div class="intro-text">
    <h1>Welcome to the ToonTales Gallery</h1>
    <p>Explore a world of imagination with our AI-generated artwork.</p>
</div>

<div class="gallery">
    <!-- Enhanced Image Placeholder -->
    <img src="https://i.imgur.com/XCoTNUA.jpg" alt="AI Generated Art 1">
    <img src="https://i.imgur.com/MDJXrmo.jpg" alt="AI Generated Art 2">
    <img src="https://i.imgur.com/9oFRibR.jpg" alt="AI Generated Art 3">
    <!-- Continue adding more images as needed -->
</div>

<footer>
    <p>Contact us at info@toontales.com</p>
    <p>&copy; 2024 ToonTales. All rights reserved.</p>
</footer>

</body>
</html>
