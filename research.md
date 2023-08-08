---
layout: page
title: "Projects"
---




<div class="wrap">
  <nav>
    <img src="https://picsum.photos/id/238/24/24" class="nav-logo" />
    <h4 class="heading-text">My Travel Journal.</h4>
  </nav>
  <div class="picture-cards">
    <img src="https://picsum.photos/id/237/125/168" alt="test Img" class="destination-pictures">
    <div class="picture-content">
      <h5 class="destination-title">Item Title here</h5>
      <p>Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem </p>
    </div>
  </div>

  <div class="picture-cards">
    <img src="https://picsum.photos/id/1016/125/168" alt="test Img" class="destination-pictures">
    <div class="picture-content">
      <h5 class="destination-title">Item Title here</h5>
      <p>Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem </p>
    </div>
  </div>

  <div class="picture-cards">
    <img src="https://picsum.photos/id/240/125/168" alt="test Img" class="destination-pictures">
    <div class="picture-content">
      <h5 class="destination-title">Item Title here</h5>
      <p>Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem Lorem isum dolor sit amet lorem </p>
    </div>
  </div>

</div>


body {
  margin: 0;
}
.wrap {
  max-width: 980px;
  margin: auto;
}

.nav-logo {
  width: 24px;
  height: 24px;
  border-radius: 50%;
}

nav {
  align-items: center;
  justify-content: center;
  display: flex;
  padding: 0.5rem;
  background-color: #f55a5a;
}

.heading-text {
  padding: 10px;
  margin: 0;
  color: white;
  font-size: 1.4rem;
  font-family: "Arial Rounded MT Bold";
}

.picture-cards {
  display: flex;
  padding: 1rem;
  border-bottom: 2px solid red;
}

.destination-pictures {
  width: 125px;
  height: 168px;
}
.picture-content {
  padding: 0 1rem;
}
