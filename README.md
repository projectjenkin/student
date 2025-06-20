<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Student Login Portal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4f8;
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
    }

    .login-container {
      background-color: white;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      width: 300px;
    }

    .login-container h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    .form-group {
      margin-bottom: 15px;
    }

    .form-group label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    .form-group input {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .login-button {
      width: 100%;
      padding: 10px;
      background-color: #3498db;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    .login-button:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>

  <div class="login-container">
    <h2>Student Login</h2>
    <form action="/login" method="POST">
      <div class="form-group">
        <label for="email">Email ID:</label>
        <input type="email" id="email" name="email" required />
      </div>

      <div class="form-group">
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required />
      </div>

      <b

