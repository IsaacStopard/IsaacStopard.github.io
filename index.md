---
layout: splash
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<div style="max-width: 900px; margin: 0 auto; padding: 40px 20px;">

  <img src="/profile-pic.jpg" alt="Isaac J Stopard" style="float: right; width: 250px; margin: 0 0 20px 20px; border-radius: 10px;">

  # Hi, I'm Isaac
  
  I research the impact of socioeconomic inequality, environmental variables and public health interventions on infectious disease transmission.

  <div style="clear: both;"></div> <style>
    /* Container for the grid */
    .explore-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 30px; 
      justify-content: flex-start;
      margin-top: 60px;
    }

    /* The container for each item */
    .explore-item {
      position: relative;
      flex: 1 1 280px; /* Adjusts size based on screen width */
      max-width: 400px;
      overflow: hidden;
      border-radius: 12px;
      aspect-ratio: 1/1;
      border: 1px solid #eee;
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
      background-color: rgba(0, 0, 0, 0.7); /* Darker tint for better text contrast */
      opacity: 0;
      transition: 0.5s ease;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    /* Show overlay and zoom image on hover */
    .explore-item:hover .overlay {
      opacity: 1;
    }
    
    .explore-item:hover img {
      transform: scale(1.05);
    }

    .overlay-text {
      color: white;
      font-size: 24px;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
  </style>

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

</div>
