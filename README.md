<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Philippine Artistry Art Gallery</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
  
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4eccf; 
            background-image: linear-gradient(to bottom, rgba(255,255,255,0.5), rgba(255,255,255,0.2));
            color: #3e2723;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .serif-font { font-family: Georgia, 'Times New Roman', serif; }
        .sans-font { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }

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
            gap: 40px;
        }

        .nav-links a {
            text-decoration: none;
            color: #efebe9;
            font-weight: bold;
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: #ffcc80;
        }

        .main-container {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            text-align: center;
            width: 100%;
        }

        .header-section {
            margin-bottom: 30px;
        }

        h1.welcome-title {
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 5px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        h2.gallery-name {
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 1.5rem;
            font-style: italic;
            color: #6d4c41;
            font-weight: normal;
        }

        .login-card {
            background-color: #fff;
            padding: 40px 30px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 400px;
            border: 1px solid #d7ccc8;
        }

        h3.login-heading {
            font-family: Georgia, 'Times New Roman', serif;
            font-size: 2rem;
            margin-bottom: 25px;
            color: #4e342e;
        }

        .input-group {
            margin-bottom: 15px;
        }

        .input-field {
            width: 100%;
            padding: 12px 15px;
            font-size: 1rem;
            border: 2px solid #a1887f;
            border-radius: 6px;
            outline: none;
            color: #555;
        }

        .input-field:focus {
            border-color: #5d4037;
        }

        .login-button {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            font-size: 1.1rem;
            font-weight: bold;
            color: white;
            background-color: #5d4037;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-family: Georgia, 'Times New Roman', serif;
            transition: background-color 0.3s;
        }

        .login-button:hover {
            background-color: #8d6e63;
        }

        .signup-text {
            margin-top: 20px;
            font-size: 0.9rem;
            color: #5d4037;
        }

        .signup-link {
            color: #bf360c;
            font-weight: bold;
            text-decoration: none;
        }

        .signup-link:hover {
            text-decoration: underline;
        }

        .footer-section {
            margin-top: auto;
            padding: 20px;
            text-align: center;
            font-size: 0.9rem;
            color: #5d4037;
        }

        .quote {
            font-family: Georgia, 'Times New Roman', serif;
            font-style: italic;
            font-size: 1.1rem;
            margin-bottom: 10px;
            display: block;
        }
    </style>
</head>
<body>

    <nav class="top-nav">
        <div class="nav-links">
            <a href="#home">Home</a>
            <a href="#tutorials">Tutorials</a>
            <a href="#artists">Artists & History</a>
        </div>
    </nav>

    <main class="main-container">
        
        <header class="header-section">
            <h1 class="welcome-title">Welcome!</h1>
            <h2 class="gallery-name">Philippine Artistry Art Gallery</h2>
        </header>

        <section class="login-card">
            <h3 class="login-heading">Log-in</h3>
            
            <form action="#" method="post">
                <div class="input-group">
                    <input type="text" name="username" class="input-field" placeholder="Username" required>
                </div>
                <div class="input-group">
                    <input type="password" name="password" class="input-field" placeholder="Password" required>
                </div>
                <button type="submit" class="login-button">Log In</button>
            </form>

            <div class="signup-text">
                <p>or</p>
                <p>Sign-up here <a href="#signup" class="signup-link">click me</a></p>
            </div>
        </section>

    </main>

    <footer class="footer-section">
        <span class="quote">"Art isn't all about the details but on how you show your imagination"</span>
        <div class="contact-info">
            <p>contact@philippineartistry.com | 09989980979</p>
        </div>
    </footer>

</body>
</html>
