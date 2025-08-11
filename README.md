<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Jonny & Isabel Black - Musicians</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Poppins&display=swap" rel="stylesheet" />
  <style>
    /* Reset & basics */
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #f7f9fc;
      color: #222;
      line-height: 1.6;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    a {
      color: #0077cc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    header {
      background: #1a1a1a;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }
    header h1 {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 2.8rem;
      letter-spacing: 1.5px;
    }
    header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
      font-weight: 400;
      opacity: 0.8;
    }
    main {
      flex-grow: 1;
      max-width: 700px;
      margin: 2rem auto 3rem;
      background: white;
      padding: 2.5rem 3rem;
      border-radius: 10px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }
    section + section {
      margin-top: 3rem;
    }
    h2 {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 2rem;
      margin-bottom: 1rem;
      border-bottom: 3px solid #0077cc;
      display: inline-block;
      padding-bottom: 0.3rem;
      color: #0077cc;
    }
    p {
      font-size: 1.1rem;
      color: #444;
    }
    form {
      margin-top: 1rem;
    }
    label {
      display: block;
      margin-bottom: 0.3rem;
      font-weight: 600;
      color: #333;
      margin-top: 1.2rem;
    }
    input[type="text"],
    input[type="email"],
    select,
    textarea {
      width: 100%;
      padding: 0.8rem 1rem;
      font-size: 1rem;
      border: 2px solid #ddd;
      border-radius: 6px;
      transition: border-color 0.3s ease;
      font-family: inherit;
      resize: vertical;
    }
    input[type="text"]:focus,
    input[type="email"]:focus,
    select:focus,
    textarea:focus {
      outline: none;
      border-color: #0077cc;
      background: #f0f8ff;
    }
    input[type="submit"] {
      margin-top: 2rem;
      background: #0077cc;
      color: white;
      border: none;
      padding: 1rem;
      font-size: 1.2rem;
      font-weight: 700;
      border-radius: 8px;
      cursor: pointer;
      width: 100%;
      transition: background-color 0.3s ease;
    }
    input[type="submit"]:hover {
      background: #005fa3;
    }
    footer {
      background: #1a1a1a;
      color: white;
      text-align: center;
      padding: 1.5rem 1rem;
      font-size: 0.9rem;
      margin-top: auto;
    }
    footer a {
      color: #7ec8ff;
    }
    @media (max-width: 600px) {
      main {
        margin: 1rem;
        padding: 1.5rem 1.5rem;
      }
      header h1 {
        font-size: 2rem;
      }
      h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Jonny &amp; Isabel Black</h1>
    <p>Musicians available for weddings, funerals &amp; special events</p>
  </header>

  <main>
    <section id="about">
      <h2>About Us</h2>
      <p>We are Jonny and Isabel Black, passionate musicians who love performing at weddings, funerals, parties, and other special occasions. Our music sets the perfect tone for your memorable events.</p>
    </section>

    <section id="contact">
      <h2>Enquire Now</h2>
      <form id="enquiryForm" action="https://formspree.io/f/myzplldd" method="POST">
        <label for="name">Your Name*</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Your Email*</label>
        <input type="email" id="email" name="_replyto" required />

        <label for="eventType">Event Type</label>
        <select id="eventType" name="eventType">
          <option>Wedding</option>
          <option>Funeral</option>
          <option>Party</option>
          <option>Other</option>
        </select>

        <label for="message">Message*</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <input type="hidden" name="_subject" value="New enquiry from your website" />
        <input type="submit" value="Send Enquiry" />
      </form>
    </section>
  </main>

  <footer>
    <p>Contact us at <a href="mailto:jonnyblack98@hotmail.com">jonnyblack98@hotmail.com</a></p>
  </footer>
</body>
</html>

  <footer>
    <p>Contact us at <a href="mailto:jonnyblack98@hotmail.com" style="color: #fff;">jonnyblack98@hotmail.com</a></p>
  </footer>
</body>
</html>
