<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Validation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    form {
      max-width: 400px;
      margin: 0 auto;
    }
    input {
      display: block;
      margin-bottom: 10px;
      padding: 10px;
      width: 100%;
      box-sizing: border-box;
    }
    .error {
      color: red;
      font-size: 0.9em;
      display: none;
    }
    .valid {
      border-color: green;
    }
    .invalid {
      border-color: red;
    }
    button {
      padding: 10px;
      background-color: green;
      color: white;
      border: none;
      width: 100%;
      cursor: pointer;
    }
    button:disabled {
      background-color: gray;
    }
  </style>
</head>
<body>
  <h2>Registration Form</h2>
  <form id="registrationForm">
    <input type="text" id="username" placeholder="Username" required minlength="4">
    <span class="error" id="usernameError">Username must be at least 4 characters long.</span>

    <input type="email" id="email" placeholder="Email" required>
    <span class="error" id="emailError">Please enter a valid email address.</span>

    <input type="password" id="password" placeholder="Password" required>
    <span class="error" id="passwordError">Password must be at least 8 characters long, include uppercase, lowercase, and special characters.</span>

    <input type="password" id="confirmPassword" placeholder="Confirm Password" required>
    <span class="error" id="confirmPasswordError">Passwords do not match.</span>

    <button type="submit" id="submitBtn" disabled>Register</button>
  </form>

  <script>
    const username = document.getElementById('username');
    const email = document.getElementById('email');
    const password = document.getElementById('password');
    const confirmPassword = document.getElementById('confirmPassword');
    const submitBtn = document.getElementById('submitBtn');

    const usernameError = document.getElementById('usernameError');
    const emailError = document.getElementById('emailError');
    const passwordError = document.getElementById('passwordError');
    const confirmPasswordError = document.getElementById('confirmPasswordError');

    function validateUsername() {
      if (username.value.length < 4) {
        username.classList.add('invalid');
        usernameError.style.display = 'block';
        return false;
      } else {
        username.classList.remove('invalid');
        username.classList.add('valid');
        usernameError.style.display = 'none';
        return true;
      }
    }

    function validateEmail() {
      const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
      if (!emailPattern.test(email.value)) {
        email.classList.add('invalid');
        emailError.style.display = 'block';
        return false;
      } else {
        email.classList.remove('invalid');
        email.classList.add('valid');
        emailError.style.display = 'none';
        return true;
      }
    }

    function validatePassword() {
      const passwordPattern = /^(?=.*[a-z])(?=.*[A-Z])(?=.*\W).{8,}$/;
      if (!passwordPattern.test(password.value)) {
        password.classList.add('invalid');
        passwordError.style.display = 'block';
        return false;
      } else {
        password.classList.remove('invalid');
        password.classList.add('valid');
        passwordError.style.display = 'none';
        return true;
      }
    }

    function validateConfirmPassword() {
      if (password.value !== confirmPassword.value) {
        confirmPassword.classList.add('invalid');
        confirmPasswordError.style.display = 'block';
        return false;
      } else {
        confirmPassword.classList.remove('invalid');
        confirmPassword.classList.add('valid');
        confirmPasswordError.style.display = 'none';
        return true;
      }
    }

    function validateForm() {
      const isFormValid = validateUsername() && validateEmail() && validatePassword() && validateConfirmPassword();
      submitBtn.disabled = !isFormValid;
    }

    username.addEventListener('input', validateForm);
    email.addEventListener('input', validateForm);
    password.addEventListener('input', validateForm);
    confirmPassword.addEventListener('input', validateForm);

    document.getElementById('registrationForm').addEventListener('submit', function (event) {
      event.preventDefault();
      alert('Form submitted successfully!');
    });
  </script>
</body>
</html>
