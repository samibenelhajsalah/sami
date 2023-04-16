---
permalink: /markdown/
# title: "Markdown"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
<!-- <div class="mb-3"> 
      <form name="contact" method="POST" action="https://formspree.io/f/xwkjwjzl">
        <div class="form-group form-inline">
          <label class="sr-only" for="inputName">Name</label>
          <input type="text" name="name" class="form-control w-100" id="inputName" placeholder="Name" required>
        </div>
        <div class="form-group form-inline">
          <label class="sr-only" for="inputEmail">Email</label>
          <input type="email" name="email" class="form-control w-100" id="inputEmail" placeholder="Email" required>
        </div>
        <div class="form-group">
          <label class="sr-only" for="inputMessage">Message</label>
          <textarea name="message" class="form-control" id="inputMessage" rows="5" placeholder="Message" required></textarea>
        </div>
        <button type="submit" class="btn btn-outline-primary px-3 py-2">Send</button>
      </form>
</div>
-->
<html>
  <head>
    <title>Formulaire de Contact</title>
    <style>
      /* Styles pour le formulaire */
      form {
        max-width: 600px;
        margin: auto;
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
        background-color: #f2f2f2;
      }
      label {
        display: block;
        margin-bottom: 10px;
        font-weight: bold;
      }
      input[type="text"],
      input[type="email"],
      textarea {
        width: 100%;
        padding: 10px;
        margin-bottom: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
        resize: none;
      }
      input[type="submit"] {
        background-color: #4CAF50;
        color: white;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }
      input[type="submit"]:hover {
        background-color: #45a049;
      }
      /* Styles pour la page */
      body {
        font-family: Arial, sans-serif;
        font-size: 16px;
        line-height: 1.5;
        margin: 0;
        padding: 0;
      }
      h1 {
        text-align: center;
        margin-top: 50px;
      }
    </style>
  </head>
  <body>
    <h1>Contact Me</h1>
    <form name="contact" method="POST" action="https://formspree.io/f/xwkjwjzl">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>
      <input type="submit" value="Send">
    </form>
  </body>
</html>
