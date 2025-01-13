<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Login</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <div class="login-box">
            <h1>Instagram</h1>
            <form>
                <input type="text" placeholder="Phone number, username, or email" required>
                <input type="password" placeholder="Password" required>
                <button type="submit">Log In</button>
            </form>
            <div class="separator">OR</div>
            <button class="facebook-login">Log in with Facebook</button>
            <a href="#" class="forgot-password">Forgot password?</a>
        </div>
        <div class="signup-box">
            <p>Don't have an account? <a href="#">Sign up</a></p>
        </div>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #fafafa;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.login-container {
    width: 100%;
    max-width: 350px;
    text-align: center;
}

.login-box {
    background-color: #fff;
    border: 1px solid #dbdbdb;
    padding: 20px;
    border-radius: 8px;
    margin-bottom: 10px;
}

h1 {
    font-family: 'Billabong', sans-serif;
    font-size: 2.5rem;
    color: #262626;
    margin-bottom: 20px;
}

form input {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #dbdbdb;
    border-radius: 4px;
    background-color: #fafafa;
}

button {
    width: 100%;
    padding: 10px;
    background-color: #0095f6;
    color: #fff;
    border: none;
    border-radius: 4px;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background-color: #007dc5;
}

.separator {
    margin: 20px 0;
    color: #8e8e8e;
    position: relative;
    font-size: 0.9rem;
}

.separator:before, .separator:after {
    content: "";
    height: 1px;
    background-color: #dbdbdb;
    position: absolute;
    top: 50%;
    width: 40%;
}

.separator:before {
    left: 0;
}

.separator:after {
    right: 0;
}

.facebook-login {
    background-color: transparent;
    color: #385185;
    font-weight: bold;
    border: none;
    cursor: pointer;
    margin-bottom: 10px;
}

.facebook-login:hover {
    text-decoration: underline;
}

.forgot-password {
    color: #00376b;
    font-size: 0.9rem;
    text-decoration: none;
}

.forgot-password:hover {
    text-decoration: underline;
}

.signup-box {
    background-color: #fff;
    border: 1px solid #dbdbdb;
    padding: 10px;
    border-radius: 8px;
}
