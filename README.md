# educfile:<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Inclusive Education</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Rubik', sans-serif;
      background: linear-gradient(135deg, #1c1c1c, #2e003e);
      color: #fff;
    }

    .header {
      background: #1a1a1a;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #ff70a6;
    }

    .logo {
      animation: fadeInLogo 1s ease-out;
    }

    @keyframes rotateLogo {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    @keyframes fadeInLogo {
      from { opacity: 0; transform: scale(0.8); }
      to { opacity: 1; transform: scale(1); }
    }

    .logo-text {
      font-size: 1.8rem;
      color: #ff70a6;
      font-weight: 600;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
      position: relative;
    }

    nav a::after {
      content: '';
      position: absolute;
      width: 0;
      height: 2px;
      bottom: -4px;
      left: 0;
      background-color: #ff70a6;
      transition: width 0.3s;
    }

    nav a:hover::after {
      width: 100%;
    }

    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background: linear-gradient(to right, #2e003e, #1c1c1c);
      animation: fadeInText 2s ease-in-out;
    }

    @keyframes fadeInText {
      0% { opacity: 0; transform: translateY(40px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    .hero h1 {
      font-size: 3rem;
      color: #ff70a6;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 700px;
      margin: 0 auto;
      color: #ddd;
    }

    .main {
      display: flex;
      gap: 2rem;
      padding: 3rem 2rem;
      max-width: 1200px;
      margin: auto;
    }

    .content {
      flex: 3;
      background: #1f1f1f;
      padding: 2rem;
      border-radius: 10px;
      animation: fadeIn 1.5s ease-in-out;
    }

    .content h2 {
      color: #ff70a6;
      margin-bottom: 1rem;
    }

    .content p {
      margin-bottom: 1.5rem;
      line-height: 1.7;
      color: #ccc;
    }

    .content .cta-button {
      display: inline-block;
      background-color: #ff70a6;
      color: #1a1a1a;
      padding: 0.75rem 1.5rem;
      font-weight: bold;
      border-radius: 8px;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }

    .content .cta-button:hover {
      background-color: #ff4081;
    }

    .sidebar {
      flex: 1;
      background: #252525;
      padding: 2rem;
      border-radius: 10px;
      animation: fadeIn 1.5s ease-in-out 0.3s;
    }

    .sidebar h3 {
      color: #ff70a6;
      margin-bottom: 1rem;
    }

    .sidebar ul {
      list-style: none;
      padding: 0;
    }

    .sidebar ul li {
      margin-bottom: 1rem;
    }

    .sidebar ul li a {
      color: #fff;
      text-decoration: none;
      position: relative;
    }

    .sidebar ul li a::before {
      content: '➤';
      color: #ff70a6;
      margin-right: 8px;
    }

    .sidebar ul li a:hover {
      color: #ff70a6;
    }

    .contact-form {
      background: #1f1f1f;
      padding: 2rem;
      margin: 2rem auto;
      max-width: 800px;
      border-radius: 10px;
      animation: fadeIn 2s ease-in-out;
    }

    .contact-form h2 {
      color: #ff70a6;
      margin-bottom: 1rem;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0 1rem;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
    }

    .contact-form button {
      background: #ff70a6;
      color: #1a1a1a;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
    }

    .contact-form button:hover {
      background: #ff4081;
    }

    footer {
      background: #1a1a1a;
      text-align: center;
      padding: 1.5rem 2rem;
      color: #aaa;
      margin-top: 3rem;
    }

    @media (max-width: 768px) {
      .main {
        flex-direction: column;
      }

      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
    }
  </style>
</head>
<body>
  <header class="header">
    <div class="logo-text">InclusiveEd</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Articles</a>
      <a href="#">Resources</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Inclusive Education Is a Right, Not a Privilege</h1>
    <p>Every child, regardless of ability, background, or identity, deserves a place in the classroom. Discover how inclusive education transforms lives and shapes a fairer world.</p>
  </section>

  <main class="main">
    <section class="content">
      <h2>What is Inclusive Education?</h2>
      <p>Inclusive education is an approach that ensures all students are welcomed and supported in mainstream classrooms. It celebrates diversity and aims to remove barriers to learning for every child.</p>

      <h2>Why Does Inclusion Matter?</h2>
      <p>Inclusion fosters empathy, respect, and collaboration among students. It builds stronger communities and ensures equal opportunities for success in life, regardless of one's starting point.</p>

      <h2>How Can We Support It?</h2>
      <p>We can support inclusive education by advocating for policy changes, supporting teacher training, and ensuring schools have the resources to accommodate every student’s needs.</p>

      <a href="#contact" class="cta-button">Get Involved</a>
    </section>

    <aside class="sidebar">
      <h3>Popular Topics</h3>
      <ul>
        <li><a href="#">Universal Design for Learning</a></li>
        <li><a href="#">Teaching Strategies for Inclusion</a></li>
        <li><a href="#">Disability Awareness in Schools</a></li>
        <li><a href="#">Inclusive Curriculum Planning</a></li>
      </ul>
    </aside>
  </main>

  <section class="contact-form" id="contact">
    <h2>Contact Us</h2>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 InclusiveEd. All rights reserved.</p>
    <p>Developed by <a href="https://marione.netlify.app" target="_blank" style="color: #ff70a6; text-decoration: none; font-weight: 500;">Marione</a></p>
  </footer>
</body>
</html>

