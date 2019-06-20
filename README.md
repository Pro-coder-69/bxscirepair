# website
<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

body, html {
  height: 100%;
  line-height: 1.8;
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url("https://cdn.vox-cdn.com/thumbor/1aFhodAxJJEoTDsly4kgCDiPElo=/0x0:2040x1360/1200x800/filters:focal(948x690:1274x1016)/cdn.vox-cdn.com/uploads/chorus_image/image/60986247/cracked-iphone-stock-1197.0.0.jpg");
  min-height: 100%;
}

.w3-top .w3-button {
  padding: 16px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top" style="margin:auto">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide"></a> 
    <img src = "https://cdn.discordapp.com/attachments/353766529277362188/591040049492131851/yes.png"
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">ABOUT</a>
      <a href="#store" class="w3-bar-item w3-button"><img src="https://cdn.discordapp.com/attachments/353766529277362188/591318506742480942/Webp.net-resizeimage.png"> STORE</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#store" onclick="w3_close()" class="w3-bar-item w3-button">STORE</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">Affordable & Quality Repair</span><br>
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">Affordable & Quality Repair</span><br>
    <span class="w3-large">Right at your School</span>
    <p><a href="#contact" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Don't delay, get a repair today!</a></p>
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">ABOUT THE COMPANY</h3>
  <p class="w3-center w3-large">Key focuses of our company</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fa fa-diamond w3-margin-bottom w3-jumbo w3-center"></i>
      <p class="w3-large">Quality</p>
      <p>We belive in proper repair with good parts.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-heart w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Passion</p>
      <p>E-Waste is a growing international crisis. Not only is repair more affordable, it's also cleaner.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-desktop w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Responsive</p>
      <p>We strive to please the customer, if you have any feedback feel free to let us know!</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-cog w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Support</p>
      <p>If you need help with your device feel free to contact us!</p>
    </div>
  </div>
</div>

<!-- Store -->

  <div class="w3-row-padding w3-padding-16" id="store">
    <h3 class="w3-center">STORE</h3>
    <div class="w3-third w3-margin-bottom">
      <img src="https://cdn.discordapp.com/attachments/353766529277362188/591138813720395776/6s.png" alt="iPhone 6s" style="width:100%">
      <div class="w3-container w3-light-grey">
        <h3>iPhone 6s</h3>
        <h6 class="w3-opacity">$180</h6>
        <p>Space Grey 64gb Factory Unlocked</p>
        <p>In stock</p>
        <p class="w3-large"><i class="fa fa-bath"></i> <i class="fa fa-phone"></i> <i class="fa fa-wifi"></i></p>
        <button class="w3-button w3-block w3-black w3-margin-bottom">Buy Now</button>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="https://cdn.discordapp.com/attachments/353766529277362188/591138813720395776/6s.png" alt="iPhone 6s 2" style="width:100%">
      <div class="w3-container w3-light-grey">
        <h3>iPhone 6s</h3>
        <h6 class="w3-opacity">$180</h6>
        <p>Space Grey 64gb Factory Unlocked</p>
        <p>In stock</p>
        <p class="w3-large"><i class="fa fa-bath"></i> <i class="fa fa-phone"></i> <i class="fa fa-wifi"></i> <i class="fa fa-tv"></i></p>
        <button class="w3-button w3-block w3-black w3-margin-bottom">Buy Now</button>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="https://cdn.discordapp.com/attachments/353766529277362188/591138813720395776/6s.png" alt="iPhone 6s 3" style="width:100%">
      <div class="w3-container w3-light-grey">
        <h3>iPhone 6s</h3>
        <h6 class="w3-opacity">$180</h6>
        <p>Space Grey 64gb Factory Unlocked</p>
        <p>In stock</p>
        <p class="w3-large"><i class="fa fa-bath"></i> <i class="fa fa-phone"></i> <i class="fa fa-wifi"></i> <i class="fa fa-tv"></i> <i class="fa fa-glass"></i> <i class="fa fa-cutlery"></i></p>
        <button class="w3-button w3-block w3-black w3-margin-bottom">Buy Now</button>
      </div>
    </div>
  </div>

<!-- Want a Customized Look? -->
<div class="w3-container" style="padding:128px 16px">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Want a Customized Look?</h3>
      <p>Look no further! It's not a skin, it's your phone!</p>
      <p><a href="#work" class="w3-button w3-black"><i class="fa fa-th"> </i> View Our Works</a></p>
    </div>
    <div class="w3-col m6">
      <img class="w3-image w3-round-large" src="https://cdn.discordapp.com/attachments/353766529277362188/591114244955570186/image0.jpg" alt="Custom_Phone" width="500" height="700">
    </div>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">CONTACT</h3>
  <p class="w3-center w3-large">Let's get in touch. Send us a message:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> The Bronx High School of Science</p>
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> goodfixez@gmail.com</p>
    <br>
        <button class="w3-button w3-black" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
    <!-- Image of location/map -->
    <img src="https://cdn3.creativecirclemedia.com/riverdalepress/original/1438808105_770c.jpg" style="width:100%;margin-top:48px">
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <a href="https://www.google.com/"><i class="fa fa-facebook-official w3-hover-opacity"></i></a>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
  </div>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
 
<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

</script>

</body>
</html>
