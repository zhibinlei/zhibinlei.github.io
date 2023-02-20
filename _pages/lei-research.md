---
title: "Research"
permalink: /research/
author_profile: true
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 30%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  top: 100%;
  left: 0px;
  color: black;
  font-size: 15px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10%;
  right: 10%;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>
</head>
<body>

<div style="text-align:left">
  <h2>Single-sided subduction (SSS): High trench retreat rate & back-arc extension</h2>  
  <p>Models can self-consistently generate a variety of trench retreat rate and induce different extent of extension within a homogeneous and mobile overriding plate. This is achieved by verying merely the age/thickness of the subducting slab and overriding plate under a well-tested rheology setup. slideshow gallery tested: tabbed.</p>
</div>
  
<div style="text-align:center">
  <h4>↓ View full-size images with captions on click below. ↓</h4>
</div>
  
<!-- The four columns -->
<div class="row">
  <div class="column">
    <img src="/images/zhibinlei-SSS-thermal_state.png" alt="Comparison of thermal state for models with increasing trench retreat rate." style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="/images/zhibinlei-SSS-velocity_filter.png" alt="Comparison of horizontal & vertical velocity component for models with increasing trench retreat rate, suggesting that non-uniform basal drag accounts for the rifting and spreading back-arc area." style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="/images/zhibinlei-SSS-contribution.png" alt="Contribution of this work relative to previous work." style="width:100%" onclick="myFunction(this);">
  </div>
</div>

<div class="container">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <img id="expandedImg" style="width:100%">
  <div id="imgtext"></div>
</div>

<script>
function myFunction(imgs) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = imgs.src;
  imgText.innerHTML = imgs.alt;
  expandImg.parentElement.style.display = "block";
}
</script>
</body>
</html>

/* ######################################################################################## */
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  top: 100%;
  left: 0px;
  color: black;
  font-size: 15px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10%;
  right: 10%;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>
</head>
<body>

<div style="text-align:left">
  <h2>Dual inward dipping subduction (DIDS) & progressive weakening within the overriding plate</h2>  
  <p>Relative to SSS, DIDS can generate:  1) fixed boundary condition for the middle overriding plate 2) a stronger united upwelling mantle flow. Both effects contribute to the progressive weakening, exbited as viscosity reduction, within the overriding plate.</p>
</div>
  
<div style="text-align:center">
  <h4>↓ View full-size images with captions on click below. ↓</h4>
</div>
  
<!-- The four columns -->
<div class="row">
  <div class="column">
    <img src="/images/zhibinlei-dualsp-model_setup.png" alt="Model setup." style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="/images/zhibinlei-dualsp-fixed trench + single sp.png" alt="Temporal evolution of horizontal velocity component for DIDS and  SSS." style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="/images/zhibinlei-adaptive_mesh-example.gif" alt="Animation of plate weakening (viscosity reduction) in a DIDS model." style="width:100%" onclick="myFunction(this);">
  <div class="column">
    <img src="/images/zhibinlei-dualsp-dominant deformation_mechanism.png" alt="Dominant deformation analysis for a DIDS model that pull apart the overriding plate, indicating that dislocation and yielding plays the dominant role to weaken the overriding plate." style="width:100%" onclick="myFunction(this);">
  </div>
</div>

<div class="container">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <img id="expandedImg" style="width:100%">
  <div id="imgtext"></div>
</div>

<script>
function myFunction(imgs) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = imgs.src;
  imgText.innerHTML = imgs.alt;
  expandImg.parentElement.style.display = "block";
}
</script>
</body>
</html>

  
  
  
## Inherited lateral lithospheric heterogeneities & localisation of plate weakening
