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
            font-family: Arial, sans-serif;
            color: #3e2723; 
            min-height: 100vh;
            display: flex;
            flex-direction: column;

            background: 
                linear-gradient(rgba(244, 236, 207, 0.8), rgba(244, 236, 207, 0.8)), /* Light semi-transparent overlay */
                url('https://cdn.luxatic.com/wp-content/uploads/2019/02/Vincent-van-Gogh.jpg') no-repeat center center fixed; 
            background-size: cover; 
        }

        .nav {
            background-color: #5d4037; 
            padding: 15px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .nav-list {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 40px;
        }

        .nav-link {
            text-decoration: none;
            color: #efebe9; 
            font-weight: bold;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        .nav-link:hover {
            color: #ffcc80;
        }

        .main-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            text-align: center;
        }

        .header {
            margin-bottom: 30px;
        }

        .header-title {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 5px;
            text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.5);
        }

        .header-subtitle {
            font-size: 1.5rem;
            font-style: italic;
            color: #6d4c41; 
            font-weight: normal;
        }

        .login-card {
            background-color: rgba(255, 255, 255, 0.95); /* Slightly transparent white for backdrop */
            padding: 40px 30px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            width: 100%;
            max-width: 400px;
        }

        .login-heading {
            font-size: 2rem;
            margin-bottom: 25px;
            color: #4e342e;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-input {
            width: 100%;
            padding: 12px 15px;
            font-size: 1rem;
            border: 2px solid #a1887f;
            border-radius: 6px;
            outline: none;
        }

        .form-input:focus {
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
            text-decoration: none; 
            display: block; 
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

        .alert-message {
            padding: 10px;
            margin-bottom: 20px;
            border-radius: 4px;
            font-weight: bold;
            text-align: center;
            display: none; 
        }

        .alert-error {
            background-color: #ffebee;
            color: #F44336;
            border: 1px solid #F44336;
        }

        #login-trigger {
            display: none;
        }
        
        #login-trigger:checked ~ .alert-message {
            display: block;
        }

        .footer {
            margin-top: auto;
            padding: 20px;
            text-align: center;
            font-size: 0.9rem;
            color: #5d4037;
            background-color: rgba(244, 236, 207, 0.7); /* Added background for readability */
        }

        .footer-quote {
            font-style: italic;
            font-size: 1.1rem;
            margin-bottom: 10px;
            display: block;
        }
    </style>
</head>
<body>

    <nav class="nav">
    <ul class="nav-list">
    <li><a href="#home" class="nav-link">Home</a></li>
    <li><a href="#tutorials" class="nav-link">Tutorials</a></li>
    <li><a href="#artists" class="nav-link">Artists & History</a></li>
    </ul>
    </nav>

    <main class="main-content">
        
        <header class="header">
            <h1 class="header-title">Welcome!</h1>
            <h2 class="header-subtitle">Philippine Artistry Art Gallery</h2>
        </header>

        <section class="login-card">
        <h3 class="login-heading">Log-in</h3>
            
        <input type="radio" id="login-trigger" name="login-state" hidden>

        <div class="alert-message alert-error">
        Mock Error: Invalid login attempt. (Click the "Log In" button again to try again.)
        </div>

        <form action="#" method="post">
        <div class="form-group">
        <input type="text" id="username" name="username" class="form-input" placeholder="Username" required>
        </div>

        <div class="form-group">
        <input type="password" id="password" name="password" class="form-input" placeholder="Password" required>
        </div>
                
        <label for="login-trigger" class="login-button">Log In</label>
        </form>

        <div class="signup-text">
        <p>or</p>
        <p>Sign-up here <a href="#signup" class="signup-link">click me</a></p>
        </div>
        </section>

    </main>

    <footer class="footer">
    <span class="footer-quote">"Art isn't all about the details but on how you show your imagination"</span>
    <div class="contact-info">
    <p>contact@philippineartistry.com | 09989980979</p>
    </div>
    </footer>

</body>
</html>
