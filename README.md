<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Akshya Kashyap – Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Akshya Kashyap</h1>
    <p>Class 9 Jasmine, DAV Public School, Ghaziabad</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>A Class 9 student from Ghaziabad, proficient in Microsoft Office tools and leadership. Completed courses in Microsoft Office and ChatGPT.</p>
    <ul>
      <li><strong>DOB:</strong> 20 August 2011</li>
      <li><strong>Location:</strong> Rahul Vihar 2, Ghaziabad</li>
      <li><strong>Languages:</strong> English & Hindi</li>
    </ul>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Microsoft Word • Excel • PowerPoint • Project • Outlook</li>
      <li>Spreadsheet management</li>
      <li>Group leadership & strategic planning</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact & Social Links</h2>
    <p>📞 9319774088</p>
    <p>✉️ akshyakashyap41@gmail.com</p>
    <ul class="social">
      <li><a href="https://www.linkedin.com/in/akshya-kashyap-s-o-jaggan-kashyap-60572a297" target="_blank">LinkedIn</a></li>
      <li><a href="https://www.instagram.com/_pirate_hunter__" target="_blank">Instagram</a></li>
      <li><a href="https://www.facebook.com/share/1CxiaCD7FR/" target="_blank">Facebook</a></li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Akshya Kashyap</p>
  </footer>
</body>
</html>

body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  color: #222;
  background: #fafafa;
}

header {
  background: linear-gradient(135deg, #ff6ec4, #7873f5);
  color: white;
  text-align: center;
  padding: 3rem 1rem;
}

header h1 {
  margin: 0; font-size: 2.8rem;
}

header nav {
  margin-top: 1rem;
}

header nav a {
  color: white;
  margin: 0 1rem;
  padding: 0.7rem 1.2rem;
  text-decoration: none;
  font-weight: bold;
  transition: transform .3s, background .3s;
}

header nav a:hover {
  background: rgba(255,255,255,0.3);
  border-radius: 8px;
  transform: translateY(-2px);
}

section {
  max-width: 800px;
  margin: auto;
  padding: 2.5rem 1rem;
}

section h2 {
  font-size: 1.9rem;
  position: relative;
  display: inline-block;
  margin-bottom: 1rem;
  padding-bottom: 0.3rem;
}

section h2::after {
  content: '';
  position: absolute;
  width: 50%;
  height: 4px;
  background: #7873f5;
  bottom: 0;
  left: 0;
}

#about { background: #fff7f8; border-radius: 8px; }

#skills {
  background: #f3faff;
  border-radius: 8px;
}

#skills ul li {
  margin: 0.6rem 0;
  padding: 0.8rem;
  background: #e3eaff;
  border-radius: 6px;
  transition: transform .3s, background .3s;
}

#skills ul li:hover {
  background: #d0d4f7;
  transform: translateX(4px);
}

#contact {
  background: linear-gradient(120deg, #c1fba4, #fecdcd);
  border-radius: 8px;
  text-align: center;
}

.social { list-style: none; padding: 0; }
.social li { display: inline; margin: 0 1rem; }

.social a {
  text-decoration: none;
  color: #222;
  font-size: 1.1rem;
  transition: color .3s;
}

.social a:hover {
  color: #ff6ec4;
}

footer {
  text-align: center;
  padding: 1.2rem;
  background: #f0f0f0;
  font-size: 0.9rem;
}

/* Responsive */
@media(max-width: 600px) {
  header h1 { font-size: 2.2rem; }
  header nav a { margin: 0 .5rem; padding: .5rem 1rem; }
}
