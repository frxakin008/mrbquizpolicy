<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Privacy Policy</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      padding: 40px;
      margin: 0;
    }

    h1, h2 {
      color: #00ffea;
      text-shadow: 0 0 5px #00ffea, 0 0 10px #00ffea, 0 0 20px #00ffea;
      text-align: center;
      margin-bottom: 20px;
    }

    .section {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 1s ease-out, transform 1s ease-out;
      margin-bottom: 40px;
    }

    .section.visible {
      opacity: 1;
      transform: translateY(0);
    }

    .section p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.2em;
      line-height: 1.6;
      text-align: justify;
      color: #ccc;
    }

    .section h2 {
      margin-bottom: 10px;
      font-size: 1.5em;
    }

    .link-section {
      text-align: center;
      margin-top: 50px;
    }

    .link-section a {
      color: #00ffea;
      text-decoration: none;
      font-size: 1.2em;
      text-shadow: 0 0 5px #00ffea, 0 0 10px #00ffea;
    }

    .link-section a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1>Privacy Policy</h1>

  <div class="section">
    <h2>Data Collection</h2>
    <p>This quiz bot respects your privacy. We do not collect, store, or share any personal information from users. All interactions happen locally on Telegram, and no user data is tracked outside the platform.</p>
  </div>

  <div class="section">
    <h2>Purpose</h2>
    <p>The bot is strictly intended for educational and informational purposes following the MRB Health Inspector syllabus.</p>
  </div>

  <div class="section">
    <h2>Usage</h2>
    <p>Users are not required to provide any sensitive data to use the free or premium content.</p>
  </div>

  <div class="section">
    <h2>Agreement</h2>
    <p>By using the bot, you agree to these terms and acknowledge that the bot is designed to be simple, secure, and focused on delivering quiz-based learning only.</p>
  </div>

  <div class="section">
    <h2>Contact</h2>
    <p>For any queries or support related to the bot, please reach out through the official Telegram support channel.</p>
  </div>

  <div class="link-section">
    <p>🔗 View as secure link: <a href="https://MRBBot.com/privacy.html" target="_blank">https://yourdomain.com/privacy.html</a></p>
  </div>

  <script>
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    });

    document.querySelectorAll('.section').forEach(section => {
      observer.observe(section);
    });
  </script>
</body>
</html>

