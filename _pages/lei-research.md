---
title: "Research"
permalink: /research/
author_profile: true
---

## Single-sided subduction (SSS): High trench retreat rate & back-arc extension

Models can self-consistently generate a variety of trench retreat rate and induce different extent of extension within a homogeneous and mobile overriding plate. This is achieved by verying merely the age/thickness of the subducting slab and overriding plate under a well-tested rheology setup. slideshow gallery tested below 1 round.


<div class="slideshow-container">
  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="/images/zhibinlei-SSS-thermal_state.png" style="width:100%">
    <div class="caption">Comparison of thermal state for models with increasing trench retreat rate.</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="/images/zhibinlei-SSS-velocity_filter.png" style="width:100%">
    <div class="caption">Comparison of horizontal & vertical velocity component for models with increasing trench retreat rate, suggesting that non-uniform basal drag accounts for the rifting and spreading back-arc area.</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    <img src="/images/zhibinlei-SSS-contribution.png" style="width:100%">
    <div class="caption">Contribution of this work relative to previous work.</div>
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
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
}
</script>


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
