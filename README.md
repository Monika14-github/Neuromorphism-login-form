# Neuromorphism-login-form
....html.....
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <script src="script.js"></script>
    <html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Neumorphism Login/Registration Form | Webdevtrick.com</title>
  <link rel="stylesheet" href="style.css">
 
</head>
<body>
 
    <div class="main">
      <div class="container a-container" id="a-container">
        <form class="form" id="a-form" method="" action="">
          <h2 class="form_title title">Create Account</h2>
 
          <div class="form__icons">
            <img class="form__icon" src="https://webdevtrick.com/wp-content/uploads/facebook.svg" alt="">
            <img class="form__icon" src="https://webdevtrick.com/wp-content/uploads/twitter.svg">
            <img class="form__icon" src="https://webdevtrick.com/wp-content/uploads/linkedin.svg"></div>
            <span class="form__span">or use email for registration</span>
 
          <input class="form__input" type="text" placeholder="Name">
          <input class="form__input" type="text" placeholder="Email">
          <input class="form__input" type="password" placeholder="Password">
          <button class="form__button button submit">SIGN UP</button>
        </form>
      </div>
      <div class="container b-container" id="b-container">
        <form class="form" id="b-form" method="" action="">
          <h2 class="form_title title">Sign in to Website</h2>
 
          <div class="form__icons">
            <img class="form__icon" src="https://webdevtrick.com/wp-content/uploads/facebook.svg" alt="">
            <img class="form__icon" src="https://webdevtrick.com/wp-content/uploads/twitter.svg">
            <img class="form__icon" src="https://webdevtrick.com/wp-content/uploads/linkedin.svg"></div>
            <span class="form__span">or use your email account</span>
 
          <input class="form__input" type="text" placeholder="Email">
          <input class="form__input" type="password" placeholder="Password"><a class="form__link">Forgot your password?</a>
          <button class="form__button button submit">SIGN IN</button>
        </form>
      </div>
      <div class="switch" id="switch-cnt">
        <div class="switch__circle"></div>
        <div class="switch__circle switch__circle--t"></div>
        <div class="switch__container" id="switch-c1">
          <h2 class="switch__title title">Welcome Back !</h2>
          <p class="switch__description description">To keep connected with us please login with your personal info</p>
          <button class="switch__button button switch-btn">SIGN IN</button>
        </div>
        <div class="switch__container is-hidden" id="switch-c2">
          <h2 class="switch__title title">Hello Friend !</h2>
          <p class="switch__description description">Enter your personal details and start journey with us</p>
          <button class="switch__button button switch-btn">SIGN UP</button>
        </div>
      </div>
    </div>
 
  <script  src="function.js"></script>
  </body>
</html>
.....css.....
*, *::after, *::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  user-select: none;
}
 
 
body {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Montserrat', sans-serif;
  font-size: 12px;
  background-color: #ecf0f3;
  color: #a0a5a8;
}
 
 
.main {
  position: relative;
  width: 1000px;
  min-width: 1000px;
  min-height: 600px;
  height: 600px;
  padding: 25px;
  background-color: #ecf0f3;
  box-shadow: 10px 10px 10px #d1d9e6, -10px -10px 10px #f9f9f9;
  border-radius: 12px;
  overflow: hidden;
}
 
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  top: 0;
  width: 600px;
  height: 100%;
  padding: 25px;
  background-color: #ecf0f3;
  transition: 1.25s;
}
 
.form {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: 100%;
}
.form__icon {
  object-fit: contain;
  width: 30px;
  margin: 0 5px;
  opacity: .5;
  transition: .15s;
}
.form__icon:hover {
  opacity: 1;
  transition: .15s;
  cursor: pointer;
}
.form__input {
  width: 350px;
  height: 40px;
  margin: 4px 0;
  padding-left: 25px;
  font-size: 13px;
  letter-spacing: .15px;
  border: none;
  outline: none;
  font-family: 'Montserrat', sans-serif;
  background-color: #ecf0f3;
  transition: .25s ease;
  border-radius: 8px;
  box-shadow: inset 2px 2px 4px #d1d9e6, inset -2px -2px 4px #f9f9f9;
}
.form__input:focus {
  box-shadow: inset 4px 4px 4px #d1d9e6, inset -4px -4px 4px #f9f9f9;
}
.form__span {
  margin-top: 30px;
  margin-bottom: 12px;
}
.form__link {
  color: #181818;
  font-size: 15px;
  margin-top: 25px;
  border-bottom: 1px solid #a0a5a8;
  line-height: 2;
}
 
.title {
  font-size: 34px;
  font-weight: 700;
  line-height: 3;
  color: #181818;
}
 
.description {
  font-size: 14px;
  letter-spacing: .25px;
  text-align: center;
  line-height: 1.6;
}
 
.button {
  width: 180px;
  height: 50px;
  border-radius: 25px;
  margin-top: 50px;
  font-weight: 700;
  font-size: 14px;
  letter-spacing: 1.15px;
  background-color: #ff003d;
  color: #f9f9f9;
  box-shadow: 8px 8px 16px #d1d9e6, -8px -8px 16px #f9f9f9;
  border: none;
  outline: none;
}
 
.a-container {
  z-index: 100;
  left: calc(100% - 600px );
}
 
.b-container {
  left: calc(100% - 600px );
  z-index: 0;
}
 
.switch {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 400px;
  padding: 50px;
  z-index: 200;
  transition: 1.25s;
  background-color: #ecf0f3;
  overflow: hidden;
  box-shadow: 4px 4px 10px #d1d9e6, -4px -4px 10px #f9f9f9;
}
.switch__circle {
  position: absolute;
  width: 500px;
  height: 500px;
  border-radius: 50%;
  background-color: #ecf0f3;
  box-shadow: inset 8px 8px 12px #d1d9e6, inset -8px -8px 12px #f9f9f9;
  bottom: -60%;
  left: -60%;
  transition: 1.25s;
}
.switch__circle--t {
  top: -30%;
  left: 60%;
  width: 300px;
  height: 300px;
}
.switch__container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  position: absolute;
  width: 400px;
  padding: 50px 55px;
  transition: 1.25s;
}
.switch__button {
  cursor: pointer;
}
.switch__button:hover {
  box-shadow: 6px 6px 10px #d1d9e6, -6px -6px 10px #f9f9f9;
  transform: scale(0.985);
  transition: .25s;
}
.switch__button:active, .switch__button:focus {
  box-shadow: 2px 2px 6px #d1d9e6, -2px -2px 6px #f9f9f9;
  transform: scale(0.97);
  transition: .25s;
}
 
.is-txr {
  left: calc(100% - 400px );
  transition: 1.25s;
  transform-origin: left;
}
 
.is-txl {
  left: 0;
  transition: 1.25s;
  transform-origin: right;
}
 
.is-z200 {
  z-index: 200;
  transition: 1.25s;
}
 
.is-hidden {
  visibility: hidden;
  opacity: 0;
  position: absolute;
  transition: 1.25s;
}
 
.is-gx {
  animation: is-gx 1.25s;
}
 
@keyframes is-gx {
  0%, 10%, 100% {
    width: 400px;
  }
  30%, 50% {
    width: 500px;
  }
}
