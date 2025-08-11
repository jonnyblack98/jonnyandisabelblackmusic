<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Jonny & Isabel Black - Musicians</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #222;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    main {
      max-width: 700px;
      margin: 30px auto;
      background: white;
      padding: 20px;
      box-shadow: 0 0 10px #ccc;
      border-radius: 8px;
    }
    h1, h2 {
      margin-top: 0;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input[type="text"],
    input[type="email"],
    select,
    textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      box-sizing: border-box;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 16px;
    }
    input[type="submit"] {
      margin-top: 20px;
      background: #222;
      color: white;
      border: none;
      padding: 15px;
      font-size: 18px;
      cursor: pointer;
      border-radius: 4px;
      width: 100%;
      transition: background 0.3s ease;
    }
    input[type="submit"]:hover {
      background: #555;
    }
    footer {
      text-align: center;
      padding: 15px 0;
      background: #222;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Jonny & Isabel Black</h1>
    <p>Musicians available for weddings, funerals, and special events</p>
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
    <p>Contact us at <a href="mailto:jonnyblack98@hotmail.com" style="color: #fff;">jonnyblack98@hotmail.com</a></p>
  </footer>
</body>
</html>
