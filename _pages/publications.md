---

title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
.publications-list {
  margin-top: 1.5rem;
}

.publications-list .pub-item {
  margin: 2rem 0;
  padding-bottom: 1.5rem;
  border-bottom: 1px solid #e5e5e5;
}

/* 标题：允许正常换行 */
.publications-list .pub-title {
  margin-top: 0;
  margin-bottom: 0.8rem;
  line-height: 1.25;
  white-space: normal;
}

/* 这一层负责横向滑动：文字和图片作为整体一起滑动 */
.publications-list .pub-card {
  overflow-x: auto;
  overflow-y: hidden;
  -webkit-overflow-scrolling: touch;
}

/* 这一层是真正的横向内容 */
.publications-list .pub-card-inner {
  display: grid;
  grid-template-columns: max-content var(--fig-w, 18em);
  gap: 1.25rem;
  align-items: start;
  width: max-content;
  min-width: 100%;
}

/* 没有图片的论文只显示文字 */
.publications-list .pub-card.no-figure .pub-card-inner {
  grid-template-columns: max-content;
}

.publications-list .pub-info {
  min-width: 0;
}

/* 每一条信息保持单行 */
.publications-list .pub-line {
  display: block;
  margin: 0.25rem 0;
  line-height: 1.55;
  white-space: nowrap;
}

.publications-list .pub-figure {
  width: var(--fig-w, 18em);
}

.publications-list .pub-figure img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
}

/* 小屏幕时也仍然保持整体横向滑动，不把图片强行放到下面 */
@media (max-width: 640px) {
  .publications-list .pub-card-inner {
    grid-template-columns: max-content var(--fig-w, 16em);
  }

  .publications-list .pub-figure {
    width: var(--fig-w, 16em);
  }
}
</style>

### Upcoming Next Paper ...

---

<div class="publications-list">

  <div class="pub-item">
    <h3 class="pub-title">Design of APSK Constellations Approaching the Communication-Sensing Pareto Boundary for ISAC</h3>


<div class="pub-card" style="--fig-w: 18em;">
  <div class="pub-card-inner">
    <div class="pub-info">
      <span class="pub-line"><strong>Authors:</strong> <strong>Y. Shao</strong>, M. Qiu, M.-C. Lee, Y.-C. Huang, and J. Yuan</span>
      <span class="pub-line"><strong>Venue:</strong> 2026 IEEE Information Theory Workshop (ITW) (under review)</span>
      <span class="pub-line"><strong>Link:</strong> <a href="https://arxiv.org/abs/2605.25047">arXiv</a> (original version)</span>
    </div>

    <div class="pub-figure">
      <img src="{{ '/files/ITW2026.svg' | relative_url }}" alt="Proposed APSK performance">
    </div>
  </div>
</div>


  </div>

  <div class="pub-item">
    <h3 class="pub-title">On the Rate Region of I.I.D. Discrete Signaling and Treating Interference as Noise for the Gaussian Broadcast Channel</h3>


<div class="pub-card" style="--fig-w: 18em;">
  <div class="pub-card-inner">
    <div class="pub-info">
      <span class="pub-line"><strong>Authors:</strong> <strong>Y. Shao</strong> and M. Qiu</span>
      <span class="pub-line"><strong>Venue:</strong> 2026 IEEE International Symposium on Information Theory (ISIT) (accepted)</span>
      <span class="pub-line"><strong>Date:</strong> 2026-03-28</span>
      <span class="pub-line"><strong>Link:</strong> <a href="http://arxiv.org/abs/2604.04092">arXiv</a> (extended version)</span>
    </div>

    <div class="pub-figure">
      <img src="{{ '/files/ISIT2026.svg' | relative_url }}" alt="Proposed Rate Region">
    </div>
  </div>
</div>


  </div>

  <div class="pub-item">
    <h3 class="pub-title">Fast Aging-Aware Cell-to-Path Timing Reliability Prediction with Fine-Grained Transistor Stress Modeling</h3>


<div class="pub-card no-figure">
  <div class="pub-card-inner">
    <div class="pub-info">
      <span class="pub-line"><strong>Authors:</strong> F. Hu, S. J. Babu, <strong>Y. Shao</strong>, J. Liu, Y. Pan, S. Singhal, and X. Guo</span>
      <span class="pub-line"><strong>Venue:</strong> IEEE Transactions on Reliability (under review)</span>
    </div>
  </div>
</div>


  </div>

</div>
