## Contact form
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container">
  <form action="https://formspree.io/xoqkkvbv" method="POST">
    
    <div class="row">
      <div class="col-25">
        <label for="lname">Email</label>
      </div>
      <div class="col-75">
        <input style="width:50%;" type="text" id="lname" name="_replyto" placeholder="Your email..">
      </div>
    </div>
    
    <div class="row">
      <div class="col-25">
        <label for="subject">Subject</label>
      </div>
      <div class="col-75">
        <textarea id="subject" name="message" placeholder="Write something.." style="height:200px; width: 100%"></textarea>
      </div>
    </div>
    <div class="row">
      <button type="submit">Send</button>
    </div>
    <input type="hidden" name="_next" value="https://www.google.com" />
  </form>
</div>
  </body>
  </html>
