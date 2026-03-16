<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Splash Page</title>
    
    <style>
        /* 1. Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: radial-gradient(circle, #2c3e50 0%, #000000 100%);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Times New Roman', serif; /* Classic elegant font */
            color: #d4af37; /* Soft Gold color */
        }

        #splash-card {
            text-align: center;
            padding: 60px 40px;
            border: 1px solid rgba(212, 175, 55, 0.3); /* Subtle gold border */
            background: rgba(0, 0, 0, 0.6);
            backdrop-filter: blur(5px);
            max-width: 500px;
            width: 90%;
            letter-spacing: 2px;
        }

        /* 3. Typography Styles */
        #full-name {
            font-size: 3rem;
            font-weight: 300;
            text-transform: uppercase;
            margin-bottom: 5px;
            border-bottom: 1px solid #d4af37;
            display: inline-block;
            padding-bottom: 10px;
        }

        .academic-info {
            font-size: 1rem;
            color: #ffffff;
            margin-top: 15px;
            font-style: italic;
            letter-spacing: 3px;
        }

        #bio-text {
            margin: 30px 0;
            color: #bdc3c7;
            line-height: 1.8;
            font-family: 'Arial', sans-serif;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }

        /* 4. Social Media Links */
        .social-container {
            margin-top: 40px;
        }

        .link-item {
            text-decoration: none;
            color: #d4af37;
            margin: 0 15px;
            font-size: 0.8rem;
            text-transform: uppercase;
            transition: 0.4s;
            border: 1px solid transparent;
            padding: 5px 10px;
        }

        .link-item:hover {
            color: #ffffff;
            border: 1px solid #ffffff;
        }
    </style>
</head>
<body>

    <div id="splash-card">
        <h1 id="full-name">JANNA ROSELLE M. FORMOSO</h1>
        <p class="academic-info">Bachelor of Science in Computer Engineering</p>

        <p id="bio-text">
            A 22-year-old soul fueled by wildflowers and fresh air. Finding beauty in the little things.
        </p>

        <div class="social-container">
            <a href="https://www.instagram.com/jannarosellle/?__pwa=1" class="link-item">Instagram</a>
            <a href="https://web.facebook.com/janna.roselle" class="link-item">Facebook</a>
            <a href="https://github.com/janna-17" class="link-item">Github</a>
        </div>
    </div>

</body>
</html>
