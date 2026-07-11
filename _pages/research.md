---
title: " "
permalink: /research/
layout: single
author_profile: true
---


<div class="research-hero">
  <div class="research-hero-text">
    <p>
      I am a multiwavelength observational astronomer working on two main threads:
      cosmic-ray acceleration and transport in star-forming environments using
      <em>Fermi</em>-LAT gamma-ray data, and the nature of exotic nuclear transients. Click a topic below to read more.
    </p>
  </div>
</div>

<!-- ============================================================
     RESEARCH CARDS
     ============================================================ -->
<div class="research-grid">

  <div class="research-card" onclick="openModal('cr')">
    <img src="/images/Figureplot_00.png" alt="RCW 38 multiwavelength image">
    <div class="research-card-label">
      <h3>Cosmic-Ray Acceleration in Young Star-Forming Regions</h3>
      <span class="read-more">Read more</span>
    </div>
  </div>

  <div class="research-card" onclick="openModal('ant')">
    <img src="/images/project2_plot.jpg" alt="AT2020adpi comparison plot">
    <div class="research-card-label">
      <h3>Ambiguous Nuclear Transients</h3>
      <span class="read-more">Read more</span>
    </div>
  </div>

</div>

<!-- ============================================================
     MODALS
     ============================================================ -->

<!-- Modal 1: Cosmic Rays -->
<div id="modal-cr" class="research-modal">
  <div class="modal-content">
    <span class="modal-close" onclick="closeModal('cr')">&times;</span>
    <h2>Cosmic-Ray Acceleration in Young Star-Forming Regions</h2>
    <p><strong>Keywords:</strong> Fermi-LAT, Stellar Winds, Diffusion Coefficient</p>
    <p>
      Cosmic rays play a key role in shaping galaxies, influencing how they form and evolve.
      Understanding where these high-energy particles come from is therefore essential for
      modeling galaxy evolution and cosmic-ray feedback. While supernova remnants are
      traditionally considered the main accelerators of cosmic rays, recent observations
      suggest that young, massive star-forming regions may also contribute significantly.
    </p>
    <p>
      In this work, we use Fermi-LAT gamma-ray observations to investigate cosmic-ray
      acceleration in two such environments.
    </p>
    <p>
      First, we look at the young star-forming region RCW 38 (age &lt; 0.5 Myr),
      where we detect gamma-ray emission at a 22&sigma; significance level,
      providing strong evidence that stellar winds can accelerate cosmic-ray particles.
      These observations allow us to constrain the cosmic-ray acceleration efficiency,
      diffusion timescales, and pressure within the region.
    </p>
    <figure class="paper-fig" style="max-width: 55%; margin: 1.5rem auto;">
      <img src="/images/Figureplot_00.png" style="width:100%;">
      <figcaption>
        Multiwavelength image of RCW 38, with IR Spitzer image in red,
        the Chandra X-ray broad-band data in green, and the background subtracted
        &gt;2 GeV Fermi-LAT counts map in blue.
      </figcaption>
    </figure>
    <p>
      We also identify a new class of Fermi gamma-ray sources associated with explosive
      dispersal outflows, focusing on DR21 in the Cygnus-X star-forming complex,
      detected at 35&sigma; significance. For this system, we quantify
      the acceleration efficiency of explosive outflows and evaluate their contribution
      to the overall galactic cosmic-ray budget.
    </p>
    <p>
      Overall, our results show that star-forming regions younger than ~3 Myr are efficient
      cosmic-ray accelerators, with important implications for galaxy simulations and for
      understanding the origin of galactic cosmic rays.
    </p>
    <figure class="paper-fig" style="max-width: 70%; margin: 1.5rem auto;">
      <img src="/images/project1_plot.jpg" style="width:100%;">
      <figcaption>
        Gamma-ray luminosity versus mechanical power for EDOs and young star-forming regions.
      </figcaption>
    </figure>
    <ul>
      <li>Read the RCW 38 paper: <a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...976...98P/abstract" target="_blank">ADS</a></li>
      <li>Read the Explosive Dispersal Outflows paper: <a href="https://ui.adsabs.harvard.edu/abs/2025arXiv250902679P/abstract" target="_blank">ADS</a></li>
    </ul>
  </div>
</div>

