<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css">
  <title>Isaiah's Portfolio</title>
</head>
<body>
  <div class="header">
    <h1>Isaiah  Markel</h1>
    <p>A portfolio of creativity & ambition</p>
  </div>
  <div class="navbar">
    <a href="contact.html">Contact Me</a></li>
    <a href="aboutme.html">About Me</a></li>
  </div>
  <div>
    <img class="mySlides" src="file:///Users/isaiahlesley/Downloads/3rd%20podcast%20banner%20-%20draft.JPG" style="width:100%">
    <img class="mySlides" src="file:///Users/isaiahlesley/Downloads/LPCC%20Graphic%20for%20Social%20Media.JPG" style="width:100%">
    <img class="mySlides" src="file:///Users/isaiahlesley/Downloads/Potcast%20Channel%20banner.JPG" style="width:100%"> <i>graphics created by Isaiah.</i>
  </div>
  <div class="team" style="max-width:600px">
    <h2 class="brandname">Isaiah's Team</h2>
    <p class="logline"><i>we are merging the boundaries of new media and expanding the boundaries of creativity</i></p>
    <p class="whoarewe"> We are a creative collective of goofy college students that stay in Chicago and Create on a weekly basis. Meet the Team!</p>
  </div>
  <h2 style="text-align:center">My Team</h2>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="https://portfolium1.cloudimg.io/s/crop/192x192/https://cdn.portfolium.com/ugcs3%2Fv3%2Favatar%2FlnaDQ6VcQQWJRt5MRq47_IMG_5814.JPG" alt="Picture of Isaiah" style="width:100%">
      <div class="container">
        <h2>Isaiah Lesley</h2>
        <p class="title">CEO & Founder</p>
        <p>Leader of an Extrordinary collective of creators</p>
        <p>isaiah.lesley@gmail.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="https://scontent-ort2-2.xx.fbcdn.net/v/t1.0-9/67509020_2600833579937454_8331333911028170752_n.jpg?_nc_cat=106&ccb=2&_nc_sid=174925&_nc_ohc=gGEP1tIGTYQAX_1peKT&_nc_ht=scontent-ort2-2.xx&oh=7df5abf2171edd34f25677922418bf0b&oe=5FFC5447" alt="Picture of Vicky" style="width:100%">
      <div class="container">
        <h2>Victoria Soto</h2>
        <p class="title">Assistant</p>
        <p>assisting in day to day duties with the team</p>
        <p>victoria.soto@gmail.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="column">
      <div class="card">
        <img src="https://res.cloudinary.com/campus-job/image/upload/t_student-public-page/v1/profile_pictures/bEOamyPxP6_20170822.jpg" alt="Picture of Sam" style="width:100%">
        <div class="container">
          <h2>Samantha Bone</h2>
          <p class="title">Assistant</p>
          <p>assisting in day to day duties with the team</p>
          <p>samantha.bone@gmail.com</p>
          <p><button class="button">Contact</button></p>
        </div>
      </div>
    </div>
  <footer class="footer">
    <a href="#"><i class="fa fa-facebook-official"></i></a>
    <a href="#"><i class="fa fa-pinterest-p"></i></a>
    <a href="#"><i class="fa fa-twitter"></i></a>
    <a href="#"><i class="fa fa-linkedin"></i></a>
    <p class="w3-medium">
    Powered by <a href="https://canvas.colum.edu/courses/17363" target="_blank">Professor Douglas & Team</a>
    </p>
  </footer>
  <script>
  var myIndex = 0;
    carousel();
    
    function carousel() {
      var i;
      var x = document.getElementsByClassName("mySlides");
      for (i = 0; i < x.length; i++) {
        x[i].style.display = "none";
      }
      myIndex++;
      if (myIndex > x.length) {myIndex = 1}
      x[myIndex-1].style.display = "block";
      setTimeout(carousel, 3000);
    }</script>
</body>
</html>