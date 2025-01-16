<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
    />
    <title>Đăng Nhập</title>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        font-family: "Arial", sans-serif;
        background-color: #ffb1ef;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
      }

      .login-box {
        width: 320px;
        padding: 40px;
        background-color: #ff0ea7;
        box-shadow: 0 4px 8px rgb(255, 53, 53);
        border-radius: 8px;
        text-align: center;
      }

      .login-box h1 {
        margin-bottom: 20px;
        color: #ffffff;
      }

      .input-field {
        margin-bottom: 15px;
      }

      .input-field input {
        width: 100%;
        padding: 10px;
        font-size: 16px;
        border: 2px solid #ff00f7;
        border-radius: 4px;
        outline: none;
        transition: all 0.3s ease;
      }

      .input-field input:focus {
        border-color: #ff9cfd;
        box-shadow: 0 0 5px rgb(255, 144, 218);
      }

      .btn-login {
        width: 100%;
        padding: 12px;
        background-color: #fc9aff;
        color: white;
        font-size: 18px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        transition: background-color 0.3s ease;
      }

      .signup-link {
        margin-top: 20px;
        font-size: 14px;
      }

      .signup-link a {
        color: #d727f6;
        text-decoration: none;
      }

      .signup-link a:hover {
        text-decoration: underline;
      }
    </style>
  </head>
  <body>
    <div class="login-box">
      <h1>Đăng Nhập</h1>
      <form action="/submit" method="POST">
        <div class="input-field">
          <input
            type="text"
            id="username"
            name="username"
            placeholder="Tên đăng nhập"
            required
          />
        </div>
        <div class="input-field">
          <input
            type="password"
            id="password"
            name="password"
            placeholder="Mật khẩu"
            required
          />
        </div>
        <button type="submit" class="btn-login">Đăng Nhập</button>
      </form>
    </div>
  </body>
</html>
