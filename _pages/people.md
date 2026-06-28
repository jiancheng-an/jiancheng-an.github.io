---
layout: archive
permalink: /people/
author_profile: true
---

{% include base_path %}

<style>
  /* 团队网格容器 */
  .team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 25px;
    padding: 15px 0;
  }
  
  /* 成员卡片样式 */
  .team-card {
    background: #fff;
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  
  .team-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  
  /* 头像样式 */
  .team-avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 15px;
    border: 3px solid #f6f8fa;
  }
  
  /* 姓名与时间 */
  .team-name {
    font-size: 1.2rem;
    font-weight: bold;
    margin: 5px 0 2px 0;
  }
  
  .team-period {
    font-size: 0.85rem;
    color: #586069;
    margin-bottom: 10px;
  }
  
  /* 社交链接图标 */
  .team-links {
    margin: 10px 0;
  }
  
  .team-links a {
    margin: 0 8px;
    font-size: 1.2rem;
    color: #0366d6;
    text-decoration: none;
  }
  
  .team-links a:hover {
    color: #0056b3;
  }
  
  /* 研究方向与荣誉 */
  .team-info {
    font-size: 0.9rem;
    text-align: left;
    margin-top: 15px;
    border-top: 1px dashed #e1e4e8;
    padding-top: 10px;
  }
  
  .info-title {
    font-weight: bold;
    color: #24292e;
    margin-bottom: 2px;
  }
  
  .info-content {
    color: #24292e;
    margin-bottom: 8px;
  }
  
  .status-tag {
    display: inline-block;
    padding: 2px 8px;
    font-size: 0.75rem;
    font-weight: 600;
    border-radius: 12px;
    margin-top: 5px;
  }
  .status-current { background-color: #dcffe4; color: #155724; }
  .status-graduated { background-color: #f6f8fa; color: #6a737d; }
  
  /* 分组标题 */
  .section-title {
    margin-top: 40px;
    border-bottom: 2px solid #0366d6;
    padding-bottom: 5px;
    color: #24292e;
  }
</style>

<h2 class="section-title">Current Members</h2>
<div class="team-grid">

  <!-- Zihao Teng -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZihaoTeng.jpg" alt="Zihao Teng" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Zihao Teng</div>
    <div class="team-period">2021.09 -- Present</div>
    <span class="status-tag status-current">Ph.D. Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=9hWGhi0AAAAJ&hl=en&oi=ao" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
      <a href="https://www.linkedin.com/in/zihao-teng-b43355317/" target="_blank" title="LinkedIn"><i class="fab fa-fw fa-linkedin"></i></a>
      <a href="https://ieeexplore.ieee.org/author/37089899520" target="_blank" title="IEEE Xplore"><i class="fas fa-fw fa-book"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i> Research Interests:</div>
      <div class="info-content">Flexible Intelligent Metasurface (FIM), Integrated Sensing and Communication.</div>
      <div class="info-title"><i class="fas fa-trophy"></i> Honors:</div>
      <div class="info-content">National Scholarship (2025).</div>
    </div>
  </div>

  <!-- Hao Liu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/HaoLiu.jpg" alt="Hao Liu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Hao Liu</div>
    <div class="team-period">2021.09 -- Present</div>
    <span class="status-tag status-current">Ph.D. Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=AsNd2-EAAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
      <a href="https://www.linkedin.com/in/hao-liu-19b380317/" target="_blank" title="LinkedIn"><i class="fab fa-fw fa-linkedin"></i></a>
      <a href="https://ieeexplore.ieee.org/author/37089903215" target="_blank" title="IEEE Xplore"><i class="fas fa-fw fa-book"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i> Research Interests:</div>
      <div class="info-content">Electromagnetic Neural Network (EMNN).</div>
      <div class="info-title"><i class="fas fa-trophy"></i> Honors:</div>
      <div class="info-content">Outstanding Graduate (2021).</div>
    </div>
  </div>

  <!-- Xing Jia -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/XingJia.jpg" alt="Xing Jia" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Xing Jia</div>
    <div class="team-period">2021.09 -- Present</div>
    <span class="status-tag status-current">Ph.D. / Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=xWI9_l0AAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
      <a href="#" target="_blank" title="LinkedIn"><i class="fab fa-fw fa-linkedin"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i> Research Interests:</div>
      <div class="info-content">Stacked Intelligent Metasurface (SIM).</div>
    </div>
  </div>

  <!-- Hanwen Hu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/HanwenHu.jpg" alt="Hanwen Hu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Hanwen Hu</div>
    <div class="team-period">2021.09 -- Present</div>
    <span class="status-tag status-current">Ph.D. Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=HZb8p0gAAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
      <a href="#" target="_blank" title="LinkedIn"><i class="fab fa-fw fa-linkedin"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i> Research Interests:</div>
      <div class="info-content">Flexible Intelligent Metasurface (FIM).</div>
    </div>
  </div>
  
  <!-- Haoxian Niu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZihaoTeng.jpg" alt="Haoxian Niu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Haoxian Niu</div>
    <div class="team-period">2024.09 -- Present</div>
    <span class="status-tag status-current">Ph.D. / Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=LbGlo44AAAAJ&hl=en&oi=ao" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i> Research Interests:</div>
      <div class="info-content">Electromagnetic-Domain Signal Processing.</div>
    </div>
  </div>

</div>

<h2 class="section-title">Alumni</h2>
<div class="team-grid">

  <!-- Shining Lin -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZihaoTeng.jpg" alt="Shining Lin" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Shining Lin</div>
    <div class="team-period">2022.09 -- 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=_9PqpBEAAAAJ&hl=en&oi=ao" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-briefcase"></i> Destination:</div>
      <div class="info-content">Huawei Technologies Co., Ltd.</div>
    </div>
  </div>

  <!-- Guojun Huang -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZihaoTeng.jpg" alt="Guojun Huang" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Guojun Huang</div>
    <div class="team-period">2022.09 -- 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=1uiQEvEAAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
    </div>
  </div>

  <!-- Xianghao Yao -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZihaoTeng.jpg" alt="Xianghao Yao" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Xianghao Yao</div>
    <div class="team-period">2022.09 -- 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=hq6wxXsAAAAJ&hl=en&oi=ao" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
    </div>
  </div>

  <!-- Zhiheng Yu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZihaoTeng.jpg" alt="Zhiheng Yu">
    <div class="team-name">Zhiheng Yu</div>
    <div class="team-period">2022.09 -- 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <!-- No link provided -->
    </div>
  </div>

  <!-- Wangyang Xu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZihaoTeng.jpg" alt="Wangyang Xu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Wangyang Xu</div>
    <div class="team-period">2019.09 -- 2023.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=Nug8x1UAAAAJ&hl=en&oi=ao" target="_blank" title="Google Scholar"><i class="fas fa-fw fa-graduation-cap"></i></a>
    </div>
  </div>

</div>
