<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday</title>
    <style>
        @keyframes fadeInOut {
            0%, 100% { opacity: 0; }
            50% { opacity: 1; }
        }
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            margin: 0;
            text-align: center;
            background-color: #f0f8ff; /* Light blue background color */
        }
        .bouquet {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .bouquet img {
            width: 50%; /* Reduce the image size */
            height: auto;
            border-radius: 10px;
        }
        .bouquet p {
            font-size: 1.2em;
            color: #666;
        }
        .birthday-message {
            font-size: 3em; /* Increase font size */
            color: #ff6600; /* Use a more vibrant color */
            font-weight: bold;
            animation: fadeInOut 5s infinite; /* Adjust animation duration */
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="birthday-message">Happy Birthday Adya!</div>
    <div class="bouquet">
        <img src="https://imgur.com/tw2c0gf.jpeg" alt="Sunflower Bouquet">
        <p>Wishing you a day filled with love and joy!</p>
    </div>
</body>
</html>
