<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Khadija's Practice Website</title>
  <meta name="description" content="A simple practice website with headings, lists, table, form, and media elements.">
  <meta name="keywords" content="HTML, Practice, Khadija, Table, Form, SEO">
  <style>
    body { font-family: Arial, sans-serif; background: #f5f7fa; margin: 0; padding: 20px; }
    h1, h2 { text-align: center; color: #2c3e50; }
    section { margin: 20px 0; padding: 15px; background: white; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    table { width: 100%; border-collapse: collapse; margin-top: 10px; }
    th, td { border: 1px solid #444; padding: 8px; text-align: center; }
    th { background: #2c3e50; color: white; }
    tr:nth-child(even) { background: #ecf0f1; }
    form { display: flex; flex-direction: column; }
    input, select, textarea, button { margin: 8px 0; padding: 10px; border-radius: 5px; border: 1px solid #aaa; }
    button { background: #2c3e50; color: white; cursor: pointer; }
    button:hover { background: #34495e; }
  </style>
</head>
<body>

  <h1>Welcome to My Practice Website</h1>
  <p style="text-align:center;">This page is created by <b>Khadija</b> for practice of HTML, CSS and basic web development.</p>

  <!-- Headings -->
  <section>
    <h2>Headings Example</h2>
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
  </section>

  <!-- Lists -->
  <section>
    <h2>My Hobbies (Lists)</h2>
    <ul>
      <li>Reading</li>
      <li>Cooking</li>
      <li>Coding</li>
    </ul>
    <ol>
      <li>Wake up early</li>
      <li>Pray</li>
      <li>Study</li>
    </ol>
    <dl>
      <dt>HTML</dt>
      <dd>- Structure of a webpage</dd>
      <dt>CSS</dt>
      <dd>- Styling webpages</dd>
    </dl>
  </section>

  <!-- Table -->
  <section>
    <h2>Subjects Table</h2>
    <table>
      <tr>
        <th>Subject</th>
        <th>Teacher</th>
        <th>Day</th>
      </tr>
      <tr>
        <td>Math</td>
        <td>Miss Tahmina</td>
        <td>Monday</td>
      </tr>
      <tr>
        <td>Chemistry</td>
        <td>Miss Urooj</td>
        <td>Tuesday</td>
      </tr>
      <tr>
        <td>English</td>
        <td>Miss Farahna</td>
        <td>Wednesday</td>
      </tr>
    </table>
  </section>

  <!-- Form -->
  <section>
    <h2>Contact Form</h2>
    <form>
      <input type="text" placeholder="Enter your name" required>
      <input type="email" placeholder="Enter your email" required>
      <input type="password" placeholder="Enter your password">
      <select>
        <option>Select your city</option>
        <option>Hyderabad</option>
        <option>Karachi</option>
        <option>Islamabad</option>
      </select>
      <textarea rows="4" placeholder="Write your message..."></textarea>
      <button type="submit">Submit</button>
      <button type="reset">Reset</button>
    </form>
  </section>

  <!-- Media -->
  <section>
    <h2>Media Example</h2>
    <p>Audio:</p>
    <audio controls>
      <source src="sample.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
    <p>Video:</p>
    <video controls width="300">
      <source src="sample.mp4" type="video/mp4">
      Your browser does not support the video element.
    </video>
  </section>

  <!-- Iframe -->
  <section>
    <h2>Iframe Example</h2>
    <iframe src="https://www.wikipedia.org" width="100%" height="300"></iframe>
  </section>

</body>
</html>
