---
permalink: /halo-lab/
title: ""
excerpt: ""
layout: default
author_profile: false
sidebar:
  - image: /images/halo/halo-logo.png
    image_alt: "HALO Lab"
---

<style>
.team-section {
  margin-bottom: 2.5em;
}
.team-section h2 {
  font-size: 1.05em;
  font-weight: 700;
  color: #1a2e5a;
  border-left: 4px solid #3a6cc4;
  padding-left: 0.75em;
  margin-bottom: 1.2em;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.team-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
  gap: 1.1em;
}

@media (max-width: 480px) {
  .team-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 0.75em;
  }
  .member-photo {
    width: 80px;
    height: 80px;
  }
}

.member-card {
  background: #fff;
  border: 1px solid #e4eaf5;
  border-radius: 12px;
  padding: 1.2em 0.85em 1em;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  box-shadow: 0 2px 8px rgba(58,108,196,0.07);
  transition: box-shadow 0.2s, transform 0.2s;
}
.member-card:hover {
  box-shadow: 0 6px 20px rgba(58,108,196,0.13);
  transform: translateY(-2px);
}

.member-photo {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  overflow: hidden;
  margin-bottom: 0.65em;
  background: #e8edf5;
  flex-shrink: 0;
}
.member-photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.member-name {
  font-size: 0.88em;
  font-weight: 700;
  margin: 0 0 0.18em;
  line-height: 1.3;
  color: #1a2e5a;
}

.member-affil {
  font-size: 13px !important;
  color: #aaa;
  margin: 0 0 0.18em;
  line-height: 1.4;
}


.member-footer {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 0.3em;
  justify-content: center;
  margin-top: 0.55em;
  width: 100%;
}
.scholar-icon {
  color: #4a7fc1;
  font-size: 1.15em;
  line-height: 1;
  text-decoration: none;
  flex-shrink: 0;
}
.scholar-icon:hover {
  color: #1a4a8a;
  text-decoration: none;
}

.paper-tag {
  display: inline-block;
  font-size: 0.6em;
  font-weight: 700;
  padding: 0.12em 0.38em;
  border-radius: 4px;
  background: #eef2fa;
  color: #2c50a0;
  text-decoration: none;
  border: 1px solid #c8d5ee;
  white-space: nowrap;
  flex-shrink: 0;
}
.paper-tag:hover {
  background: #3a6cc4;
  color: #fff;
  border-color: #3a6cc4;
  text-decoration: none;
}
</style>

<div class="team-section">
<h2>PhD Students</h2>
<div class="team-grid">

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/zirui-song.jpg" alt="Zirui Song" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Zirui Song</p>
  <p class="member-affil">BS @ UTS</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://ziruisongbest.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=fmKRIPUAAAAJ" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://arxiv.org/abs/2505.16517">Embodied AI</a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/lang-gao.jpg" alt="Lang Gao" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Lang Gao</p>
  <p class="member-affil">BS @ HUST</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://heartyhaven.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=LzKcdl8AAAAJ" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://aclanthology.org/2025.acl-long.1233/">Interpretability</a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/jinghui-zhang.jpg" alt="Jinghui Zhang" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Jinghui Zhang</p>
  <p class="member-affil">BS @ SDU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://znull-1220.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=qDDj9nkAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://dl.acm.org/doi/abs/10.1145/3746027.3754828">Interpretability</a>
  </div>
</div>

</div>
</div>

<div class="team-section">
<h2>Visiting Students</h2>
<div class="team-grid">

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/akash-ghosh.jpg" alt="Akash Ghosh" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Akash Ghosh</p>
  <p class="member-affil">PhD @ IIT Patna</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=NWc6Pw8AAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <span class="paper-tag">AI4Science</span>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/puning-yang.jpg" alt="Puning Yang" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Puning Yang</p>
  <p class="member-affil">MS @ UCAS</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=_QGfhW8AAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/fengxian-ji.jpg" alt="Fengxian Ji" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Fengxian Ji</p>
  <p class="member-affil">BS @ NEU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=__L9dy4AAAAJ&hl=zh-CN" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  </div>
</div>

</div>
</div>

