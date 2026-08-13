<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #667eea, #764ba2);
            padding: 20px;
        }

        .form-container {
            width: 100%;
            max-width: 430px;
            background: rgba(255, 255, 255, 0.96);
            padding: 35px;
            border-radius: 20px;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.2);
        }

        .form-container h2 {
            text-align: center;
            color: #2d3748;
            margin-bottom: 8px;
            font-size: 30px;
        }

        .subtitle {
            text-align: center;
            color: #718096;
            margin-bottom: 28px;
            font-size: 14px;
        }

        .input-group {
            margin-bottom: 18px;
        }

        .input-group label {
            display: block;
            color: #2d3748;
            font-weight: 600;
            margin-bottom: 7px;
            font-size: 14px;
        }

        .input-group input {
            width: 100%;
            padding: 13px 15px;
            border: 1px solid #e2e8f0;
            border-radius: 10px;
            outline: none;
            font-size: 15px;
            transition: 0.3s;
            background: #f8fafc;
        }

        .input-group input:focus {
            border-color: #6c63ff;
            background: #fff;
            box-shadow: 0 0 0 3px rgba(108, 99, 255, 0.12);
        }

        .terms {
            display: flex;
            align-items: center;
            gap: 8px;
            margin: 8px 0 22px;
            font-size: 13px;
            color: #718096;
        }

        .terms input {
            accent-color: #6c63ff;
        }

        .terms a {
            color: #6c63ff;
            text-decoration: none;
            font-weight: 600;
        }

        .register-btn {
            width: 100%;
            padding: 14px;
            border: none;
            border-radius: 10px;
            background: linear-gradient(135deg, #6c63ff, #8b5cf6);
            color: white;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
            box-shadow: 0 8px 20px rgba(108, 99, 255, 0.3);
        }

        .register-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 12px 25px rgba(108, 99, 255, 0.4);
        }

        .login-text {
            text-align: center;
            margin-top: 20px;
            color: #718096;
            font-size: 14px;
        }

        .login-text a {
            color: #6c63ff;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <div class="form-container">

        <h2>Create Account</h2>
        <p class="subtitle">Join us and get started today!</p>

        <form>

            <div class="input-group">
                <label>Full Name</label>
                <input type="text" placeholder="Enter your full name" required>
            </div>

            <div class="input-group">
                <label>Email Address</label>
                <input type="email" placeholder="Enter your email" required>
            </div>

            <div class="input-group">
                <label>Phone Number</label>
                <input type="tel" placeholder="Enter your phone number" required>
            </div>

            <div class="input-group">
                <label>Password</label>
                <input type="password" placeholder="Create a password" required>
            </div>

            <div class="input-group">
                <label>Confirm Password</label>
                <input type="password" placeholder="Confirm your password" required>
            </div>

            <div class="terms">
                <input type="checkbox" required>
                <span>I agree to the <a href="#">Terms & Conditions</a></span>
            </div>

            <button type="submit" class="register-btn">
                Create Account
            </button>

        </form>

        <p class="login-text">
            Already have an account?
            <a href="#">Login</a>
        </p>

    </div>

</body>
</html>
