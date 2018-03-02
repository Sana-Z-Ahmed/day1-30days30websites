<html>
  <head>
    <title>Portfolio</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
    <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
      </script>
    </script>
    <style>
      body {
          font: 400 15px Lato, sans-serif;
          line-height: 1.8;
          color: #818181;
      }

      h2 {
          font-size: 24px;
          text-transform: uppercase;
          color: #303030;
          font-weight: 600;
          margin-bottom: 30px;
      }

      h4 {
          font-size: 19px;
          line-height: 1.375em;
          color: #303030;
          font-weight: 400;
          margin-bottom: 30px;
      }

      .navbar {
          margin-bottom: 0;
          background-color: #5b7f98;
          z-index: 9999;
          border: 0;
          font-size: 12px !important;
          line-height: 1.42857143 !important;
          letter-spacing: 4px;
          border-radius: 0;
          font-family: Montserrat, sans-serif
      }

      .navbar li a, .navbar .navbar-brand {
          color: #fff !important;
      }

      .navbar-nav li a:hover, .navbar-nav li.active a {
          color: #f4511e !important;
          background-color: #fff !important;
      }

      .navbar-default .navbar-toggle {
          border-color: transparent;
          color: #fff !important;
      }      

      .jumbotron { 
         background-color: #7c334f; /* Merlot Pink */
         color: #ece4d8;
         padding: 100px 25px;
         font-family: Montserrat, sans-serif
      }
      
      .bg-1 {
        background-color: #fff6e9;
      }

      .bg-2 {
        background-color: #ece4d8;
      }

      .container-fluid {
        padding: 60px 50px;
      }

      .logo {
        font-size: 200px;
      }

      @media screen and (max-width: 768px) {
    
        .col-sm-4 {
          text-align: center;
          margin: 25px 0;
        }
      }

      .logo-small {
        color: #7c334f;
        font-size: 50px;
      }

      .logo {
          color: #7c334f;
          font-size: 200px;
      }

      .thumbnail {
          padding: 0 0 15px 0;
          border: none;
          border-radius: 0;
      }

      .thumbnail img {
          width: 80%;
          height: 80%;
          margin-bottom: 10px;
      }

      .carousel-control.right, .carousel-control.left {
          background-image: none;
          color: #cd5f77;
      }

      .carousel-indicators li {
          border-color: #f4511e;
      }

      .carousel-indicators li.active {
          background-color: #ece4d8;
      }

      .item h4 {
          font-size: 19px;
          line-height: 1.375em;
          font-weight: 400;
          font-style: italic;
          margin: 70px 0;
          color: #7c3352;
      }

      .item span {
          font-style: normal;
      }

      .slideanim {visibility:hidden;}
      .slide {
          /* The name of the animation */
          animation-name: slide;
          -webkit-animation-name: slide; 
          /* The duration of the animation */
          animation-duration: 1s; 
          -webkit-animation-duration: 1s;
          /* Make the element visible */
          visibility: visible; 
      }

      /* Go from 0% to 100% opacity (see-through) and specify the percentage from when to slide in the element along the Y-axis */
      @keyframes slide {
          0% {
              opacity: 0;
              transform: translateY(70%);
          } 
          100% {
              opacity: 1;
              transform: translateY(0%);
          } 
      }
      @-webkit-keyframes slide {
          0% {
              opacity: 0;
              -webkit-transform: translateY(70%);
          } 
          100% {
              opacity: 1;
              -webkit-transform: translateY(0%);
          }
      }
    </style>
  </head>
  <body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">
    <nav class="navbar navbar-default navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span> 
          </button>
          <a class="navbar-brand" href="#">Sana Fatima</a>
        </div>
        <div class="collapse navbar-collapse" id="myNavbar">
          <ul class="nav navbar-nav navbar-right">
            <li><a href="#about">KNOW ME</a></li>
            <li><a href="#services">SKILLS</a></li>
            <li><a href="#portfolio">PORTFOLIO</a></li>
            <li><a href="#pricing">QUOTES</a></li>
            <li><a href="#contact">CONTACT</a></li>
          </ul>
        </div>
      </div>
    </nav>   

    <header>
      <div class="jumbotron text-center">
         <h1>Sana Fatima</h1> 
         <p>Welcome to my designing playground!</p> 
      </div>
    </header>


    <div class="container-fluid bg-1">
      <div class="row">
        <div class="col-sm-8">
          <h2>Know Me</h2>
          <h4>Lorem ipsum..</h4> 
          <p>Lorem ipsum..</p>
          <button class="btn btn-default btn-lg">GitHub</button>
        </div>
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-user logo"></span>
        </div>
      </div>
    </div>


    <div class="container-fluid bg-2">
      <div class="row">
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-road logo"></span> 
        </div>
        <div class="col-sm-8">
          <h2>My Journey</h2>
          <h4><strong></strong> Our mission lorem ipsum..</h4> 
          <p><strong></strong> Our vision Lorem ipsum..</p>
        </div>
      </div>
    </div>


    <div class="container-fluid text-center bg-1">
      <h2>SKILLS</h2>
      <h4>What I offer</h4>
      <br>
      <div class="row">
        <div class="col-sm-4">
          <span class="fa fa-html5 logo-small"></span>
          <h4>HTML5</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
        <div class="col-sm-4">
          <span class="fa fa-css3 logo-small"></span>
          <h4>CSS3</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
        <div class="col-sm-4">
          <span class=""></span>
          <h4>Bootstrap</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
      </div>
      <br><br>
      <div class="row">
        <div class="col-sm-4">
          <span class=""></span>
          <h4>JavaScript</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
        <div class="col-sm-4">
          <span class=""></span>
          <h4>jQuery</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
        <div class="col-sm-4">
          <span class="fa fa-wordpress logo-small"></span>
          <h4>Wordpress</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
      </div>
    </div>


    <div class="container-fluid text-center bg-2">
      <h2>Portfolio</h2>
      <h4>What I have created</h4>
      <div class="row text-center">
        <div class="col-sm-4">
          <div class="thumbnail">
            <img src="https://img00.deviantart.net/72d5/i/2014/229/0/2/robin_williams_tribute_by_emilystepp-d7ut3q0.jpg" alt="Tribute Page for Free Code Camp">
            <p><a href="https://codepen.io/SanaZAhmed/pen/MQaxoV"></a><strong>Tribute Page for Free Code Camp Project</strong></p>
            <p>I built a tribute page for Robbie Williams.</p>
           
          </div>
        </div>
        <div class="col-sm-4">
          <div class="thumbnail">
            <img src="https://images.pexels.com/photos/905913/pexels-photo-905913.jpeg?h=350&auto=compress&cs=tinysrgb" alt="Portfolio page for Free Code Camp">
            <p><strong>Portfolio Page for Free Code Camp Project</strong></p>
            <p>My first portfolio page based on Simply Me Theme from W3Schools.</p>
            <a href="https://codepen.io/SanaZAhmed/pen/zRrxoO"></a>
          </div>
        </div>
        <div class="col-sm-4">
          <div class="thumbnail">
            <img src="https://images.pexels.com/photos/34676/pexels-photo.jpg?h=350&auto=compress&cs=tinysrgb" alt="My Portfolio Website">
            <p><strong>My Portfolio Website</strong></p>
            <p>Built a portfolio website for myself.</p>
          </div>
        </div>
      </div>


      <h2>My Favourite Quotes</h2>
      <div id="myCarousel" class="carousel slide text-center bg-1" data-ride="carousel">
        <!-- Indicators -->
        <ol class="carousel-indicators">
          <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
          <li data-target="#myCarousel" data-slide-to="1"></li>
          <li data-target="#myCarousel" data-slide-to="2"></li>
          <li data-target="#myCarousel" data-slide-to="3"></li>
          <li data-target="#myCarousel" data-slide-to="4"></li>
          <li data-target="#myCarousel" data-slide-to="5"></li>
          <li data-target="#myCarousel" data-slide-to="6"></li>
          <li data-target="#myCarousel" data-slide-to="7"></li>
        </ol>

        <!-- Wrapper for slides -->
        <div class="carousel-inner" role="listbox">
          <div class="item active">
          <h4>"The Way Get Started Is To Quit Talking And Begin Doing."<br><span style="font-style:normal;">Walt Disney</span></h4>
          </div>
          <div class="item">
            <h4>"You Learn More From Failure Than From Success. Don’t Let It Stop You. Failure Builds Character."<br><span style="font-style:normal;">Unknown</span></h4>
          </div>
          <div class="item">
            <h4>"If You Are Working On Something That You Really Care About, You Don’t Have To Be Pushed. The Vision Pulls You."<br><span style="font-style:normal;">Steve Jobs</span></h4>
          </div>
          <div class="item">
            <h4>"People Who Are Crazy Enough To Think They Can Change The World, Are The Ones Who Do."<br><span style="font-style:normal;">Rob Siltanen</span></h4>
          </div>
          <div class="item">
            <h4>"The Only Limit To Our Realization Of Tomorrow Will Be Our Doubts Of Today."<br><span style="font-style:normal;">Franklin D. Roosevelt</span></h4>
          </div>
          <div class="item">
            <h4>"What You Lack In Talent Can Be Made Up With Desire, Hustle And Giving 110% All The Time."<br><span style="font-style:normal;">Don Zimmer</span></h4>
          </div>
          <div class="item">
            <h4>"You Are Never Too Old To Set Another Goal Or To Dream A New Dream."<br><span style="font-style:normal;">C.S. Lewis</span></h4>
          </div>
          <div class="item">
            <h4>"Fake It Until You Make It! Act As If You Had All The Confidence You Require Until It Becomes Your Reality."<br><span style="font-style:normal;">Brian Tracy</span></h4>
          </div>
        </div>

        <!-- Left and right controls -->
        <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
          <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
          <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>


      <div class="container-fluid bg-grey">
        <h2 class="text-center">Reach Me</h2>
        <div class="row">
          <div class="col-sm-5">
            <p>To know more about me, to request more information about myself or my experience, to ask for my resume, random questions about the world, the meaning of life, feel free to drop in a line. I will reach out ASAP! </p>
            <p><span class="glyphicon glyphicon-map-marker"></span>Hyderabad, India</p>
            <p><span class="glyphicon glyphicon-phone"></span> +91 1515151515</p>
            <p><span class="glyphicon glyphicon-envelope"></span> fatimasana3112@gmail.com /p> 
          </div>
          <div class="col-sm-7">
            <div class="row">
              <div class="col-sm-6 form-group">
                <input class="form-control" id="name" name="name" placeholder="Name" type="text" required>
              </div>
              <div class="col-sm-6 form-group">
                <input class="form-control" id="email" name="email" placeholder="Email" type="email" required>
              </div>
            </div>
            <textarea class="form-control" id="comments" name="comments" placeholder="Comment" rows="5"></textarea><br>
            <div class="row">
              <div class="col-sm-12 form-group">
                <button class="btn btn-default pull-right" type="submit">Send</button>
              </div>
            </div> 
          </div>
        </div>
      </div>


     <!-- Add Google Maps -->
      <div id="googleMap" style="height:400px;width:100%;"></div>
      <script>
      function myMap() {
      var myCenter = new google.maps.LatLng(17.385044, 78.486671);
      var mapProp = {center:myCenter, zoom:12, scrollwheel:false, draggable:false, mapTypeId:google.maps.MapTypeId.ROADMAP};
      var map = new google.maps.Map(document.getElementById("googleMap"),mapProp);
      var marker = new google.maps.Marker({position:myCenter});
      marker.setMap(map);
      }
      </script>
      <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
      <!--
      To use this code on your website, get a free API key from Google.
      Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
      -->
      

      <footer class="container-fluid text-center">
        <a href="#myPage" title="To Top">
          <span class="glyphicon glyphicon-chevron-up"></span>
        </a>
        <p><a href="http://sanaahmed.in" title="Visit w3schools">sanaahmed.in</a></p>
      </footer>

      
      <script>
      $(document).ready(function(){
        // Add smooth scrolling to all links in navbar + footer link
        $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
          // Make sure this.hash has a value before overriding default behavior
          if (this.hash !== "") {
            // Prevent default anchor click behavior
            event.preventDefault();

            // Store hash
            var hash = this.hash;

            // Using jQuery's animate() method to add smooth page scroll
            // The optional number (900) specifies the number of milliseconds it takes to scroll to the specified area
            $('html, body').animate({
              scrollTop: $(hash).offset().top
            }, 900, function(){
         
              // Add hash (#) to URL when done scrolling (default click behavior)
              window.location.hash = hash;
            });
          } // End if
        });
        
        $(window).scroll(function() {
          $(".slideanim").each(function(){
            var pos = $(this).offset().top;

            var winTop = $(window).scrollTop();
              if (pos < winTop + 600) {
                $(this).addClass("slide");
              }
          });
        });
      })
      </script>
  </body>
</html>
  
