---
title: "Unpublished findings"
permalink: /unpublished_findings/
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
  <h2>Findings that are interesting, but have not been published yet.</h2>  
  <p>May some of these findinds interests you. Collaborations are welcome from cross-deciplines.</p>
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
