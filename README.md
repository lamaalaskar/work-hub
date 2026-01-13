# work-hub
Senior Project
<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="CreAccCom.aspx.cs" Inherits="workHub.CreAccCom" %>

<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WorkHub Registration</title>
  <link rel="stylesheet" href="CreAccCom.css">
  <script src="script.js" type="module"></script>
  <script type="importmap">
{
  "imports": {
    "config": "./config.js"
  }
}
</script>
</head>

<body>
  <div class="container">
    <div class="form-container">
      <div class="left-section">
        <h1>Welcome to<br>WorkHub Platform</h1>
        <p>Join Work Hub Today. Recruit smarter with WorkHub. Create your account to post job openings, filter candidates, and
          organize applications—all in one place. Discover an efficient way to build your team effortlessly.</p>
      </div>
      <div class="right-section">
        <h2>Create an account</h2>
        <form id="registrationForm">
          <div class="form-group">
            <label for="companyName">Company Name</label>
            <input type="text" id="companyName" name="companyName" placeholder="Full legal name of the company">
          </div>
          <div class="form-group">
            <label for="emailAddress">Email Address</label>
            <input type="email" id="emailAddress" name="emailAddress"
              placeholder="A valid company email for account verification and communication">
          </div>
          <div class="form-group">
            <label for="password">Password</label>
            <input type="password" id="password" name="password"
              placeholder="Strong password (must include uppercase letters, numbers, and symbols)">
          </div>
          <div class="form-group">
            <label for="phoneNumber">Phone Number</label>
            <div class="phone-input">
              <select id="countryCode">
                <option value="+966">+966</option>
                <option value="+1">+1</option>
                <!-- Add more country codes as needed -->
              </select>
              <input type="tel" id="phoneNumber" name="phoneNumber">
            </div>
          </div>
          <div class="form-group">
            <label for="website">Company Website (Optional)</label>
            <input type="url" id="website" name="website">
          </div>
          <div class="form-group">
            <label for="industry">Industry</label>
            <input type="text" id="industry" name="industry"
              placeholder="The industry the company operates in (e.g., Technology, Retail, Healthcare)">
          </div>
          <div class="form-group">
            <label for="location">Location</label>
            <input type="text" id="location" name="location">
          </div>
          <div class="form-group">
            <label for="logo">Logo (Optional)</label>
            <input type="file" id="logo" name="logo">
          </div>

         <a href="HomePage.aspx" class="button"> Register </a> 
                    

          <!-- <button type="submit" onclick="window.location.href='HomePage.aspx'">Register</button> -->

          <p class="login-link">Already have an account? <a href="LoginCompany.aspx">Log in</a></p>
        </form>
      </div>
    </div>
  </div>
</body>

</html>
