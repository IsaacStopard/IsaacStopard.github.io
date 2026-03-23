---
layout: single
title: "Research"
permalink: /research/
author_profile: false
classes: wide
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<h1 style="color: #3498db; font-weight: bold; border-bottom: 2px solid #eee; padding-bottom: 0px;">Explore</h1>

<div style="clear: both;"></div> 

<style>
  /* Container for the grid - using CSS Grid for better standardization */
  .explore-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 25px;
    margin-top: 15px;
  }

  /* The container for each item */
  .explore-item {
    position: relative;
    overflow: hidden;
    border-radius: 12px;
    aspect-ratio: 1 / 1;
    border: 1px solid #eee;
    display: block;
  }

  /* The image style with top alignment */
  .explore-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top; /* Standardizes view to the top of the image */
    transition: transform 0.5s ease;
    display: block;
  }

  /* The overlay that appears on hover */
  .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: rgba(44, 62, 80, 0.9); /* Dark blue tint for readability */
    opacity: 0;
    transition: opacity 0.4s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    text-align: center;
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
    font-size: 16px;
    font-weight: 600;
    line-height: 1.4;
    text-transform: none;
  }
</style>

<div class="explore-grid">

  <a href="https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008658" class="explore-item">
    <img src="/photos/papers/mSOS_paper.jpg" alt="mSOS Paper">
    <div class="overlay">
      <span class="overlay-text">Estimating the extrinsic incubation period of malaria using a mechanistic model of sporogony</span>
    </div>
  </a>

  <a href="https://www.nature.com/articles/s41467-024-47265-w" class="explore-item">
    <img src="/photos/papers/mSOS_temp_paper.jpg" alt="Temperature Paper">
    <div class="overlay">
      <span class="overlay-text">Estimating the effects of temperature on transmission of the human malaria parasite, Plasmodium falciparum</span>
    </div>
  </a>
  
  <a href="https://www.thelancet.com/journals/langlo/article/PIIS2214-109X(24)00329-2/fulltext" class="explore-item">
    <img src="/photos/papers/Lancet_ITN_paper.jpg" alt="Lancet ITN">
    <div class="overlay">
      <span class="overlay-text">The epidemiological benefit of pyrethroid–pyrrole insecticide treated nets against malaria: an individual-based malaria transmission dynamics modelling study</span>
    </div>
  </a>
  
  <a href="https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1011975" class="explore-item">
    <img src="/photos/papers/plos_dengue_paper.jpg" alt="Dengue Paper">
    <div class="overlay">
      <span class="overlay-text">Investigating the dose-dependency of the midgut escape barrier using a mechanistic model of within-mosquito dengue virus population dynamics</span>
    </div>
  </a>

  <a href="https://link.springer.com/article/10.1186/s40249-022-00935-7" class="explore-item">
    <img src="/photos/papers/feasibility_paper.jpg" alt="Feasibility Paper">
    <div class="overlay">
      <span class="overlay-text">Feasibility, acceptability, and effectiveness of non-pharmaceutical interventions against infectious diseases among crisis-affected populations: a scoping review</span>
    </div>
  </a>

  <a href="https://www.nature.com/articles/s42003-025-07949-5" class="explore-item">
    <img src="/photos/papers/DTR_paper.jpg" alt="DTR Paper">
    <div class="overlay">
      <span class="overlay-text">Modelling the effects of diurnal temperature variation on malaria infection dynamics in mosquitoes</span>
    </div>
  </a>

  <a href="https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1013035" class="explore-item">
    <img src="/photos/papers/mosquito_age_paper.jpg" alt="Mosquito Age Paper">
    <div class="overlay">
      <span class="overlay-text">Modelling the effects of adult emergence on the surveillance and age distribution of medically important mosquitoes</span>
    </div>
  </a>

  <a href="https://academic.oup.com/evolut/article/80/2/396/8342153?login=false&guestAccessKey=" class="explore-item">
    <img src="/photos/papers/evo_paper.jpg" alt="Evolution Paper">
    <div class="overlay">
      <span class="overlay-text">Immunity can impose a reproduction-survival tradeoff on human malaria parasites</span>
    </div>
  </a>

  <a href="https://journals.lww.com/aidsonline/fulltext/2019/06010/The_influence_of_constraints_on_the_efficient.14.aspx" class="explore-item">
    <img src="/photos/papers/HIV_paper.jpg" alt="HIV Paper">
    <div class="overlay">
      <span class="overlay-text">The influence of constraints on the efficient allocation of resources for HIV prevention</span>
    </div>
  </a>

  <a href="https://www.mdpi.com/2036-7449/13/1/27" class="explore-item">
    <img src="/photos/papers/cov_hosp_paper.jpg" alt="COVID Paper">
    <div class="overlay">
      <span class="overlay-text">A Dynamic Bayesian Model for Identifying High-Mortality Risk in Hospitalized COVID-19 Patients</span>
    </div>
  </a>

  <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0272442" class="explore-item">
    <img src="/photos/papers/cov_hosp_bio_paper.jpg" alt="COVID Bio Paper">
    <div class="overlay">
      <span class="overlay-text">Using patient biomarker time series to determine mortality risk in hospitalised COVID-19 patients: a comparative analysis across two New York hospitals</span>
    </div>
  </a>

</div>