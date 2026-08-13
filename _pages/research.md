---
title: " "
permalink: /research/
layout: single
author_profile: true
---


<div class="research-hero">
  <div class="research-hero-text">
    <p>
      I am a multiwavelength observational astronomer working on two main threads: cosmic-ray acceleration and transport in star-forming environments using
      Fermi-LAT gamma-ray data, and the nature of exotic nuclear transients. Click a topic below to read more.
    </p>
  </div>
</div>

<!-- ============================================================
     RESEARCH CARDS
     ============================================================ -->
<div class="research-grid">

  <div class="research-card" onclick="openModal('cr1')">
    <img src="/images/Figureplot_00.png" alt="RCW 38 multiwavelength image">
    <div class="research-card-label">
      <h3>Cosmic-Ray Acceleration in Young Star-Forming Regions</h3>
      <span class="read-more">Read more</span>
    </div>
  </div>

  <div class="research-card" onclick="openModal('cr2')">
    <img src="/images/ORION.jpg" alt="Orion BN/KL JWST">
    <div class="research-card-label">
      <h3>Cosmic-Ray Acceleration in Explosive Dispersal Outflows</h3>
      <span class="read-more">Read more</span>
    </div>
  </div>

  <div class="research-card" onclick="openModal('ant')">
    <img src="/images/ANT.jpg" alt="Galaxies">
    <div class="research-card-label">
      <h3> Ambiguous Nuclear Transients </h3>
      <span class="read-more">Read more</span>
    </div>
  </div>



<!-- ============================================================
     MODALS
     ============================================================ -->

<!-- Modal 1: Cosmic Rays -->
<div id="modal-cr1" class="research-modal">
  <div class="modal-content">
    <span class="modal-close" onclick="closeModal('cr1')">&times;</span>
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
      We look at the young star-forming region RCW 38 (age &lt; 0.5 Myr),
      where we detect gamma-ray emission at a 22&sigma; significance level,
      providing strong evidence that stellar winds can accelerate cosmic-ray particles.
      These observations allow us to constrain the cosmic-ray acceleration efficiency,
      diffusion timescales, and pressure within the region.
    </p>
    <figure class="paper-fig" style="max-width: 55%; margin: 1.5rem auto;">
      <img src="/images/Figureplot_00.png" style="width:100%;">
      <figcaption>
        Multiwavelength image of RCW 38, with the IR Spitzer image in red,
        the Chandra X-ray broad-band data in green, and the background-subtracted
        &gt;2 GeV Fermi-LAT counts map in blue.
      </figcaption>
    </figure>
    <p>
    In our analysis, we found that the cosmic ray acceleration efficiency and the diffusion coefficient are degenerate parameters, which means they cannot be constrained independently. So, we have to assume a value for one to constrain the other. Therefore, if we assume a diffusion coefficient value typically seen in the ISM (10²⁸ cm²/s ),  we get an efficiency of about 40%. Alternatively, if we assume an efficiency equal to the canonical SNR value of 10%, we get a diffusion coefficient of 2.5 × 10²⁷ cm²/s – an order of magnitude lower than the ISM value, which implies that CR are trapped in the region for a longer period. Both scenarios are physically interesting: either the cluster is extremely efficient at accelerating CRs, or CRs are being trapped inside the cluster and are confined for longer than in the general ISM. Overall, our results show that star-forming regions younger than 3 Myr are efficient cosmic-ray accelerators, with important implications for galaxy simulations and for understanding the origin of galactic cosmic rays.
</p>
    <ul>
      <li>Read the RCW 38 paper: <a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...976...98P/abstract" target="_blank">ADS</a></li>
    </ul>
  </div>
</div>

