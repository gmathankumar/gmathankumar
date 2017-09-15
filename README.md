<!DOCTYPE html>
<html>
<title>Má Profílé</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url("https://www.w3schools.com/w3images/parallax1.jpg");
    min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url("http://calinno.com/images/resource/parallax1.jpg");
    min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
    background-image: url("http://www.ceremoniasnativas.com/images/background/home-parallax3.jpg");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}
.rotateimg {
    background-color: yellow;
    /* Rotate div */
    -ms-transform: rotate(270deg); /* IE 9 */
    -webkit-transform: rotate(270deg); /* Chrome, Safari, Opera */
    transform: rotate(270deg);
}

</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar" id="myNavbar">
    <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-button">HOME</a>
    <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> PORTFOLIO</a>
    <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
    <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">PORTFOLIO</a>
    <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity w3-hover-red">MATHAN <span class="w3-hide-small">KUMAR</span> GNANASAMBANDAM</span>
  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT ME</h3>
  <p class="w3-center"><em>I love coding</em></p>
  <p>Over 6 plus years of experience in the Design, Development, Testing and Implementation of various web based applications for different business organizations. Seeking a challenging position with ample amount of opportunities to grow professionally in this industry..</p>

<!--       <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-user w3-margin-right"></i>Mathan Kumar</b></p><br>
	  
      <img src="https://drive.google.com/uc?export=view&id=0ByIdq28ukLG4V2RQcEdaalFDZEE" class=" rotateimg w3-round w3-image w3-opacity w3-hover-opacity-off" alt="Photo of Me" width="250" height="100">
    </div> -->	
  <div class=" w3-row ">
  <div class="w3-col m3 w3-center w3-padding-large"></div>
    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-medium">
      <p> <ul class="w3-ul w3-card-4">
    <li class="w3-bar">
      <div class="w3-bar-item">
	        <img src="https://www.iconexperience.com/_img/o_collection_png/green_dark_grey/512x512/plain/clipboard_check_edit.png" class="w3-bar-item w3-circle w3-hide-small" style="width:85px">
        <span class="w3-large">Expertise In</span><br>
        <span>Messaging, plug-in, batch processes and web services implementations</span>
      </div>
    </li>

    <li class="w3-bar">    
      <div class="w3-bar-item">
	   <img src="https://www.iconexperience.com/_img/o_collection_png/green_dark_grey/512x512/plain/clipboard_check_edit.png" class="w3-bar-item w3-circle w3-hide-small" style="width:85px">
        <span class="w3-large">Guidewire integration</span><br>
        <span>PolicyCenter 8.0,ClaimCenter 8.0 and BillingCenter 8.0
</span>
      </div>
    </li>

    <li class="w3-bar">
	<div class="w3-bar-item">
	        <img src="https://www.iconexperience.com/_img/o_collection_png/green_dark_grey/512x512/plain/clipboard_check_edit.png" class="w3-bar-item w3-circle w3-hide-small" style="width:85px">
        <span class="w3-large">Integration systems</span><br>
        <span>ISO, GL,CRS, Aggregator, Bulk invoicing</span>
      </div>
    </li>
  </ul>.</p>
    </div>
  </div>
  <p class="w3-large w3-center w3-padding-16">Im really good at:</p>
  <p class="w3-wide"><i class="fa fa-book"></i>Learning</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:90%">90%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-cogs"></i>Guidewire Integration</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:85%">85%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-android"></i>Android/Spring MVC</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:75%">75%</div>
  </div>
    <p class="w3-wide"><i class="fa fa-android"></i>Agile</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:75%">80%</div>
  </div>
      <p class="w3-wide"><i class="fa fa-android"></i>Gradle, git</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:75%">70%</div>
  </div>
  </div>


<div class="w3-row w3-center w3-dark-grey w3-padding-16">
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">6+</span><br>
    Years Experience
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">4+</span><br>
    Projects Done
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-large">2+</span><br>
    <p class="w3-tooltip">Certifications<span class="w3-text"> (<em>Guidwire integration specialist and Java 5 </em>)</span></p>
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">100+</span><br>
    Client Meetings
  </div>
</div>

<!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">PORTFOLIO</span>
  </div>
</div>

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64" id="portfolio">
  <h3 class="w3-center">MY WORK</h3>
  <p class="w3-center"><em>Here are some of my latest work.<br> Click on the images to make them bigger</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="https://github.com/gmathankumar/gmathankumar/blob/master/LV=.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="LiverPool Victoria, Croydon">
    </div>

    <div class="w3-col m3">
      <img src="https://github.com/gmathankumar/gmathankumar/blob/master/ALFA_data.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="ALFA, Montgomery">
    </div>

    <div class="w3-col m3">
      <img src="https://github.com/gmathankumar/gmathankumar/blob/master/ATA_data.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="ATA, Washington">
    </div>
		 <div class="w3-col m3">
   
      <img src="https://github.com/gmathankumar/gmathankumar/blob/master/SBI_data.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="SBI,India">
    </div>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
  </div>
</div>

<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
  <h3 class="w3-center">WHERE I DWELL</h3>
  <p class="w3-center"><em>I'd love to hear from you!</em></p>

  <div class="w3-row w3-padding-32 w3-section">
    <div class="w3-col m4 w3-container">
      <!-- Add Google Maps -->
      <div id="googleMap" class="w3-round-large w3-greyscale" style="width:100%;height:400px;"></div>
    </div>
    <div class="w3-col m8 w3-panel">
      <div class="w3-large w3-margin-bottom">
        <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Croydon, UK<br>
        <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: +44 7979596797<br>
        <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: gmathankumar.24@mail.com<br>
      </div>
      <p>Swing by for a cup of <i class="fa fa-coffee"></i>, or leave me a note:</p>
      <form action="/action_page.php" target="_blank">
        <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
          </div>
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
          </div>
        </div>
        <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
        <button class="w3-button w3-black w3-right w3-section" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </form>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
 
<!-- Add Google Maps -->
<script>
function myMap()
{
  myCenter=new google.maps.LatLng(51.367151, -0.087986);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card-2" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card-2 w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}


</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAFDZPeBDEP7kmY5PwZPZqLVxwd7NnvkCw&callback=myMap"></script>

</body>
</html>
