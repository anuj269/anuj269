<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="google-site-verification" content="b88fyMrpAkyrYa_2hp826cIMuiaVOEMLBTaSbJ-6kh0" />
  <title>Anuj Paudyal - Designer & Developer</title>

  <!-- SEO Meta Tags -->
  <meta name="description" content="Anuj Paudyal - Beginner developer, friendly designer and editor helping grow businesses and ideas.">
  <meta name="keywords" content="Anuj Paudyal, developer, designer, editor, portfolio, HTML, CSS, JS, Python, PHP">
  <meta name="author" content="Anuj Paudyal">

  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #343a40;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    main {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }
    h1, h2 {
      color: #343a40;
    }
    .social-links a {
      margin-right: 10px;
      color: #007bff;
      text-decoration: none;
    }
    form {
      margin-top: 2rem;
      display: flex;
      flex-direction: column;
    }
    label {
      margin: 10px 0 5px;
    }
    input, textarea {
      padding: 10px;
      font-size: 1rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      padding: 10px;
      background-color: #343a40;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }
    button:hover {
      background-color: #495057;
    }
    .quote {
      font-style: italic;
      margin-top: 1rem;
      color: #555;
    }
  </style>
</head>
<body>

  <header>
    <h1>Anuj Paudyal</h1>
    <p>Friendly & nice designer and editor helping you grow your business, content, and ideas.</p>
  </header>

  <main>
    <section>
      <h2>About Me</h2>
      <p>👋 Hi there! I'm <strong>Anuj Paudyal</strong><br>
      I'm a beginner passionate about learning programming, building cool things, and growing every day.</p>
      
      <p>🧠 <strong>Currently learning:</strong> HTML, CSS, JavaScript, Python, and PHP</p>

      <p>🚀 <strong>Goals for 2025:</strong></p>
      <ul>
        <li>Build my first project (even a small one!)</li>
        <li>Collaborate on beginner-friendly open-source projects</li>
        <li>Learn Git, GitHub, and how to contribute</li>
        <li>Become consistent and confident in coding</li>
      </ul>

      <p>💡 I'm here to learn, improve, and grow.</p>
      <p>📚 I believe small steps every day lead to big changes.</p>
      <p>🤝 I'm always open to connect with other learners and developers.</p>

      <p class="quote">“You don’t have to be great to start, but you have to start to be great.” — Zig Ziglar</p>
    </section>

    <section>
      <h2>Connect with Me</h2>
      <p class="social-links">
        <a href="https://www.facebook.com/profile.php?id=61562560904106" target="_blank">Facebook</a> |
        <a href="https://www.instagram.com/anujpaudyal11/" target="_blank">Instagram</a>
      </p>
    </section>

    <section>
      <h2>Contact Me</h2>
      <form action="https://formsubmit.co/your@email.com" method="POST">
        <!-- Replace 'your@email.com' with your actual email -->
        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="name" required>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="topic">Describe Your Work / Topic:</label>
        <textarea id="topic" name="message" rows="4" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

</body>
</html>
