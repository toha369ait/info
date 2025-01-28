<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header, footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            z-index: 1000;
        }
        header {
            top: 0;
        }
        footer {
            bottom: 0;
        }
        nav {
            text-align: center;
            background-color: #444;
            padding: 10px 0;
            margin-top: 60px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 80px 20px 60px;
            max-width: 1000px;
            margin: 0 auto;
        }
        section {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            text-align: center;
            text-decoration: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
            margin: 5px;
        }
        .button:hover {
            background-color: #0056b3;
        }
        .social-icons {
            text-align: center;
            margin-top: 20px;
        }
        .social-icons a {
            margin: 0 10px;
            text-decoration: none;
            font-size: 24px;
            transition: color 0.3s ease;
        }
        .social-icons a:hover {
            color: #0056b3;
        }
        .social-icon-twitter {
            color: #1DA1F2;
        }
        .social-icon-facebook {
            color: #1877F2;
        }
        .social-icon-instagram {
            color: #C13584;
        }
        .social-icon-reddit {
            color: #FF4500;
        }
        .social-icon-threads {
            color: #3897F0;
        }
        .social-icon-tiktok {
            color: #010101;
        }
        .social-icon-bluesky {
            color: #0096D6;
        }
        .social-icon-quora {
            color: #B92B27;
        }
        .social-icon-linkedin {
            color: #0e76a8;
        }
        .follow-me {
            font-size: 28px;
            font-weight: bold;
            color: #333;
            margin-bottom: 15px;
            text-transform: uppercase;
        }

        @media (max-width: 768px) {
            header, footer {
                padding: 10px 0;
            }
            .container {
                padding: 80px 10px 60px;
            }
            .social-icons a {
                font-size: 20px;
            }
            .button {
                font-size: 14px;
                padding: 8px 16px;
            }
        }

        @media (max-width: 480px) {
            nav a {
                display: block;
                margin: 5px 0;
            }
            .social-icons a {
                font-size: 18px;
            }
            .button {
                font-size: 14px;
                padding: 8px 16px;
                width: 100%;
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1> السلام عليكم </h1>
    <p>T | T | T</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm P M ABRAR ISHRAQ TOHA. I love learning new technologies and improving my skills.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to send me an email or call me:</p>
        <a href="mailto:pm-toha6@protonmail.com" class="button">Email Me</a>
        <a href="tel:+8801" class="button">Call Me</a>
        <a href="https://eeejshshsh.jsbb.com" class="button">Anyone Can Text Me</a>
    </section>

    <div class="social-icons">
        <h3 class="follow-me">Follow Me</h3>
        <a href="https://twitter.com/gshhsb09" target="_blank" title="Twitter" class="social-icon-twitter">Twitter</a>
        <a href="https://hdhshshsh.hshsg.uicom" target="_blank" title="Facebook" class="social-icon-facebook">Facebook</a>
        <a href="https://instagram.com/yourusername" target="_blank" title="Instagram" class="social-icon-instagram">Instagram</a>
        <a href="https://reddit.com/user/yourusername" target="_blank" title="Reddit" class="social-icon-reddit">Reddit</a>
        <a href="https://threads.net/yourusername" target="_blank" title="Threads" class="social-icon-threads">Threads</a>
        <a href="https://tiktok.com/@yourusername" target="_blank" title="TikTok" class="social-icon-tiktok">TikTok</a>
        <a href="https://bsky.app/profile/yourusername" target="_blank" title="Bluesky" class="social-icon-bluesky">Bluesky</a>
        <a href="https://quora.com/profile/yourusername" target="_blank" title="Quora" class="social-icon-quora">Quora</a>
        <a href="https://www.linkedin.com/in/yourusername" target="_blank" title="LinkedIn" class="social-icon-linkedin">LinkedIn</a>
    </div>

</div>

<footer>
    <p>&copy; 2023 P M Abrar Ishraq Toha. All rights reserved.</p>
</footer>

</body>
</html>
