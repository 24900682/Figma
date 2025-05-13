# Ex09 Event Registration Web Application
# Date:10/05/2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
Page 1

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sports Day Registration - Saveetha Engineering College</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 15px;
    }

    .container {
      width: 100%;
      max-width: 412px;
      text-align: center;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    .college-logo {
      width: 100%;
      max-width: 380px;
      height: auto;
      margin: 20px auto;
      display: block;
    }

    .image-wrapper {
      position: relative;
      width: 100%;
    }

    .background-image {
      width: 100%;
      display: block;
      height: auto;
    }

    .buttons {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      display: flex;
      flex-direction: column;
      gap: 25px;
      width: 70%;
    }

    .button {
      text-decoration: none;
      background-color: #779BE7;
      color: #0A0952;
      padding: 15px 20px;
      font-size: 18px;
      font-weight: bold;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: all 0.3s ease;
      display: block;
    }

    .button:hover {
      background-color: #5A7ED0;
      transform: translateY(-2px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.2);
    }

    .register-button {
      background-color: #F2BEF9;
    }

    .register-button:hover {
      background-color: #E0A1E8;
    }

    @media (max-width: 480px) {
      .buttons {
        width: 85%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- College Logo -->
    <img class="college-logo" src="images/college_logo.png" alt="Saveetha Engineering College Logo" />
    
    <div class="image-wrapper">
      <!-- Background Sports Image -->
      <img class="background-image" src="images/Sports Illustration Vector_ Sports Day Banner Background Vector Stock Vector.jpg" alt="Sports Day Background" />
      
      <!-- Action Buttons -->
      <div class="buttons">
        <a href="Page 3.html" class="button register-button">REGISTER NOW</a>
        <a href="login.html" class="button">LOGIN</a>
      </div>
    </div>
  </div>
</body>
</html>

Page 2

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Event List - College Project</title>
    <style>
      /* Basic Reset */
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      /* Body Styles */
      body {
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        padding: 20px;
        background-color: #f4f4f4;
        
        background-image: url("images/Athletic Meeting Background Material Map Wallpaper Image For Free Download - Pngtree.jpg");
        background-size: cover;
        background-position: center;
        background-attachment: fixed;
      }

      /* Main Container */
      .container {
        background-color: rgba(255, 255, 255, 0.9); 
        width: 90%;
        max-width: 380px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        overflow: hidden;
        text-align: center;
        padding: 20px;
      }

      /* College Logo */
      .college-logo {
        width: 100%;
        max-width: 350px;
        height: auto;
        margin-bottom: 20px;
        border-radius: 8px;
      }

      /* Event Title */
      .title {
        font-size: 28px;
        font-weight: bold;
        color: #333;
        margin-bottom: 20px;
      }

      /* Event List */
      .event-list {
        list-style-type: none;
        padding: 0;
        font-size: 16px;
        color: #555;
        margin-bottom: 20px;
        text-align: left;
      }

      .event-list li {
        margin: 8px 0;
        padding-left: 20px;
        position: relative;
      }
      
      .event-list li:before {
        content: "•";
        position: absolute;
        left: 0;
        color: #0066cc;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <!-- College Logo -->
      <img class="college-logo" src="images/college_logo.png" alt="Saveetha Engineering College Logo" />

      <!-- Event Title -->
      <div class="title">Event List</div>

      <!-- Event List -->
      <ul class="event-list">
        <li>Volleyball</li>
        <li>Football</li>
        <li>Basketball</li>
        <li>Cricket</li>
        <li>Badminton</li>
        <li>Table Tennis</li>
        <li>Carrom</li>
        <li>Chess</li>
        <li>High Jump</li>
        <li>Long Jump</li>
        <li>Javelin Throw</li>
        <li>Kabaddi</li>
        <li>Kho-Kho</li>
        <li>Running Race</li>
        <li>Relay Race</li>
      </ul>
    </div>
  </body>
</html>

Page 3

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sports Event Registration - Saveetha Engineering College</title>
  <style>
    /* Simple Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background-color: #f5f5f5;
      display: flex;
      justify-content: center;
      padding: 20px;
    }

    .container {
      width: 100%;
      max-width: 400px;
      background-color: #ffffff;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      border-radius: 8px;
    }

    .college-logo {
      width: 100%;
      height: auto;
      margin-top: 20px;
      display: block;
    }

    .registration-form {
      padding: 20px;
      background-image: url('images/Simple Various Sports Themes Background Wallpaper Image For Free Download - Pngtree.jpg');
      background-size: cover;
      background-position: center;
    }

    .form-title {
      text-align: center;
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 25px;
      background-color: rgba(255, 255, 255, 0.7);
      padding: 8px;
      border-radius: 5px;
    }

    .input-group {
      margin-bottom: 15px;
    }

    .input-label {
      display: block;
      background-color: #d9d9d9;
      padding: 5px 10px;
      font-size: 16px;
      font-weight: bold;
      margin-bottom: 5px;
      width: fit-content;
      border-radius: 3px;
    }

    .input-field {
      width: 100%;
      padding: 10px;
      border: 1px solid #d9d9d9;
      border-radius: 5px;
      font-size: 16px;
      background-color: rgba(255, 255, 255, 0.8);
    }

    .submit-button {
      background-color: #d9d9d9;
      border: none;
      padding: 8px 25px;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      display: block;
      margin: 25px auto 10px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    .submit-button:hover {
      background-color: #b0b0b0;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- College Logo -->
    <img class="college-logo" src="images/college_logo.png" alt="Saveetha Engineering College Logo">
    
    <!-- Registration Form -->
    <div class="registration-form">
      <div class="form-title">REGISTER NOW</div>
      
      <form>
        <div class="input-group">
          <label class="input-label">Name:</label>
          <input type="text" class="input-field" required>
        </div>
        
        <div class="input-group">
          <label class="input-label">Department:</label>
          <input type="text" class="input-field" required>
        </div>
        
        <div class="input-group">
          <label class="input-label">Event 1:</label>
          <select class="input-field" required>
            <option value="">Select an event</option>
            <option value="volleyball">Volleyball</option>
            <option value="football">Football</option>
            <option value="basketball">Basketball</option>
            <option value="cricket">Cricket</option>
            <option value="badminton">Badminton</option>
            <option value="tabletennis">Table Tennis</option>
            <option value="carrom">Carrom</option>
            <option value="chess">Chess</option>
            <option value="highjump">High Jump</option>
            <option value="longjump">Long Jump</option>
            <option value="javelin">Javelin Throw</option>
            <option value="kabaddi">Kabaddi</option>
            <option value="khokho">Kho-Kho</option>
            <option value="running">Running Race</option>
            <option value="relay">Relay Race</option>
          </select>
        </div>
        
        <div class="input-group">
          <label class="input-label">Event 2:</label>
          <select class="input-field">
            <option value="">Select an event (optional)</option>
            <option value="volleyball">Volleyball</option>
            <option value="football">Football</option>
            <option value="basketball">Basketball</option>
            <option value="cricket">Cricket</option>
            <option value="badminton">Badminton</option>
            <option value="tabletennis">Table Tennis</option>
            <option value="carrom">Carrom</option>
            <option value="chess">Chess</option>
            <option value="highjump">High Jump</option>
            <option value="longjump">Long Jump</option>
            <option value="javelin">Javelin Throw</option>
            <option value="kabaddi">Kabaddi</option>
            <option value="khokho">Kho-Kho</option>
            <option value="running">Running Race</option>
            <option value="relay">Relay Race</option>
          </select>
        </div>
        
        <div class="input-group">
          <label class="input-label">Event 3:</label>
          <select class="input-field">
            <option value="">Select an event (optional)</option>
            <option value="volleyball">Volleyball</option>
            <option value="football">Football</option>
            <option value="basketball">Basketball</option>
            <option value="cricket">Cricket</option>
            <option value="badminton">Badminton</option>
            <option value="tabletennis">Table Tennis</option>
            <option value="carrom">Carrom</option>
            <option value="chess">Chess</option>
            <option value="highjump">High Jump</option>
            <option value="longjump">Long Jump</option>
            <option value="javelin">Javelin Throw</option>
            <option value="kabaddi">Kabaddi</option>
            <option value="khokho">Kho-Kho</option>
            <option value="running">Running Race</option>
            <option value="relay">Relay Race</option>
          </select>
        </div>
        
        <div class="input-group">
          <label class="input-label">Contact No:</label>
          <input type="tel" class="input-field" required>
        </div>
        
        <div class="input-group">
          <label class="input-label">Email:</label>
          <input type="email" class="input-field" required>
        </div>
        
        <button type="submit" class="submit-button">Submit</button>
      </form>
    </div>
  </div>
</body>
</html>

Page 4

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sports Day Invitation - Saveetha Engineering College</title>
  <style>
    /* Simple Reset and Base Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    
    body {
      background-color: #ffffff;
      display: flex;
      justify-content: center;
      min-height: 100vh;
      padding: 20px;
    }
    
    .container {
      width: 100%;
      max-width: 412px;
      position: relative;
    }
    
    .college-logo {
      width: 100%;
      max-width: 388px;
      height: auto;
      margin: 30px 0;
      display: block;
    }
    
    .invitation-card {
      width: 100%;
      height: 568px;
      background-image: url('images/sports-background.jpg');
      background-size: cover;
      background-position: center;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    
    .message-box {
      background-color: #d9d9d9;
      width: 85%;
      padding: 20px;
      margin-bottom: 40px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    
    .invitation-text {
      font-size: 20px;
      line-height: 1.5;
      text-align: center;
      margin-bottom: 20px;
    }
    
    .thank-you-button {
      background-color: #d9d9d9;
      border: none;
      padding: 10px 20px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
      transition: background-color 0.3s;
    }
    
    .thank-you-button:hover {
      background-color: #c0c0c0;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- College Logo -->
    <img class="college-logo" src="images/college_logo.png" alt="Saveetha Engineering College Logo">
    
    <!-- Invitation Card -->
    <div class="invitation-card">
      <div class="message-box">
        <p class="invitation-text">
          You are cordially invited to join us for the grand celebration of<br>
          <strong>SPORTS DAY 2025</strong> at Saveetha Engineering College!<br><br>
          We look forward to enthusiastic participation from all, with many exciting events, 
          opportunities to win medals, and a vibrant atmosphere to celebrate sportsmanship and team spirit.
        </p>
      </div>
      
      <button class="thank-you-button">Thank You</button>
    </div>
  </div>
</body>
</html>
```
# OUTPUT:
Figma
![alt text](<figma_page 1.png>)

![alt text](<figma_page 2.png>)

![alt text](<figma_page 3.png>)

![alt text](<figma_page 4.png>)

Webpage

![alt text](<browser_page 1.png>)

![alt text](<browser_page 2.png>)

![alt text](<browser_page 3.png>)

![alt text](<browser_page 4.png>)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
