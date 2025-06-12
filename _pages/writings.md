---
layout: page
title: writings & talks
permalink: /writings/
description: Tech articles and presentations I've shared.
nav: true
nav_order: 4
---

<div class="writings-content">

<div class="section-container">
  <h2 class="section-title">
    <i class="fa-solid fa-newspaper"></i>
    Tech Articles
  </h2>
  <p class="section-description">Tech blogs by me</p>
  
  <div class="articles-grid">
    
    <div class="article-item">
      <div class="article-icon">
        <i class="fa-brands fa-weixin"></i>
      </div>
      <div class="article-content">
        <h3><a href="https://mp.weixin.qq.com/s/GRGlDqUvBX3DWIF1jXdviA" target="_blank">“AI玩手机”原理揭秘：大模型驱动的移动端GUI智能体</a></h3>
        <p class="article-meta">
          <span class="platform">澜舟科技</span>
          <span class="date">2024年11月</span>
        </p>
        <p class="article-description">移动端GUI智能体的解析和探讨</p>
      </div>
    </div>

    <!-- Add more articles as needed -->
    
  </div>
</div>

<div class="section-container">
  <h2 class="section-title">
    <i class="fa-solid fa-presentation-screen"></i>
    Presentations & Talks
  </h2>
  <p class="section-description">Presentations and talks by me.</p>
  
  <div class="presentations-grid">
    
    <div class="presentation-item">
      <div class="presentation-icon">
        <i class="fa-solid fa-file-pdf"></i>
      </div>
      <div class="presentation-content">
        <h3><a href="/assets/pdf/nexus_talk_may.pdf" target="_blank">OS智能体原子任务到复合任务的能力泛化研究与系统调度方法</a></h3>
        <p class="presentation-meta">
          <span class="date">2025.05</span>
        </p>
        <p class="presentation-description">Shared our latest work and findings on compositional device-using tasks.</p>
      </div>
    </div>

    <div class="presentation-item">
      <div class="presentation-icon">
        <i class="fa-solid fa-file-pdf"></i>
      </div>
      <div class="presentation-content">
        <h3><a href="/assets/pdf/澜舟大模型沙龙_郭源_v3_share.pdf" target="_blank">大模型智能体技术科普</a></h3>
        <p class="presentation-meta">
          <span class="venue">Salon in Langboat Tech</span>
          <span class="date">2025.03</span>
        </p>
        <p class="presentation-description">I hosted a tech salon in Langboat technology sharing LLM agent technology.</p>
      </div>
    </div>

    <!-- Add more presentations as needed -->
    
  </div>
</div>

</div>

<style>
.writings-content {
  max-width: 900px;
  margin: 0 auto;
  padding: 2rem 0;
}

.section-container {
  margin-bottom: 4rem;
}

.section-title {
  color: #333;
  font-size: 2rem;
  font-weight: 600;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.section-title i {
  color: #007bff;
  font-size: 1.8rem;
}

.section-description {
  color: #666;
  font-size: 1.1rem;
  margin-bottom: 2.5rem;
  padding-left: 2.5rem;
}

.articles-grid, .presentations-grid {
  display: grid;
  gap: 1.5rem;
}

.article-item, .presentation-item {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  padding: 1.5rem;
  background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
  border-radius: 12px;
  border-left: 4px solid #007bff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: all 0.3s ease;
}

.article-item:hover, .presentation-item:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.12);
  background: linear-gradient(135deg, #f0f8ff 0%, #ffffff 100%);
}

.article-icon, .presentation-icon {
  flex-shrink: 0;
  width: 50px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
  border-radius: 10px;
  color: white;
  font-size: 1.4rem;
}

.article-content, .presentation-content {
  flex: 1;
}

.article-content h3, .presentation-content h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.3rem;
  font-weight: 600;
}

.article-content h3 a, .presentation-content h3 a {
  color: #333;
  text-decoration: none;
  transition: color 0.3s ease;
}

.article-content h3 a:hover, .presentation-content h3 a:hover {
  color: #007bff;
}

.article-meta, .presentation-meta {
  display: flex;
  gap: 1rem;
  margin-bottom: 0.75rem;
}

.platform, .venue, .date {
  background: #e3f2fd;
  color: #1565c0;
  padding: 0.25rem 0.75rem;
  border-radius: 15px;
  font-size: 0.85rem;
  font-weight: 500;
}

.date {
  background: #f3e5f5;
  color: #7b1fa2;
}

.article-description, .presentation-description {
  color: #555;
  line-height: 1.6;
  margin: 0;
}

/* Responsive design */
@media (max-width: 768px) {
  .writings-content {
    padding: 1rem;
  }
  
  .section-title {
    font-size: 1.6rem;
  }
  
  .article-item, .presentation-item {
    flex-direction: column;
    text-align: center;
  }
  
  .article-icon, .presentation-icon {
    align-self: center;
  }
  
  .article-meta, .presentation-meta {
    justify-content: center;
    flex-wrap: wrap;
  }
}

/* External link icon */
.article-content a[href^="http"]:after,
.presentation-content a[href^="http"]:after {
  content: " \f35d";
  font-family: "Font Awesome 6 Free";
  font-weight: 900;
  font-size: 0.8rem;
  color: #666;
  margin-left: 0.3rem;
}

.presentation-content a[href$=".pdf"]:after {
  content: " \f1c1";
  font-family: "Font Awesome 6 Free";
  font-weight: 900;
  font-size: 0.8rem;
  color: #dc3545;
  margin-left: 0.3rem;
}
</style> 
