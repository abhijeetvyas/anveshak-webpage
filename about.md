---
layout: page
title: About Us
image:
menu: true
order: 1
---

## Vision

Team Anveshak was set up with a vision to inspire students to work on challenging problems in space exploratory robotics. Our underlying vision has now expanded with the team aiming to not only develop an all terrain rover but also educate people on the importance of space research. In future, Team Anveshak aspires to assist various <b>Space Agencies</b>, <b>Defence Organizations</b> & <b>Ministries of the Govt. of India</b> in developing disaster management systems and deploying scientific expeditions or reconnaissance missions.

## History and Achievements

The foundations of the team were laid by the senior undergraduates and alumni of the Robotics Club under Center For Innovation, IIT Madras in 2016. The team takes great pride in it’s progress since its’ establishment  with our rover “Aurora” being designed & manufactured in a short time frame of about 6 months. The team secured a position among the top 30 teams from all over the world in its debut attempt at URC 2017. One of three teams from India, Team Anveshak cleared the preliminary levels of the competition from amongst 80+ teams from all over the world. The team’s performance in Utah captured the attention of prominent national dailies - The Times of India, India Today- reiterating our commitment to developing world class technologies in India & pushing the boundaries of innovation.


## Gallery
<html>

<meta name="viewport" content="width=device-width, initial-scale=1">

<body>

<div class="w3-content w3-display-container">
  <img class="mySlides" src="/assets/img/gallery/1.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/2.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/3.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/4.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/5.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/6.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/7.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/8.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/9.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/10.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/11.jpg" style="width:100%">
  <img class="mySlides" src="/assets/img/gallery/12.jpg" style="width:100%">

  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>

</body>
</html>

<style>
img {
  border-radius: 5px;
  border: 2px solid #73AD121;
  padding: 20
}
</style>
