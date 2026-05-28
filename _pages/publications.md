---
title: "Publications"
permalink: /publications/
author_profile: true
--------------------

<style>
.publication-scroll {
  display: flex;
  gap: 1.25rem;
  overflow-x: auto;
  padding: 0.5rem 0 1.5rem;
  scroll-snap-type: x mandatory;
}

.publication-card {
  flex: 0 0 360px;
  scroll-snap-align: start;
  border: 1px solid #e5e7eb;
  border-radius: 16px;
  background: #ffffff;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.06);
  overflow: hidden;
}

.publication-card img {
  width: 100%;
  height: 190px;
  object-fit: contain;
  background: #f8fafc;
  border-bottom: 1px solid #e5e7eb;
}

.publication-card-content {
  padding: 1rem;
}

.publication-card h3 {
  margin-top: 0;
  margin-bottom: 0.6rem;
  font-size: 1.05rem;
  line-height: 1.35;
}

.publication-card p {
  margin: 0.35rem 0;
  font-size: 0.9rem;
  line-height: 1.45;
}

.pub-status {
  display: inline-block;
  margin-top: 0.5rem;
  padding: 0.2rem 0.55rem;
  border-radius: 999px;
  background: #eef2ff;
  font-size: 0.78rem;
  font-weight: 600;
}

.pub-links {
  margin-top: 0.75rem;
}

.pub-links a {
  margin-right: 0.75rem;
  font-weight: 600;
}

.pub-placeholder {
  height: 190px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #f8fafc;
  color: #64748b;
  font-size: 0.9rem;
  border-bottom: 1px solid #e5e7eb;
}

@media (max-width: 600px) {
  .publication-card {
    flex-basis: 85vw;
  }
}
</style>

<div class="publication-scroll">

  <div class="publication-card">
    <div class="pub-placeholder">Upcoming work</div>
    <div class="publication-card-content">
      <h3>Upcoming Next Paper ...</h3>
      <p>More details will be added soon.</p>
      <span class="pub-status">In preparation</span>
    </div>
  </div>

  <div class="publication-card">
    <img src="{{ '/files/apsk-isac.png' | relative_url }}" alt="APSK constellations for ISAC">
    <div class="publication-card-content">
      <h3>Design of APSK Constellations Approaching the Communication-Sensing Pareto Boundary for ISAC</h3>
      <p><strong>Authors:</strong> <strong>Y. Shao</strong>, M. Qiu, M.-C. Lee, Y.-C. Huang, and J. Yuan</p>
      <p><strong>Venue:</strong> 2026 IEEE Information Theory Workshop</p>
      <p><strong>Status:</strong> Under review</p>
      <p><strong>Note:</strong> IEEE Information Theory Workshop is a major international workshop of the IEEE Information Theory Society.</p>
      <span class="pub-status">ITW 2026 under review</span>
      <div class="pub-links">
        <a href="https://arxiv.org/abs/2605.25047">arXiv</a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <img src="{{ '/files/isit-rate-region.png' | relative_url }}" alt="Rate region of discrete signaling for Gaussian broadcast channel">
    <div class="publication-card-content">
      <h3>On the Rate Region of I.I.D. Discrete Signaling and Treating Interference as Noise for the Gaussian Broadcast Channel</h3>
      <p><strong>Authors:</strong> <strong>Y. Shao</strong> and M. Qiu</p>
      <p><strong>Venue:</strong> 2026 IEEE International Symposium on Information Theory</p>
      <p><strong>Status:</strong> Accepted</p>
      <p><strong>Note:</strong> The IEEE International Symposium on Information Theory is the flagship conference of the IEEE Information Theory Society.</p>
      <p><strong>Date:</strong> 2026-03-28</p>
      <span class="pub-status">ISIT 2026 accepted</span>
      <div class="pub-links">
        <a href="http://arxiv.org/abs/2604.04092">arXiv</a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <img src="{{ '/files/timing-reliability.png' | relative_url }}" alt="Aging-aware timing reliability prediction">
    <div class="publication-card-content">
      <h3>Fast Aging-Aware Cell-to-Path Timing Reliability Prediction with Fine-Grained Transistor Stress Modeling</h3>
      <p><strong>Authors:</strong> F. Hu, S. J. Babu, <strong>Y. Shao</strong>, J. Liu, Y. Pan, S. Singhal, and X. Guo</p>
      <p><strong>Venue:</strong> IEEE Transactions on Reliability</p>
      <p><strong>Status:</strong> Under review</p>
      <span class="pub-status">Journal under review</span>
    </div>
  </div>

</div>
