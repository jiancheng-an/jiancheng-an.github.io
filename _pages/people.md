---
layout: archive
permalink: /people/
author_profile: true
---

{% include base_path %}

<style>
  /* ===== 团队网格 ===== */
  .team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 22px;
    padding: 10px 0;
  }

  /* ===== 成员卡片 ===== */
  .team-card {
    background: #fff;
    border: 1px solid #e5e7eb;
    border-radius: 12px;
    padding: 22px 18px 18px;
    text-align: center;
    box-shadow: 0 1px 3px rgba(0,0,0,0.04);
    transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  }
  .team-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    border-color: #c7d2fe;
  }

  /* ===== 头像 ===== */
  .team-avatar {
    width: 110px;
    height: 110px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 12px;
    border: 3px solid #f1f5f9;
    background: #f8fafc;
  }

  /* ===== 姓名与时间 ===== */
  .team-name {
    font-size: 1.15rem;
    font-weight: 700;
    color: #111827;
    margin: 4px 0 2px;
  }
  .team-period {
    font-size: 0.82rem;
    color: #6b7280;
    margin-bottom: 8px;
    font-variant-numeric: tabular-nums;
  }

  /* ===== 身份标签 ===== */
  .status-tag {
    display: inline-block;
    padding: 2px 10px;
    font-size: 0.72rem;
    font-weight: 600;
    border-radius: 999px;
    letter-spacing: 0.02em;
    margin-bottom: 10px;
  }
  .status-phd      { background: #eef2ff; color: #4338ca; }
  .status-master   { background: #ecfdf5; color: #047857; }
  .status-graduated{ background: #f3f4f6; color: #6b7280; }
  .status-postdoc  { background: #fff7ed; color: #c2410c; }

  /* ===== 社交链接 ===== */
  .team-links {
    margin: 8px 0 12px;
  }
  .team-links a {
    display: inline-block;
    margin: 0 5px;
    font-size: 1.05rem;
    color: #4f46e5;
    text-decoration: none;
    transition: color 0.15s ease;
  }
  .team-links a:hover { color: #312e81; }
  .team-links a.disabled { color: #d1d5db; pointer-events: none; }

  /* ===== 信息区 ===== */
  .team-info {
    font-size: 0.85rem;
    text-align: left;
    margin-top: 12px;
    border-top: 1px dashed #e5e7eb;
    padding-top: 10px;
    line-height: 1.5;
  }
  .info-title {
    font-weight: 600;
    color: #374151;
    margin-bottom: 2px;
  }
  .info-title i { color: #9ca3af; margin-right: 4px; }
  .info-content {
    color: #4b5563;
    margin-bottom: 8px;
  }

  /* ===== 分组标题 ===== */
  .section-title {
    margin: 36px 0 14px;
    padding-bottom: 6px;
    border-bottom: 2px solid #4f46e5;
    color: #111827;
    font-size: 1.25rem;
    font-weight: 700;
  }
  .section-title:first-of-type { margin-top: 12px; }
</style>

<h2 class="section-title">Current Members</h2>
<div class="team-grid">

  <!-- ====== 复制这一段来添加新成员 ====== -->
  <div class="team-card">
    <img class="team-avatar"
         src="{{ base_path }}/images/people/ZihaoTeng.jpg"
         alt="Zihao Teng"
         onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Zihao Teng</div>
    <div class="team-period">2021.09 – Present</div>
    <span class="status-tag status-phd">Ph.D. Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=9hWGhi0AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
      <a href="https://www.linkedin.com/in/zihao-teng-b43355317/" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
      <a href="https://ieeexplore.ieee.org/author/37089899520" target="_blank" title="IEEE Xplore"><i class="fas fa-book"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Flexible Intelligent Metasurface (FIM), Integrated Sensing and Communication.</div>
      <div class="info-title"><i class="fas fa-trophy"></i>Honors</div>
      <div class="info-content">National Scholarship (2025).</div>
    </div>
  </div>
  <!-- ====== 复制结束 ====== -->

  <!-- Hao Liu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/HaoLiu.jpg" alt="Hao Liu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Hao Liu</div>
    <div class="team-period">2021.09 – Present</div>
    <span class="status-tag status-phd">Ph.D. Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=AsNd2-EAAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
      <a href="https://www.linkedin.com/in/hao-liu-19b380317/" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
      <a href="https://ieeexplore.ieee.org/author/37089903215" target="_blank" title="IEEE Xplore"><i class="fas fa-book"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Electromagnetic Neural Network (EMNN).</div>
      <div class="info-title"><i class="fas fa-trophy"></i>Honors</div>
      <div class="info-content">Outstanding Graduate (2021).</div>
    </div>
  </div>

  <!-- Xing Jia -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/XingJia.jpg" alt="Xing Jia" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Xing Jia</div>
    <div class="team-period">2021.09 – Present</div>
    <span class="status-tag status-phd">Ph.D. Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=xWI9_l0AAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
      <a href="#" class="disabled" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Stacked Intelligent Metasurface (SIM).</div>
    </div>
  </div>

  <!-- Hanwen Hu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/HanwenHu.jpg" alt="Hanwen Hu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Hanwen Hu</div>
    <div class="team-period">2023.09 – Present</div>
    <span class="status-tag status-phd">Ph.D. Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=HZb8p0gAAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
      <a href="#" class="disabled" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Flexible Intelligent Metasurface (FIM).</div>
    </div>
  </div>

  <!-- Haoxian Niu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/HaoxianNiu.jpg" alt="Haoxian Niu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Haoxian Niu</div>
    <div class="team-period">2024.09 – Present</div>
    <span class="status-tag status-master">Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=LbGlo44AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Electromagnetic-Domain Signal Processing.</div>
    </div>
  </div>

  <!-- Jinbao Li -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/JinbaoLi.jpg" alt="Jinbao Li" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Jinbao Li</div>
    <div class="team-period">2024.09 – Present</div>
    <span class="status-tag status-master">Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=LbGlo44AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Electromagnetic Neural Network (EMNN).</div>
    </div>
  </div>

  <!-- Xiangyu Ding -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/XiangyuDing.jpg" alt="Xiangyu Ding" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Xiangyu Ding</div>
    <div class="team-period">2024.09 – Present</div>
    <span class="status-tag status-master">Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=LbGlo44AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Electromagnetic Neural Network (EMNN).</div>
    </div>
  </div>

  <!-- Haoyu Wang -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/HaoyuWang.jpg" alt="Haoyu Wang" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Haoyu Wang</div>
    <div class="team-period">2025.09 – Present</div>
    <span class="status-tag status-master">Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=LbGlo44AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Flexible Intelligent Metasurface (FIM).</div>
    </div>
  </div>

  <!-- Minyi Sun -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/MinyiSun.jpg" alt="Minyi Sun" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Minyi Sun</div>
    <div class="team-period">2025.09 – Present</div>
    <span class="status-tag status-master">Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=LbGlo44AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Electromagnetic-Domain Signal Processing.</div>
    </div>
  </div>

  <!-- Zidong Ma -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZidongMa.jpg" alt="Zidong Ma" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Zidong Ma</div>
    <div class="team-period">2025.09 – Present</div>
    <span class="status-tag status-master">Master Student</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=LbGlo44AAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Electromagnetic-Domain Signal Processing.</div>
    </div>
  </div>

  <!-- Yujia Li -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/YujiaLi.jpg" alt="Yujia Li" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Yujia Li</div>
    <div class="team-period">2026.09 – Present</div>
    <span class="status-tag status-master">Master Student</span>
    <div class="team-links">
      <a href="#" class="disabled" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
      <a href="#" class="disabled" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
      <a href="#" class="disabled" title="IEEE Xplore"><i class="fas fa-book"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-search"></i>Research Interests</div>
      <div class="info-content">Electromagnetic-Domain Signal Processing.</div>
    </div>
  </div>

</div>

<h2 class="section-title">Alumni</h2>
<div class="team-grid">

  <!-- Aole Ming -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/AoleMing.jpg" alt="Aole Ming" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Aole Ming</div>
    <div class="team-period">2023.09 – 2026.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=_9PqpBEAAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-briefcase"></i>Destination</div>
      <div class="info-content">Huawei Technologies Co., Ltd.</div>
    </div>
  </div>

  <!-- Jinyue Jiang -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/JinyueJiang.jpg" alt="Jinyue Jiang" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Jinyue Jiang</div>
    <div class="team-period">2023.09 – 2026.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=_9PqpBEAAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-briefcase"></i>Destination</div>
      <div class="info-content">Huawei Technologies Co., Ltd.</div>
    </div>
  </div>

  <!-- Shining Lin -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ShiningLin.jpg" alt="Shining Lin" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Shining Lin</div>
    <div class="team-period">2022.09 – 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=_9PqpBEAAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
    <div class="team-info">
      <div class="info-title"><i class="fas fa-briefcase"></i>Destination</div>
      <div class="info-content">Huawei Technologies Co., Ltd.</div>
    </div>
  </div>

  <!-- Guojun Huang -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/GuojunHuang.jpg" alt="Guojun Huang" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Guojun Huang</div>
    <div class="team-period">2022.09 – 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?hl=en&user=1uiQEvEAAAAJ" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
  </div>

  <!-- Xianghao Yao -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/XianghaoYao.jpg" alt="Xianghao Yao" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Xianghao Yao</div>
    <div class="team-period">2022.09 – 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <a href="https://scholar.google.com/citations?user=hq6wxXsAAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
    </div>
  </div>

  <!-- Zhiheng Yu -->
  <div class="team-card">
    <img class="team-avatar" src="{{ base_path }}/images/people/ZhihengYu.jpg" alt="Zhiheng Yu" onerror="this.src='{{ base_path }}/images/people/default.png'">
    <div class="team-name">Zhiheng Yu</div>
    <div class="team-period">2022.09 – 2025.06</div>
    <span class="status-tag status-graduated">Graduated</span>
    <div class="team-links">
      <!-- 无链接 -->
    </div>
  </div>

</div>
