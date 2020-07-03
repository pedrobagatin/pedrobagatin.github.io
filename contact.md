<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container">
  <form action="action_page.php">
    <div class="row">
      <div class="col-25">
        <label for="fname">Your Name</label>
      </div>
      <div class="col-75">
        <input style="width:50%;" type="text" id="fname" name="firstname" placeholder="Your name..">
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="lname">Your Email</label>
      </div>
      <div class="col-75">
        <input style="width:50%;" type="text" id="lname" name="lastname" placeholder="Your email..">
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="subject">Subject</label>
      </div>
      <div class="col-75">
        <textarea style="width:100%;" id="subject" name="subject" placeholder="Write something..   " style="height:200px"></textarea>
      </div>
    </div>
    <div class="row">
      <input type="submit" value="Submit">
    </div>
  </form>
</div>
  </body>
  </html>
