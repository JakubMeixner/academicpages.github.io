---
layout: home
title: "Jakub Meixner"
permalink: /
author_profile: false
---

<!-- === STYLES === -->
<style>
/* === Background Animation === */
.animated-bg {
  animation: gradientShift 20s ease infinite;
  background: linear-gradient(-45deg, #f4f4f4, #e5e5e5, #f4f4f4, #dcdcdc);
  background-size: 400% 400%;
}
@keyframes gradientShift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

/* === Tiles (Harvard Style) === */
.tile-win8 {
  display: block;
  padding: 1.25rem;
  text-align: center;
  border-radius: 0.75rem;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  text-decoration: none;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  font-weight: 600;
  height: 100%;
  color: white;
  text-shadow: 0 1px 2px rgba(0,0,0,0.3);
}
.tile-win8:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}
.tile-win8 h3,
.tile-win8 p {
  color: white;
  margin: 0.5rem 0;
}
.grid-tiles {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 1.5rem;
}

/* === Color themes === */
.tile-about    { background-color: #722f37; }
.tile-research { background-color: #222222; }
.tile-tools    { background-color: #5a5a5a; }
</style>

<div class="animated-bg">

<!-- === CONTACT SECTION WITH LOGOS === -->
<section style="background-color: #f4f4f4; padding: 1rem 1rem 0.5rem 1.5rem; margin-top: 0rem;">
  <div style="max-width: 850px; margin: auto; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <strong style="margin-right: 1rem;">Contact:</strong>

    <a href="mailto:kubameixner@gmail.com" style="display: flex; align-items: center; margin-right: 1rem; text-decoration: none; color: inherit;">
      <img src="https://img.icons8.com/color/48/000000/gmail-new.png" alt="Gmail" style="width: 20px; margin-right: 0.5rem;">
      kubameixner@gmail.com
    </a>

    <a href="https://github.com/JakubMeixner" target="_blank" style="display: flex; align-items: center; margin-right: 1rem; text-decoration: none; color: inherit;">
      <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png" alt="GitHub" style="width: 20px; margin-right: 0.5rem;">
      GitHub
    </a>

    <a href="https://linkedin.com/in/jmeixner" target="_blank" style="display: flex; align-items: center; text-decoration: none; color: inherit;">
      <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn" style="width: 20px; margin-right: 0.5rem;">
      LinkedIn
    </a>
  </div>
</section>




<!-- === HERO SECTION WITH GOLDEN NEBULA VIDEO BACKGROUND === -->
<div style="position: relative; overflow: hidden; height: 580px; text-align: center;">

  <!-- Background Video -->
  <video autoplay muted loop playsinline style="position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; z-index: 0;">
    <source src="/assets/hero-bg.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <!-- Semi-dark Overlay for Contrast -->
  <div style="position: absolute; inset: 0; background: rgba(0,0,0,0.35); z-index: 1;"></div>

  <!-- Hero Content -->
  <div style="position: relative; z-index: 2; padding-top: 3rem; color: white;">
    <img src="/images/profile.jpg" alt="Jakub Meixner" style="border-radius: 50%; width: 180px; height: 180px; object-fit: cover; box-shadow: 0 4px 10px rgba(0,0,0,0.5);">
    <h1 style="font-size: 2.5em; font-weight: 600; margin-top: 1rem;">Jakub Meixner</h1>
    <p style="font-size: 1.25em; max-width: 800px; margin: 1rem auto; color: #eee;">
      Research Assistant in Theoretical Physics and Machine Learning<br>
      Institute of Physics, Polish Academy of Sciences & MagTop
    </p>
    <div style="margin-top: 1rem;">
      <a href="/cv/" class="btn btn--primary" style="margin-right: 1rem;">View CV</a>
      <a href="/portfolio/" class="btn">Explore Projects</a>
    </div>
  </div>
</div>


<!-- === ABOUT SECTION === -->
<section style="background-color: #ffffff; padding: 0.2rem 0.2rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center; margin-bottom: 0.5rem;">About</h2>
    <div class="grid-tiles">
      <a href="/cv/" class="tile-win8 tile-about">
        <h3>Current Roles</h3>
        <p>IF PAN & MagTop, Warsaw</p>
      </a>
      <a href="/research/" class="tile-win8 tile-about">
        <h3>Focus</h3>
        <p>ML for MBE & quantum materials</p>
      </a>
      <a href="/about/" class="tile-win8 tile-about">
        <h3>Background</h3>
        <p>IBM AI, Qiskit, PennyLane</p>
      </a>
    </div>
  </div>
</section>

<!-- === RESEARCH AREAS === -->
<section style="background-color: #f3f6fa; padding: 0.2rem 0.2rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center; margin-bottom: 1rem;">Research Areas</h2>
    <div class="grid-tiles">
      <a href="/research/" class="tile-win8 tile-research">
        <h3>MBE + DL</h3>
        <p>Surface phase detection</p>
      </a>
      <a href="/research/" class="tile-win8 tile-research">
        <h3>Physics-Informed</h3>
        <p>PINNs for PDEs</p>
      </a>
      <a href="/quantum/" class="tile-win8 tile-research">
        <h3>Quantum Computing</h3>
        <p>VQAs & AQFT modeling</p>
      </a>
      <a href="/agents/" class="tile-win8 tile-research">
        <h3>Scientific Agents</h3>
        <p>LLMs + AutoGen pipelines</p>
      </a>
    </div>
  </div>
</section>

<!-- === TOOLS & LIBRARIES === -->
<section style="padding: 1rem 1rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center; margin-bottom: 0.2rem;">Tools & Libraries</h2>
    <div class="grid-tiles">
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>PyTorch</h3>
        <p>PINNs, U-Nets, Diffusions</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>JAX</h3>
        <p>Autodiff & vectorization</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>LangChain</h3>
        <p>RAG agents & chains</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>AutoGen</h3>
        <p>Multi-agent workflows</p>
      </a>
    </div>
  </div>
</section>

<!-- === FOOTER === -->
<footer style="text-align: center; margin: 4rem auto 2rem auto; font-size: 0.9em; color: #666;">
  Designed and built using GitHub Pages and Jekyll · Last updated {{ site.time | date: "%B %Y" }}
</footer>

</div>
