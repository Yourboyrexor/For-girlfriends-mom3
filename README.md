<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Message for You</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            overflow: hidden;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #ffcc99;
        }

        .parallax {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://source.unsplash.com/1600x900/?nature,sky') no-repeat center center fixed;
            background-size: cover;
            z-index: -1;
            animation: moveBackground 15s linear infinite;
        }

        header {
            font-size: 3em;
            color: #fff;
            font-weight: 600;
            margin-bottom: 30px;
            animation: fadeIn 2s ease-out;
        }

        main {
            background: rgba(255, 255, 255, 0.85);
            padding: 50px;
            border-radius: 25px;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 700px;
            font-size: 1.2em;
            line-height: 1.8;
            animation: fadeInUp 2s ease-out;
        }

        p {
            color: #555;
            margin: 15px 0;
        }

        .highlight {
            color: #ff6347;
            font-weight: bold;
        }

        footer {
            margin-top: 40px;
            font-size: 1.1em;
            color: #fff;
            background-color: #ff6347;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            animation: fadeIn 3s ease-out;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }

        footer a:hover {
            color: #ffcc99;
        }

        @media screen and (max-width: 600px) {
            header {
                font-size: 2.5em;
            }

            main {
                padding: 25px;
            }

            footer {
                font-size: 1em;
            }
        }

        /* Animation for fade-in, slide-up, and parallax background */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @keyframes fadeInUp {
            0% { transform: translateY(30px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        @keyframes moveBackground {
            0% { background-position: 0 0; }
            100% { background-position: 100% 0; }
        }
    </style>
</head>
<body>

    <div class="parallax"></div>

    <header>
        A Special Message for You
    </header>

    <main>
        <p>Dear <span class="highlight">Yuri</span>,</p>
        <p>Even though we haven't had the chance to meet in person yet, I wanted to take a moment to share how much I admire your <span class="highlight">kindness</span> and the way you bring joy to those around you.</p>
        <p>The way you approach life and spread positivity, even from afar, is truly inspiring. I feel fortunate to know someone like you, and I look forward to the day we can connect in person.</p>
        <p>Until then, I just wanted to send some appreciation your way and let you know how much you're appreciated.</p>
        <p>With admiration, <br> Kaiden</p>
    </main>

    <footer>
        &copy; 2025 A Special Message for You | <a href="mailto:kaidenhively2009@gmail.com">Contact Me</a>
    </footer>

</body>
</html>
