---
layout: default
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
/* 容器：使用 Flex 布局，让图片和文字并排 */
.pub-item {
    display: flex;
    flex-wrap: wrap; /* 手机端自动换行 */
    align-items: flex-start;
    margin-bottom: 40px; /* 每篇论文之间的间距 */
    border-bottom: 1px solid #eee; /* 可选：加个底部分割线 */
    padding-bottom: 20px;
}

/* 左侧图片区域 */
.pub-img {
    flex: 0 0 30%; /* 图片占 30% 宽度 */
    max-width: 250px; /* 限制最大宽度 */
    margin-right: 25px;
}

.pub-img img {
    width: 100%;
    border-radius: 8px; /* 圆角 */
    box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* 阴影效果，更有质感 */
    transition: transform 0.3s;
}

.pub-img img:hover {
    transform: scale(1.02); /* 鼠标悬停微微放大 */
}

/* 右侧文字区域 */
.pub-content {
    flex: 1; /* 占满剩余空间 */
}

/* 标题样式 */
.pub-title {
    font-size: 1.25em;
    font-weight: bold;
    color: #3670C9; /* 从蓝色 (#1a0dab) 改为 深黑灰色，表示不可点击 */
    display: block;
    margin-bottom: 8px;
    line-height: 1.3;
}

.pub-title:hover {
    text-decoration: underline;
}

/* 作者样式 */
.pub-authors {
    color: #444;
    margin-bottom: 5px;
    font-size: 0.95em;
    line-height: 1.4;
}

/* 会议样式 */
.pub-venue {
    font-style: italic;
    color: #666;
    margin-bottom: 8px;
}

/* 链接样式 */
.pub-links a {
    display: inline-block;
    margin-right: 12px;
    color: #5683c7ff; /* 红色链接，比较显眼 */
    font-size: 0.9em;
    font-weight: 600;
    text-transform: uppercase; /* 全大写 */
    text-decoration: none;
}

.pub-links a:hover {
    background-color: #fce8e6;
    border-radius: 3px;
}

/* 简介样式 */
.pub-desc {
    margin-top: 10px;
    font-size: 0.95em;
    color: #333;
    font-weight: 500; /*稍微加粗*/
}

/* 手机端适配：屏幕小于768px时，图片变大并换行 */
@media (max-width: 768px) {
    .pub-img {
        flex: 0 0 100%;
        max-width: 100%;
        margin-right: 0;
        margin-bottom: 15px;
    }
}
</style>

# 📝 Publications

<div style="margin-bottom: 30px;"></div>

<div class="pub-item">
    <div class="pub-img">
        <img src="/images/pubs/cvpr26_eagc.png" alt="CVPR 2026 Paper">
    </div>
    <div class="pub-content">
        <div class="pub-title">The Devil Is in Gradient Entanglement: Energy-Aware Gradient Coordinator for Robust Generalized Category Discovery</div>
        <div class="pub-authors">
            <strong>Haiyang Zheng</strong>, Nan Pu, Yaqi Cai, Teng Long, Wenjing Li, Nicu Sebe, Zhun Zhong.
        </div>
        <div class="pub-venue">
            IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026.
        </div>
        <div class="pub-links">
            <a href="#">[Paper]</a>
            <a href="https://haiyangzheng.github.io/EAGC/">[Code]</a>
        </div>
        <div class="pub-desc">
            A plug-and-play gradient-level module that mitigates gradient entanglement and improves robust generalized category discovery.
        </div>
    </div>
</div>

<div class="pub-item">
    <div class="pub-img">
        <img src="/images/pubs/aaai26_cal.png" alt="ICMR 2023 Paper">
    </div>
    <div class="pub-content">
        <div class="pub-title">Open-World Deepfake Attribution via Confidence-Aware Asymmetric Learning</div>
        <div class="pub-authors">
            <strong>Haiyang Zheng</strong>, Nan Pu, Wenjing Li, Teng Long, Nicu Sebe, Zhun Zhong.
        </div>
        <div class="pub-venue">
            AAAI Conference on Artificial Intelligence (AAAI), 2026.
        </div>
        <div class="pub-links">
            <a href="https://arxiv.org/abs/2512.12667">[Paper]</a>
            <a href="https://github.com/HaiyangZheng/OWDFA-CAL">[Code]</a>
        </div>
        <div class="pub-desc">
            Mitigating confidence skew and automatically estimating novel forgery types for robust open-world DeepFake attribution.
        </div>
    </div>
</div>

