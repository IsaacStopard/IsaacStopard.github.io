---
layout: splash
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<img src="/profile-pic.jpg" alt="Your Name" style="float: right; width: 250px; margin-left: 20px; border-radius: 10px;">

Hi, I'm Isaac, I research the impact of socioeconomic inequality, environmental variables and public health interventions on infectious disease transmission.

---

<style>
  /* Container for the grid */
  .explore-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 40px; 
    justify-content: flex-start;
    margin-top: 80px; /* Moves the grid lower */
  }

  /* The container for each item */
  .explore-item {
    position: relative;
    flex: 0 1 250px; /* Increased size from 120px */
    overflow: hidden;
    border-radius: 12px;
    aspect-ratio: 1/1;
  }

  /* The image style */
  .explore-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
  }

  /* The overlay that appears on hover */
  .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    opacity: 0;
    transition: .5s ease;
    background-color: rgba(0, 0, 0, 0.6); /* Dark tint */
    display: flex;
    align-items: center;
    justify-content: center;
  }

  /* Show overlay and zoom image on hover */
  .explore-item:hover .overlay {
    opacity: 1;
  }
  
  .explore-item:hover img {
    transform: scale(1.1);
  }

  .overlay-text {
    color: white;
    font-size: 20px;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
</style>

---
### Explore

<div class="explore-grid">

  <a href="/about/" class="explore-item">
    <img src="/rnli.jpg" alt="About">
    <div class="overlay">
      <div class="overlay-text">About</div>
    </div>
  </a>

  <a href="/research/" class="explore-item">
    <img src="/assets/images/research-thumb.jpg" alt="Research">
    <div class="overlay">
      <div class="overlay-text">Research</div>
    </div>
  </a>

</div>
