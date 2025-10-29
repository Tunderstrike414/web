<!DOCTYPE html>
<html lang="en-US">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nejat's Academic Webpage</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f9f9f9;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    td {
      vertical-align: top;
      padding: 10px;
      border: 1px solid #ccc;
    }

    .header {
      background-color: #ff69b4;
      color: white;
      text-align: center;
      font-size: 28px;
      padding: 20px;
    }

    .sidebar {
      width: 200px;
      background-color: #d3d3d3;
    }

    .sidebar a {
      display: block;
      margin: 8px 0;
      padding: 6px;
      text-decoration: none;
      color: black;
      background-color: #f0f0f0;
      border-radius: 4px;
    }

    .sidebar a:hover {
      background-color: #e0e0e0;
    }

    .profile {
      display: flex;
      align-items: center;
      padding: 10px;
    }

    .profile img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      margin-right: 15px;
    }

    .main-content {
      padding: 20px;
      text-align: center;
    }

    .main-content img {
      width: 150px;
      height: 150px;
      border-radius: 20%;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <table>
    <tr>
      <td colspan="2" class="header">Nejat's Academic Webpage</td>
    </tr>
    <tr>
      <td colspan="2">
        <div class="profile">
          <img src="nejat.jpg" alt="Nejat Aragaw Mohammed">
          <div>
            <strong>Nejat Aragaw Mohammed</strong><br>
            ID: NSR/0625/16
          </div>
        </div>
      </td>
    </tr>
    <tr>
      <td class="sidebar">
        <strong>Lab Practices & Assignments</strong>
        <a href="Assn1.html">Assignment</a>
        <a href="lab1.html">Lab 1</a>
        <a href="lab2.html">Lab 2</a>
        <a href="lab3.html">Lab 3</a>
        <a href="lab4.html">Lab 4</a>
      </td>
      <td class="main-content">
        <img src="nejat.jpg" alt="Nejat Aragaw Mohammed">
        <h2>Hello</h2>
        <p>Welcome to my academic webpage. Here you'll find my lab work, assignments, and personal profile.</p>
      </td>
    </tr>
  </table>

</body>
</html>