<div id="modal-cr2" class="research-modal">
  <div class="modal-content">
    <span class="modal-close" onclick="closeModal('cr2')">&times;</span>
    <h2>Cosmic-Ray Acceleration in Explosive Dispersal Outlfows</h2>
    <p><strong>Keywords:</strong> Explosive Molecular Outflows, Protostellar Mergers</p>
     <p>
      In this work, we identify a new class of Fermi gamma-ray sources associated with explosive dispersal outflows. These explosive events result from the dynamical disruption of a young, massive stellar system, like the merger of massive protostars – releasing at least 10^46 erg of energy into their environments. They consist of straight, narrow CO filaments which are isotropic and all point back to a common origin. They have been discovered using the ALMA and JWST telescopes.  Their occurrence rate is once every 100 years across the Milky Way – just like supernovae. We focus on DR21 EDO in the Cygnus-X star-forming complex, detected at 35&sigma; significance. Across the EDO sample, no more than 18% of outflow kinetic energy goes into CR acceleration. And when we account for the event rate across the Galaxy, EDOs contribute at least 1% of the Galactic CR budget that has traditionally been attributed to supernovae. That's a lower limit because there are possibly more EDOs in the galaxy.
 </p>
    <figure class="paper-fig" style="max-width: 70%; margin: 1.5rem auto;">
      <img src="/images/project1_plot.jpg" style="width:100%;">
      <figcaption>
        Gamma-ray luminosity versus mechanical power for EDOs and young star-forming regions.
      </figcaption>
    </figure>
    <ul>
      <li>Read the Explosive Dispersal Outflows paper: <a href="https://ui.adsabs.harvard.edu/abs/2025arXiv250902679P/abstract" target="_blank">ADS</a></li>
    </ul>
  </div>
</div>


<!-- Modal 2: AT2020adpi -->
<div id="modal-ant" class="research-modal">
  <div class="modal-content">
    <span class="modal-close" onclick="closeModal('ant')">&times;</span>
    <h2>Ambiguous Nuclear Transients</h2>
    <p><strong>Keywords:</strong> Active Galactic Nuclei, Tidal Disruption Events</p>
    <p>
      I study transient events associated with supermassive black holes, which offer
      unique insights into accretion physics in galactic nuclei. In recent multiwavelength
      studies, I analyzed AT2020adpi and AT2021yky, which are luminous optical/UV nuclear transients
      that do not fit into existing categories such as tidal disruption events or standard AGN variability.
    </p>
    <p>
      AT2020adpi has an unusual TDE-like light-curve evolution and a strong mid-infrared flare. The optical spectra show broad Balmer and Mg II lines, indicative of an AGN association. However, the evolution of broad lines in the optical specta are similar to what has been observed in TDEs. This combination of observed features suggests an accretion episode driven by either a stellar disruption within an active disk or instabilities in an active nucleus. 
    </p>
    <figure class="paper-fig" style="max-width: 55%; margin: 1.5rem auto;">
      <img src="/images/project2_plot.jpg" style="width:100%;">
      <figcaption>
        Comparison of AT2020adpi with other known transients in the optical absolute
        magnitude versus characteristic timescale parameter space. This source occupies the parameter space associated with most energetic transients known.
      </figcaption>
    </figure>
<p>
  Another interesting source that I studied is AT2021yky. It is a fast blue optical transient that has characteristics similar to faint and fast TDEs. However, its optical spectra are unusual for TDEs since it has a largely featureless spectra with broad H_alpha lines that turn on post-peak. We compare this source with Luminous fast blue optical transients (LFBOTs) and faint and fast (FaF) TDEs. The cooler blackbody temperature of this transient and the absence of He II and Balmer emission lines other than H_alpha favour its classification as an ANT instead.
</p>   
    <figure class="paper-fig" style="max-width: 55%; margin: 1.5rem auto;">
      <img src="/images/L40.pdf" style="width:100%;">
      <figcaption>
        Peak luminosity versus decline rate, which is the logarithmic change in bolometric luminosity between peak and 40 days post-peak, for AT2021yly along with a sample of TDEs, ANTs, and other luminous transients.
      </figcaption>
    </figure>
    <ul>
      <li>Read the paper AT2020adpi paper: <a href="https://ui.adsabs.harvard.edu/abs/2025OJAp....851453P/abstract" target="_blank">ADS</a></li>
       <li>Read the paper AT2021yky paper: <a href="https://ui.adsabs.harvard.edu/abs/2026arXiv260806462P/abstract" target="_blank">ADS</a></li>
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
