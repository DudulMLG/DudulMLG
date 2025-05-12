git clone https://github.com/username/username.github.io
cd username.github.io
echo "<paste <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yaa Kena Rickroll</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #121212;
            color: white;
            padding: 20px;
            margin: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            min-height: 100vh;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 30px;
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            max-width: 100%;
            margin: 0 auto;
            background: #000;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }
        .footer {
            margin-top: 30px;
            font-size: 0.8rem;
            color: #aaa;
        }
    </style>
</head>
<body>
    <h1>Yaa Kena Rickroll</h1>
    
    <div class="video-container">
        <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ?autoplay=1" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </div>
    
    <div class="footer">
        Never gonna give you up, never gonna let you down...
    </div>
</body>
</html>>" > index.html
git add .
git commit -m "Upload Rick Roll"
git push
