---
layout: page
title: "Projects"
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
h3 {text-align: center;}
p {text-align: center;}
* {
  box-sizing: border-box;
}

body {
/*  background-color: #000000; */
  padding: 20px;
  font-family: Arial;
}

/* Center website */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
/*  background-color: black;*/
  padding: 10px;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 2400px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 1200px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<!-- MAIN (Center website) -->
<div class="main">

<h1 style="color:white;">MYLOGO.COM</h1>
<hr>

<h2 style="color:white;">PORTFOLIO</h2>
<p style="color:white;">Resize the browser window to see the responsive effect.</p>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src="/res1.jpg" alt="Mountains" style="width:100%">
      <h3 style="color:white;"> Computational modeling of failure in fluid-structure interaction </h3>
       <p style="color:white;">Fluid-structure interaction (FSI) is a phenomenon widespread in science and engineering, ranging from biomedical to aeronautics applications among many others. In spite of this great relevance, FSI models have struggled to account for two aspects:

1. Incorporating structural failure.
2. Incorporating complex contitutive behavior of the solid.
We have developed a novel particle-based framework to model FSI problems that can incorporate both the above aspects with ease..</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="/res2.jpg" alt="Lights" style="width:100%">
      <h3 style="color:white;"> <a href="https://phanindrasp.github.io/blog/"> Learning interaction force in particle simulations using deep learning:</a>. </h3>
      <p style="color:white;">Particle-based simulations involve treating a domain (solid or a fluid for instance) as a bunch of particles that are interacting with each other in a certain fashion. Given particle trajectory data, the proposed ANN spits out the interaction force.</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="/res3.jpg" alt="Nature" style="width:100%">
      <h3 style="color:white;"> Does nature always prefer a least resistance path? - An experiment:</h3>
      <p style="color:white;"></p>
    </div>
  </div>
    <div class="column">
    <div class="content">
    <img src="/res4.jpg" alt="Mountains" style="width:100%">
      <h3 style="color:white;"> Estimating the life of ball bearings in electric drives: </h3>
       <p style="color:white;">Ball bearings in electric drives are subject to electric erosion, which causes small pits on the surface. This reduces the life of the ball bearings. </p>
    </div>
  </div>
    <div class="column">
    <div class="content">
    <img src="/res5.jpg" alt="Mountains" style="width:100%">
      <h3 style="color:white;"> Exploring fractal-inspired heat exchanger geometries:</h3>
       <p style="color:white;">LHeat exchangers are widely used in various industries. We explore novel heat exchanger geometries inspired by space filling fractal curves.</p>
    </div>
  </div>
<!-- END GRID -->


</body>
</html>

