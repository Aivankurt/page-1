<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Philippine Artistry Art Gallery</title>
    <style>
        /* --- Reset & Base Styles --- */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            /* Using system fonts that look like the original design without needing external links */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4eccf; 
            background-image: linear-gradient(to bottom, rgba(255,255,255,0.5), rgba(255,255,255,0.2)), url('https://www.transparenttextures.com/patterns/cream-paper.png');
            color: #3e2723; 
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* --- Navigation Bar (Restored) --- */
        .top-nav {
            background-color: #5d4037;
            padding: 15px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            width: 100%;
        }

        .nav-links {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        .nav-links li a {
            text-decoration: none;
            color: #efebe9;
            font-weight: 600;
            font-family: Georgia, 'Times New Roman', serif; /* Matches the "Lora" look */
            transition: color 0.3s ease;
        }

        .nav-links li a:hover {
            color: #ffcc80; 
        }

        /* --- Layout Containers --- */
        .main-container {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 40px 20px;
            text-align: center;
            width: 100%;
            max-width: 500px;
            margin: auto;
        }

        /* --- Typography --- */
        h1.welcome-title {
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 10px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        h2.gallery-name {
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 1.4rem;
            font-style: italic;
            color: #6d4c41;
            margin-bottom: 40px;
        }

        h3.login-heading {
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 2rem;
            margin-bottom: 25px;
            color: #4e342e;
        }

        /* --- Login Card --- */
        .login-section {
            background-color: rgba(255, 255, 255, 0.85);
            padding: 40px 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            width: 100%;
            border: 1px solid #d7ccc8;
        }

        .input-group {
            margin-bottom: 20px;
        }

        .input-field {
            width: 100%;
            padding: 15px;
            font-size: 1rem;
            border: 2px solid #a1887f;
            border-radius: 8px;
            background-color: #fafafa;
            outline: none;
            transition: border-color 0.3s;
        }

        .input-field:focus {
            border-color: #5d4037;
        }

        .login-button {
            width: 100%;
            padding: 15px;
            font-size: 1.1rem;
            font-weight: bold;
            color: white;
            background-color: #5d4037;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s;
            font-family: Georgia, 'Times New Roman', serif;
        }

        .login-button:hover {
            background-color: #8d6e63;
        }

        .signup-area {
            margin-top: 25px;
            font-size: 0.9rem;
            color: #6d4c41;
        }

        /* --- Footer --- */
        .footer-section {
            margin-top: auto;
            padding: 30px 20px;
            text-align: center;
            font-size: 0.9rem;
            color: #5d4037;
            background-image: linear-gradient(to top, rgba(93, 64, 55, 0.1), transparent);
        }

        .quote {
            font-family: Georgia, 'Times New Roman', serif;
            font-style: italic;
            font-size: 1.1rem;
            margin-bottom: 15px;
            display: block;
        }
    </style>
</head>
<body>

    <nav class="top-nav">
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#tutorials">Tutorials</a></li>
            <li><a href="#artists">Artists & History</a></li>
        </ul>
    </nav>

    <main class="main-container">
        
        <header>
            <h1 class="welcome-title">Welcome!</h1>
            <h2 class="gallery-name">Philippine Artistry Art Gallery</h2>
        </header>

        <section class="login-section">
            <h3 class="login-heading">Log-in</h3>
            
            <form action="#" method="post">
                <div class="input-group">
                    <input type="text" id="username" name="username" class="input-field" placeholder="Username" required>
                </div>
                <div class="input-group">
                    <input type="password" id="password" name="password" class="input-field" placeholder="Password" required>
                </div>
                <button type="submit" class="login-button">Log In</button>
            </form>

            <div class="signup-area">
                <p>or Sign-up via Admin</p>
            </div>
        </section>

    </main>

    <footer class="footer-section">
        <span class="quote">"Art isn't all about the details but on how you show your imagination"</span>
        <div class="contact-info">
            <p>Contact us:</p>
            <p>contact@philippineartistry.com | 09989980979</p>
        </div>
    </footer>

</body>
</html>
