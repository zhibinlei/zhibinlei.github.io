---
title: "Research"
permalink: /research/
author_profile: true
---

## Single-sided subduction (SSS): High trench retreat rate & back-arc extension

Models can self-consistently generate a variety of trench retreat rate and induce different extent of extension within a homogeneous and mobile overriding plate. This is achieved by verying merely the age/thickness of the subducting slab and overriding plate under a well-tested rheology setup. slideshow gallery tested below 3rd round.

<!-- Container for the image gallery -->
<div class="container">

  <!-- Full-width images with number text -->
  <div class="mySlides">
    <div class="numbertext">1 / 3</div>
      <img src="/images/zhibinlei-SSS-thermal_state.png" style="width:100%" alt="Comparison of thermal state for models with increasing trench retreat rate.">
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 3</div>
      <img src="/images/zhibinlei-SSS-velocity_filter.png" style="width:100%" alt="Comparison of horizontal & vertical velocity component for models with increasing trench retreat rate, suggesting that non-uniform basal drag accounts for the rifting and spreading back-arc area.">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 3</div>
      <img src="/images/zhibinlei-SSS-contribution.png" style="width:100%" alt="Contribution of this work relative to previous work.">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Image text -->
  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <!-- Thumbnail images -->
  <div class="row">
    <div class="column">
      <img class="demo cursor" src="/images/zhibinlei-SSS-thermal_state.png" style="width:100%" onclick="currentSlide(1)" alt="Comparison of thermal state for models with increasing trench retreat rate.">
    </div>
    <div class="column">
      <img class="demo cursor" src="/images/zhibinlei-SSS-velocity_filter.png" style="width:100%" onclick="currentSlide(2)" alt="Comparison of horizontal & vertical velocity component for models with increasing trench retreat rate, suggesting that non-uniform basal drag accounts for the rifting and spreading back-arc area.">
    </div>
    <div class="column">
      <img class="demo cursor" src="/images/zhibinlei-SSS-contribution.png" style="width:100%" onclick="currentSlide(3)" alt="Contribution of this work relative to previous work.">
    </div>
  </div>
</div>

* {
  box-sizing: border-box;
}

/* Position the image container (needed to position the left and right arrows) */
.container {
  position: relative;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Add a pointer when hovering over the thumbnail images */
.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* Container for image text */
.caption-container {
  text-align: center;
  background-color: #222;
  padding: 2px 16px;
  color: white;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Six columns side by side */
.column {
  float: left;
  width: 16.66%;
}

/* Add a transparency effect for thumnbail images */
.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}


let slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("demo");
  let captionText = document.getElementById("caption");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
  captionText.innerHTML = dots[slideIndex-1].alt;
}


## Dual inward dipping subduction (DIDS) & progressive weakening within the overriding plate

Relative to SSS, DIDS can generate:  1) fixed boundary condition for the middle overriding plate 2) a stronger united upwelling mantle flow. Both effects
contribute to the progressive weakening, exbited as viscosity reduction, within the overriding plate.

![zhibinlei-dualsp-model_setup.png](/images/zhibinlei-dualsp-model_setup.png)
Model setup

![zhibinlei-dualsp-fixed trench + single sp.png](/images/zhibinlei-dualsp-fixed trench + single sp.png)
Temporal evolution of horizontal velocity component for DIDS and  SSS.

![zhibinlei-adaptive_mesh-example.gif](/images/zhibinlei-adaptive_mesh-example.gif)
Animation of plate weakening (viscosity reduction) in a DIDS model.

![dualsp-dominant deformation_mechanism.png](/images/zhibinlei-dualsp-dominant deformation_mechanism.png)
Dominant deformation analysis for a DIDS model that pull apart the overriding plate, indicating that dislocation and yielding plays the dominant role to weaken the overriding plate.

## Inherited lateral lithospheric heterogeneities & localisation of plate weakening