<!-- Modal 2: AT2020adpi -->
<div id="modal-ant" class="research-modal">
  <div class="modal-content">
    <span class="modal-close" onclick="closeModal('ant')">&times;</span>
    <h2>Unraveling the Nature of the Nuclear Transient AT2020adpi</h2>
    <p><strong>Keywords:</strong> Active Galactic Nuclei, Tidal Disruption Events</p>
    <p>
      I study transient events associated with supermassive black holes, which offer
      unique insights into accretion physics in galactic nuclei. In a recent multiwavelength
      study, I analyzed AT2020adpi, a luminous optical/UV nuclear transient
      at z&nbsp;=&nbsp;0.26 that does not fit into existing categories such as tidal disruption
      events or standard AGN variability.
    </p>
    <p>
      Its unusual light curve, strong mid-infrared flare, and evolving emission-line features
      suggest an accretion episode driven by either a stellar disruption within an active disk
      or instabilities in an active nucleus. This event highlights both the diversity of nuclear
      transients and the importance of coordinated, multiwavelength observations.
    </p>
    <figure class="paper-fig" style="max-width: 55%; margin: 1.5rem auto;">
      <img src="/images/project2_plot.jpg" style="width:100%;">
      <figcaption>
        Comparison of AT2020adpi with other known transients in the optical absolute
        magnitude versus characteristic timescale parameter space.
      </figcaption>
    </figure>
    <ul>
      <li>Read the paper: <a href="https://ui.adsabs.harvard.edu/abs/2025OJAp....851453P/abstract" target="_blank">ADS</a></li>
    </ul>
  </div>
</div>

<!-- ============================================================
     STYLES
     ============================================================ -->
<style>
.research-hero {
  background: url('/images/research_banner.jpg') center center / cover no-repeat;
  background-color: #1a1a2e;
  padding: 3rem 2rem;
  margin: -1rem -1rem 2.5rem -1rem;
  border-radius: 4px;
}
.research-hero-text {
  background: rgba(0,0,0,0.55);
  color: #f0f0f0;
  padding: 1.5rem 2rem;
  border-radius: 4px;
  max-width: 800px;
  font-size: 1.05rem;
  line-height: 1.75;
}
.research-hero-text em { color: #c8d8f0; }

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.5rem;
  margin-bottom: 2.5rem;
}

.research-card {
  position: relative;
  overflow: hidden;
  border-radius: 6px;
  cursor: pointer;
  box-shadow: 0 2px 8px rgba(0,0,0,0.12);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  background: #fff;
}
.research-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.18);
}
.research-card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
  margin: 0;
}
.research-card-label {
  padding: 0.9rem 1rem 1rem;
  border-top: 2px solid #e8e8e8;
}
.research-card-label h3 {
  margin: 0 0 0.4rem 0;
  font-size: 0.95rem;
  color: #222;
  line-height: 1.4;
}
.read-more {
  font-size: 0.85rem;
  color: #555;
  text-decoration: underline;
}

.research-modal {
  display: none;
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.6);
  z-index: 9999;
  overflow-y: auto;
  padding: 2rem 1rem;
  box-sizing: border-box;
}
.modal-content {
  background: #fff;
  max-width: 750px;
  margin: 2rem auto;
  padding: 2.5rem 2.5rem 2rem;
  border-radius: 6px;
  position: relative;
  line-height: 1.75;
  font-size: 0.95rem;
}
.modal-content h2 {
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 1.3rem;
}
.modal-content p, .modal-content ul { margin-bottom: 1rem; }
.modal-content a { color: #1a6496; }
.modal-content figcaption {
  font-size: 0.82rem;
  color: #555;
  text-align: center;
  margin-top: 0.4rem;
  font-style: italic;
}

.modal-close {
  position: absolute;
  top: 1rem; right: 1.2rem;
  font-size: 1.8rem;
  cursor: pointer;
  color: #999;
  line-height: 1;
}
.modal-close:hover { color: #222; }

@media (max-width: 600px) {
  .research-grid { grid-template-columns: 1fr; }
  .modal-content { padding: 1.5rem 1.2rem; }
}
</style>

<!-- ============================================================
     JAVASCRIPT
     ============================================================ -->
<script>
function openModal(id) {
  document.getElementById('modal-' + id).style.display = 'block';
  document.body.style.overflow = 'hidden';
}
function closeModal(id) {
  document.getElementById('modal-' + id).style.display = 'none';
  document.body.style.overflow = '';
}
document.addEventListener('click', function(e) {
  if (e.target.classList.contains('research-modal')) {
    e.target.style.display = 'none';
    document.body.style.overflow = '';
  }
});
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') {
    document.querySelectorAll('.research-modal').forEach(function(m) {
      m.style.display = 'none';
    });
    document.body.style.overflow = '';
  }
});
</script>
