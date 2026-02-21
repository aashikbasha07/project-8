# project-8
Student Marks Web Page
Overview

This project is a simple web page that displays student marks in an organized HTML table with a dark/black theme. It is designed to provide a visually appealing interface for viewing student grades with clear styling, readable fonts, and color-coded elements.

Features

HTML Table: Displays student information including Name, Roll Number, Subject, and Marks.

Responsive Styling: Table and page are styled for better readability and aesthetics.

Hover Effects: Table rows highlight on hover to improve UX.

Technologies Used

HTML5: Structure of the page and table.

CSS3: Styling, colors, hover effects, and dark theme.

Preview

The table has alternating row colors, a black background, and white/light text for a modern dark theme. Example layout:

Name	Roll Number	Subject	Marks
Alice	101	Math	95
Bob	102	Science	88
Charlie	103	English	92
How to Use

Clone or download this repository.

Open index.html in a web browser.

Modify the HTML table to add or update student marks as needed.

Customize colors and styles in the style.css file if desired.

Example HTML Structure
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Marks</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Student Marks</h1>
    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Roll Number</th>
          <th>Subject</th>
          <th>Marks</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Alice</td>
          <td>101</td>
          <td>Math</td>
          <td>95</td>
        </tr>
        <tr>
          <td>Bob</td>
          <td>102</td>
          <td>Science</td>
          <td>88</td>
        </tr>
      </tbody>
    </table>
  </div>
</body>
</html>
Example CSS for Black Theme
body {
  background-color: #121212;
  color: #ffffff;
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  width: 80%;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
}

th, td {
  border: 1px solid #444;
  padding: 12px;
  text-align: left;
}

th {
  background-color: #1f1f1f;
}

tr:nth-child(even) {
  background-color: #1a1a1a;
}

tr:hover {
  background-color: #333;
}
Customization



Add more student rows as needed.

Enhance with sorting or searching functionality using JavaScript.
