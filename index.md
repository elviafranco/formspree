<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Form</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
</head>
<body>
    <div class="wrapper">
    <form action="https://formspree.io/f/mnqldplb" method="POST">
        <label for="name">Name:</label>
        <input id="name" type="text" name="name" placeholder="Enter your full name" required/>
        <label for="email">Enter your email:</label>
        <input type="email" id="email" size="30" placeholder="Enter your email" required/>
        <label for="form-message">Message:</label>
        <textarea
          id="form-message"
          type="text"
          name="message"
          placeholder="How can I help you?"
          required
        ></textarea>
        <button type="submit">Send</button>
      </form>
    </div>
</body>
</html>