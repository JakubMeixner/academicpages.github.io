---
layout: home
title: "Jakub Meixner"
permalink: /
author_profile: false
---

<!-- === STYLES === -->
<style>
/* Background Animation */
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

.tile-win8 {
  display: block;
  padding: 1.25rem;
  text-align: center;
  border-radius: 1rem;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  text-decoration: none;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  font-weight: 600;
  height: 100%;
  color: white;
}
.tile-win8:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}
.tile-win8 h3, .tile-win8 p {
  color: white;
  margin: 0.5rem 0;
}

.grid-tiles {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 1.5rem;
}

.tile-about    { background-color: #722f37; }
.tile-research { background-color: #1b1b1b; }
.tile-tools    { background-color: #444; }
.tile-dev      { background-color: #004c99; }
</style>

<div class="animated-bg">

<!-- CONTACT BAR -->
<section style="background-color: #f4f4f4; padding: 1rem 1rem 0.5rem 1.5rem;">
  <div style="max-width: 850px; margin: auto; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <strong style="margin-right: 1rem;">Contact:</strong>
    <a href="mailto:kubameixner@gmail.com" style="display: flex; align-items: center; margin-right: 1rem;">
      <img src="https://img.icons8.com/color/48/000000/gmail-new.png" alt="Gmail" style="width: 20px; margin-right: 0.5rem;">
      kubameixner@gmail.com
    </a>
    <a href="https://github.com/JakubMeixner" target="_blank" style="display: flex; align-items: center; margin-right: 1rem;">
      <img src="https://img.icons8.com/ios-glyphs/30/000000/github.png" alt="GitHub" style="width: 20px; margin-right: 0.5rem;">
      GitHub
    </a>
    <a href="https://linkedin.com/in/jmeixner" target="_blank" style="display: flex; align-items: center;">
      <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn" style="width: 20px; margin-right: 0.5rem;">
      LinkedIn
    </a>
  </div>
</section>

<!-- HERO SECTION -->
<div style="position: relative; overflow: hidden; height: 580px; text-align: center;">
    <video autoplay muted loop playsinline
        style="position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; z-index: 0;">
    <source src="{{ '/assets/hero-fixed.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
    </video>
    
  <div style="position: absolute; inset: 0; background: rgba(0,0,0,0.35); z-index: 1;"></div>
  <div style="position: relative; z-index: 2; padding-top: 3rem; color: white;">
    <img src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Jakub Meixner" style="border-radius: 50%; width: 180px; height: 180px; object-fit: cover; box-shadow: 0 4px 10px rgba(0,0,0,0.5);">
    <h1 style="font-size: 2.5em; font-weight: 600; margin-top: 1rem;">Jakub Meixner</h1>
    <p style="font-size: 1.25em; max-width: 800px; margin: 1rem auto; color: #eee;">
      PhD student in ML and Physics<br>
      Quantum Machine Learning · ML for quantum materials · PDE modeling · Generative Modeling
    </p>
    <div style="margin-top: 1rem;">
      <a href="https://jakubmeixner.github.io/" class="btn btn--primary" style="margin-right: 1rem;" target="_blank">View CV</a>
      <a href="{{ '/projects/' | relative_url }}" class="btn">Explore Projects</a>
    </div>
  </div>
</div>

<!-- ABOUT -->
<section style="background-color: #fff; padding: 1.5rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center;">About Me</h2>
    <div class="grid-tiles">
      <a href="/cv/" class="tile-win8 tile-about">
        <h3>Affiliations</h3>
        <p>MagTop · IF PAN · IDEAS NCBR</p>
      </a>
      <a href="/research/" class="tile-win8 tile-about">
        <h3>Expertise</h3>
        <p>Quantum materials · ML for PDEs · Scientific workflows</p>
      </a>
      <a href="/about/" class="tile-win8 tile-about">
        <h3>Highlights</h3>
        <p>IEEE · ICCV · QLFuture Hackathon · GQE Workshop</p>
      </a>
    </div>
  </div>
</section>

<!-- RESEARCH -->
<section style="background-color: #f3f6fa; padding: 1.5rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center;">Research Areas</h2>
    <div class="grid-tiles">
      <a href="/research/" class="tile-win8 tile-research">
        <h3>ML for MBE</h3>
        <p>Video data · RHEED analysis · Phase transitions</p>
      </a>
      <a href="/research/" class="tile-win8 tile-research">
        <h3>Physics-Informed ML</h3>
        <p>PINNs · Neural PDEs · Diffusions</p>
      </a>
      <a href="/quantum/" class="tile-win8 tile-research">
        <h3>Quantum Computing</h3>
        <p>QML · Qiskit · PennyLane · Quantum GANs</p>
      </a>
      <a href="/agents/" class="tile-win8 tile-research">
        <h3>Agentic Tools</h3>
        <p>AutoGen · LangChain · RAG systems</p>
      </a>
    </div>
  </div>
</section>

<!-- TOOLS -->
<section style="background-color: #fff; padding: 1.5rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center;">Tools & Libraries</h2>
    <div class="grid-tiles">
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>PyTorch</h3>
        <p>Diffusions, PINNs, GNNs</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>TensorFlow & Keras</h3>
        <p>Deep learning, AutoML, CNNs</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>scikit-learn</h3>
        <p>Classical ML, preprocessing, evaluation</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>LangChain</h3>
        <p>Agents, chains, RAG pipelines</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-tools">
        <h3>AutoGen</h3>
        <p>Multi-agent scientific assistants</p>
      </a>
    </div>
  </div>
</section>

<!-- ML FLOW -->
<section style="background-color: #f0f0f8; padding: 1.5rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center;">Machine Learning Flow</h2>
    <div class="grid-tiles">
      <a href="/projects/" class="tile-win8 tile-mlflow">
        <h3>Data Acquisition</h3>
        <p>CSV, video, sensor, RHEED images</p>
      </a>
      <a href="/projects/" class="tile-win8 tile-mlflow">
        <h3>Preprocessing</h3>
        <p>OpenCV, Pandas, augmentation, denoising</p>
      </a>
      <a href="/projects/" class="tile-win8 tile-mlflow">
        <h3>Model Design</h3>
        <p>PyTorch, Keras, PINNs, GNNs, Diffusions</p>
      </a>
      <a href="/projects/" class="tile-win8 tile-mlflow">
        <h3>Training & Evaluation</h3>
        <p>TensorBoard, cross-validation, hyperopt</p>
      </a>
      <a href="/projects/" class="tile-win8 tile-mlflow">
        <h3>Deployment</h3>
        <p>Streamlit, GitHub Pages, REST APIs</p>
      </a>
    </div>
  </div>
</section>

<style>
.tile-mlflow {
  background-color: #1e2a38;
}
</style>


<!-- PROGRAMMING SKILLS -->
<section style="background-color: #f7f7f7; padding: 1.5rem;">
  <div style="max-width: 1100px; margin: auto;">
    <h2 style="text-align: center;">Programming Skills</h2>
    <div class="grid-tiles">
      <a href="/tools/" class="tile-win8 tile-dev">
        <h3>Python</h3>
        <p>PyTorch · NumPy · data science · simulations</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-dev">
        <h3>C++</h3>
        <p>Numerical simulations · OpenMP · HPC</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-dev">
        <h3>Bash & Shell</h3>
        <p>Automation · pipelines · Linux scripting</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-dev">
        <h3>Web</h3>
        <p>HTML · CSS · JS · GitHub Pages</p>
      </a>
      <a href="/tools/" class="tile-win8 tile-dev">
        <h3>LaTeX & Markdown</h3>
        <p>Technical documents · Scientific writing</p>
      </a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer style="text-align: center; margin: 4rem auto 2rem auto; font-size: 0.9em; color: #666;">
  Designed and built using GitHub Pages and Jekyll · Last updated {{ site.time | date: "%B %Y" }}
</footer>

</div>