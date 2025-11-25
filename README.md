<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Philippine Artistry Art Gallery Welcome</title>
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,700;1,400&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Open Sans', sans-serif;
          
            background-color: #f4eccf; 
            background-image: linear-gradient(to bottom, rgba(255,255,255,0.5), rgba(255,255,255,0.2)), url('https://www.transparenttextures.com/patterns/cream-paper.png');
            color: #3e2723; 
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        .top-nav {
        
            background-color: #5d4037;
            padding: 15px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
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
            font-family: 'Lora', serif;
            transition: color 0.3s ease;
        }

        .nav-links li a:hover {
            color: #ffcc80; 
        }

        .main-container {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 40px 20px;
            text-align: center;
            max-width: 600px;
            margin: auto;
        }

        .header-section {
            margin-bottom: 40px;
        }

        h1.welcome-title {
            font-family: 'Lora', serif;
            font-size: 3.5rem;
            font-weight: 700;
            color: #3e2723;
            margin-bottom: 10px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        h2.gallery-name {
            font-family: 'Lora', serif;
            font-size: 1.5rem;
            font-weight: 400;
            font-style: italic;
            color: #6d4c41;
        }

        .login-section {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            width: 100%;
            border: 1px solid #d7ccc8;
        }

        h3.login-heading {
            font-family: 'Lora', serif;
            font-size: 2rem;
            margin-bottom: 25px;
            color: #4e342e;
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
            font-family: 'Open Sans', sans-serif;
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
            font-family: 'Lora', serif;
        }

        .login-button:hover {
            background-color: #8d6e63;
        }

        .signup-area {
            margin-top: 25px;
            font-size: 0.9rem;
            color: #6d4c41;
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
            padding: 30px 20px;
            text-align: center;
            font-size: 0.9rem;
            color: #5d4037;
            background-image: linear-gradient(to top, rgba(93, 64, 55, 0.1), transparent);
        }

        .quote {
            font-family: 'Lora', serif;
            font-style: italic;
            font-size: 1.1rem;
            margin-bottom: 15px;
            display: block;
        }
        
        .contact-info p {
            margin: 5px 0;
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
        
        <header class="header-section">
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
                <p>or</p>
                <p>Sign-up here <a href="#signup" class="signup-link">click me</a></p>
            </div>
        </section>

    </main>

    <footer class="footer-section">
        <span class="quote">"Art isn't all about etc....."</span>
        <div class="contact-info">
            <p>or you can contact us via email or phone number:</p>
            <p>contact@philippineartistry.com or 09989980979</p>
        </div>
    </footer>

</body>
</html>
