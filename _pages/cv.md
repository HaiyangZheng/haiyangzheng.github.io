---
layout: default
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
/* --- 基础列表样式 --- */
ul.cv-list {
    list-style-type: none;
    padding-left: 10px;
}
ul.cv-list li {
    margin-bottom: 15px;
    border-left: 3px solid #eee;
    padding-left: 15px;
}
ul.cv-list li strong {
    color: #333;
    font-size: 1.05em;
}
.cv-date {
    float: right;
    color: #666;
    font-size: 0.9em;
    font-style: italic;
}

/* --- 卡片样式 --- */
.cv-item {
    display: flex;
    flex-wrap: wrap;
    margin-bottom: 30px;
    background-color: #fafafa;
    border-radius: 8px;
    padding: 15px;
    border: 1px solid #eee;
}
.cv-img {
    flex: 0 0 150px;
    margin-right: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.cv-img img {
    width: 100%;
    border-radius: 6px;
    object-fit: cover;
}
.cv-content {
    flex: 1;
}
.cv-title {
    font-size: 1.1em;
    font-weight: bold;
    color: #000;
    margin-bottom: 5px;
}
.cv-subtitle {
    color: #555;
    font-size: 0.95em;
    margin-bottom: 8px;
    font-style: italic;
}
.cv-desc {
    font-size: 0.9em;
    color: #444;
    line-height: 1.5;
}

/* 手机端适配 */
@media (max-width: 600px) {
    .cv-item { display: block; }
    .cv-img { margin-bottom: 10px; width: 100%; }
    .cv-date { float: none; display: block; margin-bottom: 5px;}
}

/* --- 折叠相册样式 --- */

details {
    /* 确保 details 本身没有奇怪的布局影响 */
    display: block;
    margin-top: 10px;
}

details > summary {
    display: block;
    width: 100%;
    position: relative;
    z-index: 10;
    
    cursor: pointer;
    color: #000000;
    font-size: 0.9em;
    font-weight: 600;
    
    padding: 10px 0;
    margin: 5px 0;
    
    /* 🔥 新增：优化移动端触摸体验 */
    touch-action: manipulation;       /* 告诉浏览器只允许点击和滚动，禁止双击缩放 */
    -webkit-tap-highlight-color: transparent; /* 去掉点击时那个灰色的背景块 */
    
    /* 之前的禁止选中保持不变，但在移动端 touch-action 优先级更高 */
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    
    outline: none;
    transition: color 0.2s;
}

/* 隐藏默认箭头 */
details > summary::-webkit-details-marker {
    display: none;
}
details > summary::marker {
    display: none; /* 针对较新浏览器的标准写法 */
    content: "";
}

details > summary:hover {
    color: #b71c1c;
    text-decoration: underline;
}

details > summary:focus {
    outline: none;
}

/* 相册容器 */
.gallery-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 10px;
    padding: 10px;
    background: #f1f1f1;
    border-radius: 8px;
}

/* 图片统一高度 */
.gallery-container img {
    height: 120px; /* 统一高度，像胶卷一样排列 */
    width: auto;
    border-radius: 4px;
    object-fit: cover;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    background: #ddd; /* 加载前的占位色 */
    transition: transform 0.2s;
}

/* 图片悬停放大效果 */
.gallery-container img:hover {
    transform: scale(1.05);
    z-index: 10;
}
</style>

# 🎓 Curriculum Vitae

<div style="margin-bottom: 20px;"></div>

Here is a comprehensive overview of my academic and professional background.  
👉 **[Full CV (PDF)](/assets/files/cv.pdf)**

---

## 🏫 Education

<ul class="cv-list">
    <li>
        <span class="cv-date">2024 - Present</span>
        <strong>University of Trento</strong><br>
        PhD Student in Computer Science<br>
        <small>Advisors: Prof. Nicu Sebe & Prof. Zhun Zhong</small>
    </li>
    <li>
        <span class="cv-date">2021 - 2024</span>
        <strong>Harbin Institute of Technology, Shenzhen</strong><br>
        M.S. in Computer Technology<br>
        <small>Advisor: Prof. Hongpeng Wang</small>
    </li>
    <li>
        <span class="cv-date">2017 - 2021</span>
        <strong>Harbin Institute of Technology, Weihai</strong><br>
        B.E. in Vehicle Engineering
    </li>
</ul>

---

## 🏆 Honors & Awards

* **AAAI-26 Student Scholarship**, AAAI 2026.
* **Scholar Award**, NeurIPS 2024.
* **Outstanding Reviewer**, ACM Multimedia 2024.

---

## 🌟 Academic Service

* **Conference Reviewer:**
    * Neural Information Processing Systems (**NeurIPS**)
    * IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**)
    * International Conference on Machine Learning (**ICML**)
    * ACM International Conference on Multimedia (**ACM MM**)
    * European Conference on Computer Vision (**ECCV**)

---

## 💼 Experience

<div class="cv-item">
    <div class="cv-img" style="flex: 0 0 80px;">
        <img src="/images/konka_logo.png" alt="Konka" style="width: 80px; height: auto;">
    </div>
    <div class="cv-content">
        <div class="cv-title">Konka Group (AIoT Department) <span class="cv-date">Dec. 2021 - Jun. 2022</span></div>
        <div class="cv-subtitle">Algorithm Intern</div>
        <div class="cv-desc">
            <ul>
                <li>Responsible for the development and optimization of <strong>Speaker Recognition</strong> models.</li>
                <li>Conducted experiments on large-scale audio datasets and deployed models on edge devices.</li>
            </ul>
        </div>
    </div>
</div>

---

## 🏎️ Selected Projects & Activities

<div class="cv-item">
    <div class="cv-img">
        <img src="/images/hrt_logo.png" alt="FSAE Racing">
    </div>
    <div class="cv-content">
        <div class="cv-title">Formula Student China (FSAE)</div>
        <div class="cv-subtitle">Team Member / Engineer | Harbin Institute of Technology, Weihai</div>
        <div class="cv-desc">
            During my undergraduate studies in Vehicle Engineering, I participated in the <strong>Formula Student China</strong> competition.
            <ul>
                <li>Designed and implemented the Electronic Control Unit and Data Acquisition System for the racing car.</li>
                <li>Collaborated with a multidisciplinary team to design and build a race car from scratch for a national competition.</li>
                <li>This experience honed my engineering intuition and teamwork skills under high pressure.</li>
            </ul>

            <details>
                <summary onclick="">▶️ Click to View Gallery</summary>
                
                <div class="gallery-container">
                    <img src="/images/hrt1.png" alt="Design Defense" title="Design Defense Presentation">
                    <img src="/images/hrt2.jpg" alt="Team Photo" title="Team Group Photo">
                    <img src="/images/hrt3.jpg" alt="Skidpad Event" title="Preparing for Skidpad (Figure-8) Event">
                    <img src="/images/hrt4.jpg" alt="Debugging" title="Vehicle Debugging & Testing">
                    
                    <p style="width: 100%; margin: 5px 0 0 0; font-size: 0.85em; color: #666;">
                        * Snapshots from the 2019 National Competition season.
                    </p>
                </div>
            </details>
            
        </div>
    </div>
</div>