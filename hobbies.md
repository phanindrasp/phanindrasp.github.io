---
layout: page
title: "Hobbies"
---

<html>
<head>
<style>
h3 {text-align: center;}
p {text-align: center;}

* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>How to create side-by-side images with the CSS float property:</p>

<div class="row">
  <div class="column">
    <img src="/carnatic.png" alt="Snow" style="width:100%">
     <h3 style="color:white;"> Carnatic music</h3>
     <p style="color:white;">Lorem ipsum dolor sit amet, tempor prodesset eos no. Temporibus necessitatibus sea ei, at tantas oporteat nam. Lorem ipsum dolor sit amet, tempor prodesset eos no.</p>
  </div>
  <div class="column">
    <img src="/star.jpg" alt="Forest" style="width:100%">
    <h3 style="color:white;"> Stargazing</h3>
     <p style="color:white;">Lorem ipsum dolor sit amet, tempor prodesset eos no. Temporibus necessitatibus sea ei, at tantas oporteat nam. Lorem ipsum dolor sit amet, tempor prodesset eos no.</p>
  </div>
  <div class="column">
    <img src="/res.jpg" alt="Mountains" style="width:100%">
    <h3 style="color:white;"> Philosophy</h3>
     <p style="color:white;">Lorem ipsum dolor sit amet, tempor prodesset eos no. Temporibus necessitatibus sea ei, at tantas oporteat nam. Lorem ipsum dolor sit amet, tempor prodesset eos no.</p>
  </div>
</div>

</body>
</html>

