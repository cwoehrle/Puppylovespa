# Puppylovespa
<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/3/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css">

 <head> 
<title>Newtown Web Viewer</title>
</head>
 
 <style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
 
<body>
 <!-- Navigation -->
<nav class="w3-bar w3-grey">

 <a href="https://www.newtown-ct.gov/" target="_blank" class="w3-button w3-bar-item"><b>Home</b></a>
  <a href="https://www.newtown-ct.gov/technology-gis" target="_blank" class="w3-button w3-bar-item"><b>Technology and GIS homepage</b></a>
  <a href="https://portal.ct.gov/DEEP/GIS-and-Maps/Data/GIS-DATA" target="_blank" class="w3-button w3-bar-item"><b>GIS Downloads</b></a>
  <a href="https://www.newtown-ct.gov/user/2023/contact" target="_blank" class="w3-button w3-bar-item"><b>Contact</b></a>
   
</a>
</nav>
 
 <!-- Slide Show -->
 
<section>
 <img class="mySlides" src="DSC_0032.jpg" style="width:50%">
 <img class="mySlides" src="DSC_0055 (2).jpg" style="width:50%">
 <img class="mySlides" src="IMG_5716.jpg" style="width:50%">
 <img class="mySlides" src="DSC_0014.jpg" style="width:50%">
 <img class="mySlides" src="dbwatertreat3_orig.jpg" style="width:50%">
 <img class="mySlides" src="DSCN0086.jpg" style="width:50%">
                                                  
</section>
  
<!-- Band Description -->
<section class="w3-container w3-center w3-content" style="max-width:600px">
 <h2 class="w3-wide"><b>Welcome to Newtownn, CT</b></h2>
  <p class="w3-opacity"><i>Whatsup</i></p>
  <p class="w3-justify">This is the GIS homepage for the town of Newtown homies. Here, you can find our work order site to report issues, parcel data, environmental data, trail maps and much more!</p>
</section>

<!-- Band Members -->
<section class="w3-row-padding w3-center w3-light-grey">
  <article class="w3-third">
   <p><b>Service Requests</b></p>
   <a href="https://newtown.maps.arcgis.com/apps/CrowdsourceReporter/index.html?appid=90b74be29deb41599511d8368a40a8e8" target="_blank"> <img src="work.PNG" alt="Random Name" style="width:100%"> </a>
    <p>Is there a problem in your neighborhood? Let us know!</p>
  </article>
  <article class="w3-third">
   <p><b>Trail Map</b></p>
   <a href="https://newtown.maps.arcgis.com/apps/webappviewer/index.html?id=f9a51e2dc8b646d6a14ab4ed43b03f1c" target="_blank"> <img src="trail.PNG" alt="Random Name" style="width:100%"> </a>
    <p>Want to know how to hike from one end of town to the other?</p>
  </article>
  <article class="w3-third">
   <p><b>Map Data</b></p>
    <img src="Aerial.PNG" alt="Random Name" style="width:90%">
    <p>Parcels, wetlands, and aerial photos galore!</p>
  </article>
</section>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-black w3-xlarge">
  <a href="#"><i class="fa fa-facebook-official"></i></a>
  <a href="#"><i class="fa fa-pinterest-p"></i></a>
  <a href="#"><i class="fa fa-twitter"></i></a>
  <a href="#"><i class="fa fa-flickr"></i></a>
  <a href="#"><i class="fa fa-linkedin"></i></a>
 
  <p class="w3-medium">
   <a href="https://www.civicplus.com target="_blank">Government Website By CivicPlus</a>
                                                     </p>
                                                     
  <p class="w3-medium">
   <a href="https://www.newtown-ct.gov/user/login?current=node/553 target="_blank">Employee Login</a>
  </p>
</footer>

<script>
// Automatic Slideshow - change image every 3 seconds
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
}
</script>

</body>
</html>
