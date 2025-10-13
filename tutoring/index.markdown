<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tutoring Services - Noah Lowery</title>
  <link rel="stylesheet" href="../styles.css" />
  <style>
    /* you can move this into your CSS file */
    .highlight-section {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      text-align: center;
      margin: 2em 0;
    }
    .highlight-box {
      background-color: #f5f5f5;
      border-radius: 12px;
      padding: 1.5em;
      width: 300px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      margin: 1em;
    }
    .highlight-box h2 {
      margin-bottom: 0.5em;
    }
    section {
      margin: 2em auto;
      max-width: 700px;
      text-align: center;
    }
    form input, form textarea {
      width: 100%;
      margin: 0.5em 0;
      padding: 0.7em;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    button {
      padding: 0.8em 1.5em;
      border: none;
      border-radius: 6px;
      background-color: #0077cc;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }
    button:hover {
      background-color: #005fa3;
    }
  </style>
</head>
<body>

  <header>
    <h1>Tutoring Services</h1>
    <nav>
      <a href="../index.html">Home</a> |
      <a href="../research.html">Research Papers</a> |
      <a href="index.html" class="active">Tutoring</a> |
      <a href="../contact.html">Contact</a>
    </nav>
  </header>

  <main>

    <!-- Highlights section -->
    <div class="highlight-section">
      <div class="highlight-box">
        <h2>TUTORING</h2>
        <h3>$35/hr</h3>
        <p>Receive top-quality tutoring services either in-person at a location of your choice or via online video chat.</p>
      </div>
      <div class="highlight-box">
        <h2>MEET THE TUTOR</h2>
        <h3>Free Consultation</h3>
        <p>A brief meeting that provides an opportunity to meet your tutor and discuss your specific tutoring needs.</p>
      </div>
    </div>

    <!-- Survey / get in touch -->
    <section>
      <h2>GET IN TOUCH</h2>
      <p>Questions, comments, or requests? Feel free to reach out below.</p>
      <p>If you wish to receive tutoring services, please complete this brief survey so I can best tailor our sessions:</p>
      <p><a href="https://forms.gle/your-google-form-link" target="_blank" style="color:#0077cc;font-weight:bold;">Preliminary Tutoring Survey →</a></p>
    </section>

    <!-- Contact form -->
    <section>
      <h2>Contact Form</h2>
      <form action="https://formspree.io/f/your_form_id" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="_replyto" placeholder="Your Email" required>
        <input type="text" name="subject" placeholder="Subject">
        <textarea name="message" rows="5" placeholder="Your message..." required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>

  </main>

  <footer>
    <p>© 2025 Noah Lowery</p>
  </footer>

</body>
</html>