<div class="team-section">
<h2>PhD Students (Co-supervised)</h2>
<div class="team-grid">

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/ruihong-zeng.jpg" alt="Ruihong Zeng" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Ruihong Zeng</p>
  <p class="member-affil">MS @ SYSU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=hCt0gK0AAAAJ&hl=zh-CN" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/chong-tian.jpg" alt="Chong Tian" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Chong Tian</p>
  <p class="member-affil">BS @ SDU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=MTZF0pEAAAAJ&hl=zh-CN" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://aclanthology.org/2025.emnlp-main.619/">Fact Checking</a>
  </div>
</div>


<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/junior-tonga.webp" alt="Junior Tonga" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Junior Tonga</p>
  <p class="member-affil">MS @ ENS Paris-Saclay</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://juniortonga.github.io/" title="Website"><i class="fas fa-home"></i></a>
  </div>
</div>

</div>
</div>

<div class="team-section">
<h2>Master Students</h2>
<div class="team-grid">

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/chenxi-wang.jpg" alt="Chenxi Wang" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Chenxi Wang</p>
  <p class="member-affil">BS @ XJU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://aurora-cx.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=Gtj8924AAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://aclanthology.org/2025.findings-acl.866/">Interpretability</a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/ishita-agarwal.jpg" alt="Ishita Agarwal" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Ishita Agarwal</p>
  <p class="member-affil">BS @ Sharda University</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://www.linkedin.com/in/ishitaaagarwal/?originalSubdomain=in" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/besher-hassan.jpg" alt="Besher Hassan" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Besher Hassan</p>
  <p class="member-affil">BS @ Ajman University</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=RPD3000AAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/muhammad-airlangga.jpg" alt="Muhammad Cendekia Airlangga" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Muhammad Kia</p>
  <p class="member-affil">BE @ ITS</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://sites.google.com/view/mcairlangga/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=GXhAThEAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/dequan-yang.jpg" alt="Dequan Yang" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Dequan Yang</p>
  <p class="member-affil">PhD @ SJTU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://www.linkedin.com/in/dequan-yang-58b183162/?originalSubdomain=ae" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/fadli-aulawi.jpg" alt="Fadli Aulawi Al Ghiffari" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Fadli Aulawi</p>
  <p class="member-affil">BS @ Univ. of Indonesia</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://www.linkedin.com/in/fadliaulawi/?originalSubdomain=id" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/youssef-khalil.jpg" alt="Youssef Mohamed Khalil" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Youssef Khalil</p>
</div>

</div>
</div>

<div class="team-section">
<h2>Past Research Associates</h2>
<div class="team-grid">

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/kaiyang-wan.jpg" alt="Kaiyang Wan" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Kaiyang Wan</p>
  <p class="member-affil">BS @ BUPT</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://kaiyangwan.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=v_faxAsAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://arxiv.org/abs/2509.21199">Reasoning</a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/zixiang-xu.jpg" alt="Zixiang Xu" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Zixiang Xu</p>
  <p class="member-affil">BS @ SCU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://xzx34.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=lPLP6H8AAAAJ" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://aclanthology.org/2025.acl-long.404/">Multilinguality</a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/yanbo-wang.png" alt="Yanbo Wang" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Yanbo Wang</p>
  <p class="member-affil">BS @ SCU</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://wyf23187.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=ZEcwTysAAAAJ" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="paper-tag" href="https://arxiv.org/abs/2502.01609">Stability</a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/yougang-lyu.png" alt="Yougang Lyu" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Yougang Lyu</p>
  <p class="member-affil">PhD @ UvA</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://youganglyu.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=vh2AP8gAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  </div>
</div>

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/xueran-han.jpg" alt="Xueran Han" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Xueran Han</p>
  <p class="member-affil">PhD @ MBZUAI</p>
  <div class="member-footer">
    <a class="paper-tag" href="https://arxiv.org/abs/2502.15616">Personalization</a>
  </div>
</div>

</div>
</div>

<div class="team-section">
<h2>Alumni</h2>
<div class="team-grid">

<div class="member-card">
  <div class="member-photo">
    <img src="/images/halo/guoming-li.jpg" alt="Guoming Li" onerror="this.onerror=null;this.src='/images/halo/default-avatar.svg'">
  </div>
  <p class="member-name">Guoming Li</p>
  <div class="member-footer">
    <a class="scholar-icon" href="https://vasile-paskardlgm.github.io/" title="Website"><i class="fas fa-home"></i></a>
    <a class="scholar-icon" href="https://scholar.google.com/citations?user=MkxLbngAAAAJ&hl=zh-CN" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
  </div>
</div>

</div>
</div>
