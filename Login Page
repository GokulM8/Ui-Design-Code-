# Ui-Design-Code-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BioRx-AI</title>
    <style>
        :root {
            --black: #000000;
            --white: #ffffff;
            --gray-light: #f5f5f5;
            --gray-dark: #222222;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, var(--white) 0%, var(--gray-light) 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .login-container {
            background-color: var(--white);
            width: 100%;
            max-width: 480px;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            border: 1px solid var(--black);
        }
        
        .brand-header {
            background-color: var(--white);
            color: var(--black);
            padding: 20px;
            text-align: center;
            border-bottom: 1px solid var(--black);
        }
        
        .brand-header h1 {
            font-size: 28px;
            font-weight: 700;
            letter-spacing: -0.5px;
        }
        
        .login-header {
            background-color: var(--black);
            color: var(--white);
            padding: 20px;
            text-align: center;
        }
        
        .logo-container {
            width: 80px;
            height: 80px;
            margin: 0 auto 15px;
            background-color: var(--white);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            border: 2px solid var(--black);
        }
        
        .logo-container img {
            width: 60px;
            height: 60px;
        }
        
        .login-header h2 {
            font-size: 22px;
            font-weight: 600;
            margin-bottom: 5px;
        }
        
        .login-header p {
            font-size: 14px;
            opacity: 0.8;
        }
        
        .login-form {
            padding: 30px;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: var(--gray-dark);
            font-size: 14px;
        }
        
        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid var(--black);
            border-radius: 6px;
            font-size: 16px;
            background-color: var(--white);
            color: var(--black);
            transition: all 0.3s ease;
        }
        
        .form-control:focus {
            outline: none;
            box-shadow: 0 0 0 2px rgba(0, 0, 0, 0.1);
        }
        
        .form-footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            font-size: 14px;
        }
        
        .remember-me {
            display: flex;
            align-items: center;
        }
        
        .remember-me input {
            margin-right: 8px;
        }
        
        .forgot-password a {
            color: var(--black);
            text-decoration: none;
            font-weight: 500;
        }
        
        .btn {
            display: block;
            width: 100%;
            padding: 14px;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .btn-primary {
            background-color: var(--black);
            color: var(--white);
        }
        
        .btn-primary:hover {
            background-color: var(--gray-dark);
        }
        
        .signup-link {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
            color: var(--gray-dark);
        }
        
        .signup-link a {
            color: var(--black);
            font-weight: 600;
            text-decoration: none;
        }
        
        @media (max-width: 480px) {
            .login-container {
                border-radius: 0;
            }
            
            .brand-header h1 {
                font-size: 24px;
            }
            
            .login-header {
                padding: 20px;
            }
            
            .login-form {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="login-container">
        <div class="brand-header">
            <h1>BioRx-AI</h1>
        </div>
        <div class="login-header">
            <h2>Sign in to get access</h2>
        </div>
        <div class="login-form">
            <form id="loginForm">
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" class="form-control" placeholder="Enter your email" required>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" class="form-control" placeholder="Enter your password" required>
                </div>
                <div class="form-footer">
                    <div class="remember-me">
                        <input type="checkbox" id="remember">
                        <label for="remember">Remember me</label>
                    </div>
                    <div class="forgot-password">
                        <a href="#">Forgot password?</a>
                    </div>
                </div>
                <button type="submit" class="btn btn-primary">Login</button>
                <div class="signup-link">
                    Don't have an account? <a href="#">Sign up</a>
                </div>
            </form>
        </div>
    </div>

    <script>
        document.getElementById('loginForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const email = document.getElementById('email').value;
            const password = document.getElementById('password').value;
            
            // Basic validation
            if (!email || !password) {
                alert('Please fill in all fields');
                return;
            }
            
            // Here you would typically make an API call to authenticate
            console.log('Login attempt with:', { email, password });
            
            // Simulate successful login
            setTimeout(() => {
                alert('Login successful! Redirecting to your dashboard...');
                // window.location.href = '/dashboard';
            }, 1000);
        });
    </script>
</body>
</html>
