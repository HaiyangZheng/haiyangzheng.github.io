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

/* --- 新的折叠按钮样式 (JS版) --- */
.gallery-trigger {
    display: block;
    width: 100%;
    cursor: pointer;
    color: #000000; /* 默认黑色 */
    font-size: 0.9em;
    font-weight: 600;
    padding: 10px 0;
    margin: 5px 0;
    
    /* 移动端防误触优化 */
    touch-action: manipulation; 
    -webkit-tap-highlight-color: transparent;
    user-select: none;
    -webkit-user-select: none;
    
    transition: color 0.2s;
}

.gallery-trigger:hover {
    color: #b71c1c; /* 悬停变红 */
    text-decoration: underline;
}

/* 隐藏相册容器 */
#fsae-gallery {
    display: none; /* 默认隐藏 */
    /* 其它样式保持 flex 布局 */
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 10px;
    padding: 10px;
    background: #f1f1f1;
    border-radius: 8px;
}

/* 🔥 关键修改：当有 .show 这个类时，强制显示为 flex */
#fsae-gallery.show {
    display: flex !important;
}

/* 图片样式保持不变 */
.gallery-container img {
    height: 120px; 
    width: auto;
    border-radius: 4px;
    object-fit: cover;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    background: #ddd; 
    transition: transform 0.2s;
}
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

* **Conference Reviewer:** NeurIPS, CVPR, ICML, ACM MM, ECCV

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

            <div class="gallery-trigger" role="button" onclick="toggleGallery(event)">
                ▶️ Click to View Gallery
            </div>
            
            <div id="fsae-gallery" class="gallery-container">
                <img src="/images/hrt1.png" alt="Design Defense" title="Design Defense Presentation" loading="lazy">
                <img src="/images/hrt2.jpg" alt="Team Photo" title="Team Group Photo" loading="lazy">
                <img src="/images/hrt3.jpg" alt="Skidpad Event" title="Preparing for Skidpad Event" loading="lazy">
                <img src="/images/hrt4.jpg" alt="Debugging" title="Vehicle Debugging & Testing" loading="lazy">
                
                <p style="width: 100%; margin: 5px 0 0 0; font-size: 0.85em; color: #666;">
                    * Snapshots from the 2019 National Competition season.
                </p>
            </div>

            <script>
                function toggleGallery(event) {
                    // 🔥 核心修复：阻止浏览器的默认导航或缩放行为
                    if (event) {
                        event.preventDefault();
                        event.stopPropagation();
                    }

                    var gallery = document.getElementById("fsae-gallery");
                    
                    // 使用 classList.toggle 来切换，比直接操作 style 更稳健
                    gallery.classList.toggle("show");
                }
            </script>

        </div> </div> </div> 