---
layout: single
title: "About"
permalink: /about/
author_profile: false
classes: wide
---

<style>
  .profile-container {
    display: flex;
    flex-direction: row-reverse;
    gap: 40px;
    align-items: flex-start;
    margin-bottom: 40px;
  }

  .profile-image-wrapper {
    flex: 0 0 300px; /* Fixed width for the photo */
  }

  .profile-image-wrapper img {
    width: 100%;
    border-radius: 15px; /* Matches the rounded corners of your grid */
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    display: block;
  }

  .profile-text {
    flex: 1; /* Text takes up remaining space */
  }

  /* Responsive: Stack them on mobile */
  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    .profile-image-wrapper {
      flex: 0 0 auto;
      width: 80%; /* Larger on mobile for visibility */
      max-width: 300px;
    }
  }
</style>

<div class="profile-container">
  
  <div class="profile-image-wrapper">
    <img src="/photos/profile-pic.jpg" alt="Isaac Profile Photo">
  </div>

  <div class="profile-text">
    <p>
      Hello, I'm Isaac. I am a Computational Biologist, drawing on knowledge and methods from epidemiology, statistics, economics and ecology. Globally, measures of death due to infectious diseases have reduced; disease burden, however, remains concentrated in areas and people with lower socioeconomic status. My research has spanned multiple scales and methods but broadly aims to guide data-driven decision making by quantifying the impact of socioeconomic factors, environmental variables and public health interventions to reduce both the absolute burden and inequality of infectious disease transmission.
    </p>

    <p>
      Outside of work I'm a keen surfer. I've spent most of my income on rent, but what's left I've spent on surf trips. And, I've been incredibly lucky to travel for work. I enjoy running and swimming.
    </p>

    <p><strong>Work:</strong> Postdoctoral research at <a href="https://www.imperial.ac.uk/">Imperial College London</a> and the <a href="https://www.unsw.edu.au/">University of New South Wales Sydney</a>. Ecologist at <a href="https://www.fishtek.co.uk/">Fishtek Consulting</a>. Beach lifeguard.</p>

    <p><strong>Education:</strong> PhD in the <a href="https://www.imperial.ac.uk/qmee-cdt/">QMEE CDT</a>, supervised by <a href="https://ben-lambert.com/">Dr Ben Lambert</a> and <a href="https://www.imperial.ac.uk/people/thomas.churcher">Prof Thomas Churcher</a>. First class honours in Biology from Imperial College London.</p>
  </div>
</div>

<h1 style="color: #3498db; font-weight: bold; border-bottom: 2px solid #eee; padding-bottom: 10px; margin-top: 40px;">Gallery</h1>