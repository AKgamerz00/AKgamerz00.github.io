<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Akshya Kashyap - Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #fdfbfb;
      color: #333;
      animation: fadeIn 1s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    header {
      background: linear-gradient(to right, #6a11cb, #2575fc);
      color: white;
      padding: 1.5em;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffea00;
    }

    .hero {
      background: linear-gradient(to right, #f7971e, #ffd200);
      color: #fff;
      text-align: center;
      padding: 60px 20px;
      animation: slideUp 1s ease-in;
    }

    @keyframes slideUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .section h2 {
      color: #333;
      margin-bottom: 20px;
      text-align: center;
      font-size: 28px;
      position: relative;
    }

    .card {
      background: linear-gradient(to right, #e0c3fc, #8ec5fc);
      padding: 20px;
      margin: 20px 0;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: pointer;
    }

    .card:hover {
      transform: scale(1.03);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }

    ul {
      padding-left: 20px;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      animation: fadeIn 2s ease-in;
    }

    @media (max-width: 600px) {
      header, .hero, .section, footer {
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>🌟 Akshya Kashyap 🌟</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#courses">Courses</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Class 9 - Jasmine</h2>
    <p>💡 Student at DAV Public School | Eager Learner | Future Leader</p>
  </section>

  <section class="section" id="about">
    <h2>🎓 About Me</h2>
    <div class="card">
      <p><strong>Name:</strong> Akshya Kashyap</p>
      <p><strong>Date of Birth:</strong> 20 August 2011</p>
      <p><strong>Father's Name:</strong> Jaggan Singh</p>
      <p><strong>Mother's Name:</strong> Balesh Devi</p>
      <p><strong>School:</strong> DAV Public School</p>
      <p><strong>Class:</strong> 9 (Jasmine)</p>
    </div>
  </section>

  <section class="section" id="skills">
    <h2>🧠 Skills</h2>
    <div class="card">
      <ul>
        <li>Microsoft Office</li>
        <li>Microsoft Word</li>
        <li>Microsoft PowerPoint</li>
        <li>Microsoft Excel</li>
        <li>Microsoft Project</li>
        <li>Spreadsheet Handling</li>
        <li>Microsoft Outlook</li>
        <li>Group Leadership</li>
        <li>Strategic Thinking</li>
      </ul>
    </div>
  </section>

  <section class="section" id="courses">
    <h2>📚 Courses Completed</h2>
    <div class="card">
      <ul>
        <li>Microsoft Office Suite</li>
        <li>Introduction to ChatGPT</li>
      </ul>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>📞 Contact</h2>
    <div class="card">
      <p>You can reach out through school or contact parents for more details.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Akshya Kashyap | Designed with 💖 | All rights reserved.
  </footer>

</body>
</html>
