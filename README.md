ASSIGNMENTNMENTTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DREAM CHASERS TUTORS</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(to right, #74ebd5, #acb6e5);
      padding: 20px;
      margin: 0;
    }
    .container {
      max-width: 700px;
      margin: auto;
      background: #ffffff;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
    h1 {
      text-align: center;
      font-size: 28px;
      color: #333;
    }
    p.description {
      text-align: center;
      color: #666;
      margin-bottom: 25px;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
    button {
      background: #4CAF50;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 20px;
      width: 100%;
      font-size: 16px;
    }
    button:hover {
      background: #45a049;
    }
    @media screen and (max-width: 600px) {
      .container {
        padding: 20px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>DREAM CHASERS ASSIGNMENT</h1>
    <p class="description">Submit your academic assignments with ease. Select your course, upload your file, and we'll take care of the rest.</p>
    <form action="https://formsubmit.co/jeremylameck25@gmail.com" method="POST" enctype="multipart/form-data">

      <label for="university">Select or Enter Your University:</label>
      <input list="universities" name="university" id="university" placeholder="Type your university name..." required>
      <datalist id="universities">
        <option value="Harvard University">
        <option value="University of Oxford">
        <option value="University of Nairobi">
        <option value="Stanford University">
        <option value="Massachusetts Institute of Technology (MIT)">
        <option value="University of Toronto">
        <option value="University of Tokyo">
        <option value="University of Cape Town">
        <option value="University of Delhi">
        <option value="Kenyatta University">
        <option value="University of Lagos">
        <option value="University of Ghana">
        <option value="University of Sydney">
        <option value="University of British Columbia">
        <!-- Add more globally if needed -->
      </datalist>

      <label for="course">Select or Enter Your Course:</label>
      <input list="courses" name="course" id="course" placeholder="e.g., Computer Science, Law, Business..." required>
      <datalist id="courses">
        <option value="Computer Science">
        <option value="Law">
        <option value="Medicine">
        <option value="Engineering">
        <option value="Marketing">
        <option value="Psychology">
        <option value="Finance">
        <option value="Education">
        <option value="Architecture">
        <option value="Economics">
      </datalist>

      <label for="name">Your Full Name:</label>
      <input type="text" name="name" id="name" required>

      <label for="email">Your Email:</label>
      <input type="email" name="email" id="email" required>

      <label for="message">Assignment Description:</label>
      <textarea name="message" id="message" rows="6" placeholder="Provide topic, deadline, formatting style (APA, MLA), etc." required></textarea>

      <label for="file">Upload Assignment File (PDF, DOC, DOCX, TXT):</label>
      <input type="file" name="file" id="file" accept=".pdf,.doc,.docx,.txt">

      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_template" value="box">

      <button type="submit">Submit Assignment</button>
    </form>
  </div>
</body>
</html>