<div class="pub-item">
    <div class="pub-img">
        <img src="/images/pubs/iccv25_diffgre.png" alt="ICMR 2023 Paper">
    </div>
    <div class="pub-content">
        <div class="pub-title">Generate, Refine, and Encode: Leveraging Synthesized Novel Samples for On-the-Fly Fine-Grained Category Discovery</div>
        <div class="pub-authors">
            Xiao Liu, Nan Pu, <strong>Haiyang Zheng</strong>, Wenjing Li, Nicu Sebe, Zhun Zhong.
        </div>
        <div class="pub-venue">
            International Conference on Computer Vision (ICCV), 2025.
        </div>
        <div class="pub-links">
            <a href="https://arxiv.org/abs/2507.04051">[Paper]</a>
            <a href="https://github.com/XLiu443/DiffGRE">[Code]</a>
        </div>
        <div class="pub-desc">
            A diffusion-based framework that synthesizes and refines novel samples to enhance on-the-fly fine-grained category discovery.
        </div>
    </div>
</div>

<div class="pub-item">
    <div class="pub-img">
        <img src="/images/pubs/neurips24_hash.png" alt="Neurips 2024 Paper">
    </div>
    <div class="pub-content">
        <div class="pub-title">Prototypical Hash Encoding for On-the-Fly Fine-Grained Category Discovery</div>
        <div class="pub-authors">
            <strong>Haiyang Zheng</strong>, Nan Pu, Wenjing Li, Nicu Sebe, and Zhun Zhong.
        </div>
        <div class="pub-venue">
            Neural Information Processing Systems (NeurIPS), 2024.
        </div>
        <div class="pub-links">
            <a href="https://arxiv.org/abs/2410.19213">[Paper]</a>
            <a href="https://github.com/HaiyangZheng/PHE">[Code]</a>
        </div>
        <div class="pub-desc">
            We propose a prototypical hash encoding method to discover fine-grained categories in real-time streams.
        </div>
    </div>
</div>

<div class="pub-item">
    <div class="pub-img">
        <img src="/images/pubs/eccv24_textual.png" alt="ECCV 2024 Paper">
    </div>
    <div class="pub-content">
        <div class="pub-title">Textual Knowledge Matters: Cross-Modality Co-Teaching for Generalized Visual Class Discovery</div>
        <div class="pub-authors">
            <strong>Haiyang Zheng</strong>, Nan Pu, Wenjing Li, Nicu Sebe, and Zhun Zhong.
        </div>
        <div class="pub-venue">
            European Conference on Computer Vision (ECCV), 2024.
        </div>
        <div class="pub-links">
            <a href="https://arxiv.org/abs/2403.07369">[Paper]</a>
            <a href="https://github.com/HaiyangZheng/TextGCD">[Code]</a>
        </div>
        <div class="pub-desc">
            Leveraging textual knowledge to guide visual discovery in generalized settings using a co-teaching framework.
        </div>
    </div>
</div>

<div class="pub-item">
    <div class="pub-img">
        <img src="/images/pubs/icmr24_density.png" alt="ICMR 2024 Paper">
    </div>
    <div class="pub-content">
        <div class="pub-title">Deep Image Clustering Based on Curriculum Learning and Density Information</div>
        <div class="pub-authors">
            <strong>Haiyang Zheng</strong>, Ruilin Zhang, Hongpeng Wang.
        </div>
        <div class="pub-venue">
            ACM International Conference on Multimedia Retrieval (ICMR), 2024.
        </div>
        <div class="pub-links">
            <a href="https://dl.acm.org/doi/abs/10.1145/3652583.3658081">[Paper]</a>
        </div>
        <div class="pub-desc">
            Combining curriculum learning strategies with density peaks to improve deep clustering performance.
        </div>
    </div>
</div>

<div class="pub-item">
    <div class="pub-img">
        <img src="/images/pubs/icmr23_tdec.png" alt="ICMR 2023 Paper">
    </div>
    <div class="pub-content">
        <div class="pub-title">TDEC: Deep Embedded Image Clustering with Transformer and Distribution Information</div>
        <div class="pub-authors">
            Ruilin Zhang, <strong>Haiyang Zheng</strong>, Hongpeng Wang.
        </div>
        <div class="pub-venue">
            ACM International Conference on Multimedia Retrieval (ICMR), 2023.
        </div>
        <div class="pub-links">
            <a href="https://dl.acm.org/doi/abs/10.1145/3591106.3592268">[Paper]</a>
        </div>
        <div class="pub-desc">
            A novel Transformer-based framework for deep embedded clustering that exploits distribution information.
        </div>
    </div>
</div>
