<html>
<head></head>
   
<body  bgcolor="pink">
   
   <h1 align ="center" style ="color:magenta">السلام عليكم </h1>


   <h2> <i> MY NAME IS P M ABRAR ISHRAQ TOHA </i> </h2> 
<hr>   

 <h3 align ="center"> <b>

 
  <a href="https://chithi.me/toha_2">
  <tt> <button> <h3 align ="center" style ="color:red">  ANYONE CAN TEXT ME </h3> </button> </tt> 
  </a>
  
</b>

</h3>

  
  <hr>
  
      <h6> <i>In my name </i> </h6>
   <h5> P=PRAMANIK </h5>
<h5> M=MUHAMMAD </h5>

 
<hr>
<h4 style = "color:blue" align ="center"> I will fill this web when I get free time. </h4>
<hr>

</body>
</html>








    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Login and Sign Up Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 400px;
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
        }
        .input-group {
            margin-bottom: 15px;
        }
        .input-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .input-group input, .input-group select {
            width: 100%;
            padding: 10px;
            margin: 5px 0 10px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        .button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            border: none;
            border-radius: 5px;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #45a049;
        }
        .additional-options {
            text-align: center;
            margin-top: 10px;
        }
        .additional-options a {
            color: #4CAF50;
            text-decoration: none;
            cursor: pointer;
        }
        .additional-options a:hover {
            text-decoration: underline;
        }
        .hidden {
            display: none;
        }
    </style>
    <script>
        function showForm(formId) {
            document.getElementById("login").classList.add("hidden");
            document.getElementById("signup").classList.add("hidden");
            document.getElementById("forgot-password-form").classList.add("hidden");
            document.getElementById(formId).classList.remove("hidden");
        }

        function sendCode() {
            alert("A verification code has been sent to your email.");
            document.getElementById("code").classList.remove("hidden");
        }
    </script>
</head>
<body>
    <div class="container" id="login">
        <h1>Login</h1>
        <form action="/login" method="post">
            <div class="input-group">
                <label for="username">Username or Email:</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="input-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <button type="submit" class="button">Login</button>
        </form>
        <div class="additional-options">
            <a onclick="showForm('forgot-password-form')">Forgot Password?</a><br>
            <a onclick="showForm('signup')">Sign Up</a>
        </div>
    </div>

    <div class="container hidden" id="signup">
        <h1>Sign Up</h1>
        <form action="/signup" method="post">
            <div class="input-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="input-group">
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required>
            </div>
            <div class="input-group">
                <label for="gender">Gender:</label>
                <select id="gender" name="gender" required>
                    <option value="">Select Gender</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>
            </div>
            <div class="input-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="input-group">
                <label for="phone">Phone Number (Bangladeshi +880):</label>
                <input type="tel" id="phone" name="phone" pattern="\+880[0-9]{9}" required>
            </div>
            <div class="input-group">
                <label for="whatsapp">WhatsApp Number:</label>
                <input type="tel" id="whatsapp" name="whatsapp" pattern="\+880[0-9]{9}" required>
            </div>
            <div class="input-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <button type="button" class="button" onclick="sendCode()">Sign Up</button>
        </form>
        <div class="input-group hidden" id="code">
            <label for="verification-code">Enter Verification Code:</label>
            <input type="text" id="verification-code" name="verification-code" required>
            <button type="submit" class="button">Verify</button>
        </div>
        <div class="additional-options">
            <a onclick="showForm('login')">Back</a>
        </div>
    </div>

    <div class="container hidden" id="forgot-password-form">
        <h1>Forgot Password</h1>
        <form action="/reset-password" method="post">
            <div class="input-group">
                <label for="reset-email">Email:</label>
                <input type="email" id="reset-email" name="email" required>
            </div>
            <button type="submit" class="button">Send Reset Code</button>
        </form>
        <div class="additional-options">
            <a onclick="showForm('login')">Back</a>
        </div>
    </div>
</body>
</html>
