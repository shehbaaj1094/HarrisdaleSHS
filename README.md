<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Harrisdale Login</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      margin: 0;
      background: #e6f0fb;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .background {
      position: absolute;
      z-index: -1;
      width: 100%;
      height: 100%;
      overflow: hidden;
    }

    .blob {
      position: absolute;
      border-radius: 50%;
      opacity: 0.6;
      filter: blur(50px);
    }

    .blob1 {
      background: #f85a3e;
      width: 600px;
      height: 600px;
      top: -100px;
      left: -100px;
    }

    .blob2 {
      background: #008dff;
      width: 500px;
      height: 500px;
      bottom: 50px;
      left: 100px;
    }

    .blob3 {
      background: #ffca28;
      width: 400px;
      height: 400px;
      top: -100px;
      right: -100px;
    }

    .login-box {
      background: white;
      padding: 30px 40px;
      border-radius: 12px;
      width: 320px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
      text-align: center;
    }

    .login-box img {
      width: 100px;
      margin-bottom: 10px;
    }

    h2 {
      margin: 10px 0 20px;
      font-size: 20px;
    }

    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 6px;
      border: 1px solid #ccc;
    }

    button {
      width: 100%;
      padding: 12px;
      background: #0073e6;
      color: white;
      border: none;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
    }

    .alt-login {
      margin-top: 15px;
      font-size: 14px;
    }

    .alt-login a {
      color: #0073e6;
      text-decoration: none;
    }

    .remember {
      text-align: left;
      margin: 10px 0;
    }

    .remember input {
      margin-right: 5px;
    }
  </style>
</head>
<body>

<div class="background">
  <div class="blob blob1"></div>
  <div class="blob blob2"></div>
  <div class="blob blob3"></div>
</div>

<div class="login-box">
  <img src="https://upload.wikimedia.org/wikipedia/en/3/34/Harrisdale_Senior_High_School_logo.png" alt="School Logo">
  <h2>Harrisdale Senior High School</h2>
  <form>
    <input type="text" placeholder="Username" required>
    <input type="password" placeholder="Password" required>
    <div class="remember">
      <label><input type="checkbox" /> Remember me</label>
    </div>
    <button type="submit">Sign in</button>
  </form>
  <div class="alt-login">
    <p>Can't access your account? <a href="#">Click here</a></p>
  </div>
</div>

</body>
</html>
