---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is **Tianyu Zong** (宗天禹). I am a Ph.D. candidate in Computer Application Technology at the [University of Chinese Academy of Sciences (UCAS)](https://www.ucas.ac.cn/), advised by Prof. [Jungang Xu](https://people.ucas.edu.cn/~xujg), and I expect to graduate in **June 2027**. My research interests lie in **Multimodal Representation Learning, Unsupervised Contrastive Learning, World Models / 3D Vision, and Embodied AI**, with a core focus on learning robust and generalizable representations from complex multimodal data. I have published **4 first-author papers** across **ACL**, **AAAI** (including an **AAAI 2025 Oral**), and **Neural Networks**, and received the **2026 National Scholarship for Doctoral Students**. Currently, I am a Pre-training Algorithm Intern at **PsiBot (灵初智能)**, with prior industry research experience at **ShengShu Technology**, **Alibaba Amap**, and **Qiwu Technology**. I received my M.S. in Electronic Information from UCAS in 2023 and my B.Eng. in Electronic Information Engineering from North China University of Technology in 2020.


# 🔥 News
- *2026.11*: &nbsp;🚀 I joined **PsiBot (灵初智能)** as a Pre-training Algorithm Intern, working on robotic manipulation keyframe mining and multimodal temporal localization.
- *2026.10*: &nbsp;🏆 Honored to receive the **National Scholarship for Doctoral Students (博士研究生国家奖学金)**!
- *2026.10*: &nbsp;🎉🎉 My first-author journal paper **JTCSE** has been accepted by **Neural Networks**!
- *2026.09*: &nbsp;🚀 I joined **ShengShu Technology (生数科技)** as a Video Data Pipeline Intern, developing video inpainting/outpainting and quality scoring operators.
- *2026.06*: &nbsp;🏆 Honored to receive the **"Merit Student" (三好学生)** award from UCAS!
- *2026.04*: &nbsp;🎉🎉 My first-author paper **L2Dir** has been accepted by **ACL 2026 Main Conference**!
- *2026.04*: &nbsp;🎉🎉 Two co-authored papers have been accepted by **ACL 2026** (Main & Findings).
- *2025.11*: &nbsp;🎉🎉 A co-authored paper has been accepted by **AAAI 2026**.
- *2025.10*: &nbsp;🚀 I joined **Alibaba Amap** as a Research Intern, working on feed-forward relightable 3D reconstruction for world models.
- *2025.07*: &nbsp;🚀 I joined **Qiwu Technology** as an Embodied AI Intern, focusing on VLA pre-training and inference optimization.
- *2025.01*: &nbsp;🎉🎉 I am invited by **AAAI 2025** to give an **Oral** presentation in Philadelphia (Top 4.6% of submissions)! 
- *2024.12*: &nbsp;🎉🎉 My first-author paper **TNCSE** has been accepted by **AAAI 2025**.
- *2022.11*: &nbsp;🎉🎉 My first-author paper has been accepted by **AAAI 2023**. 

# 📝 Publications 

## Multimodal Representation Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Main</div><img src='images/ACL26ML.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[L2Dir: Integrating L<sub>2</sub>-Norm and Directional Alignment for Unsupervised Contrastive Representation Learning in Multimodal Retrieval](https://aclanthology.org/2026.acl-long.1604/)
[**Paper**](https://aclanthology.org/2026.acl-long.1604/) · [**Code**](https://github.com/tianyuzong/L2Dir_ACL2026)

**Tianyu Zong**, Rui Dai, Hongzhu Yi, Yuanxiang Wang, Zhenghao Zhang, Zhenyu Guan, Yujia Yang, Bingkang Shi, Yueyang Ding, Xiangxiang Chu, Kaikui Liu, Jungang Xu

*Evaluated across 95 multimodal retrieval tasks (81 MMEB-V2 + 14 M-BEIR); improves CLIP-L average Recall@10 on M-BEIR from 44.8% to 48.4% (+3.6 pts).*
</div>
</div>

## Benchmark
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Main</div><img src='images/ACL26MG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FAIRGAMER: Evaluating Social Biases in LLM-Based Video Game NPCs](https://aclanthology.org/2026.acl-long.2015/)
[**Paper**](https://aclanthology.org/2026.acl-long.2015/) · [**Code**](https://github.com/BingkangShi/FairGamer)

Bingkang Shi, Jen-tse Huang, Luo Long, **Tianyu Zong**, Hongzhu Yi, Yuanxiang Wang, Songlin Hu, Xiaodan Zhang, Zhongjiang Yao
</div>
</div>

## Time Series
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src='images/ACL26F.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLaTiSA: Towards Difficulty-Stratified Time Series Reasoning from Visual Perception to Semantics](https://aclanthology.org/2026.findings-acl.1636/)
[**Paper**](https://aclanthology.org/2026.findings-acl.1636/) · [**arXiv**](https://arxiv.org/abs/2604.17295)

Yueyang Ding, HaoPeng Zhang, Rui Dai, Yi Wang, **Tianyu Zong**, Kaikui Liu, Xiangxiang Chu
</div>
</div>

## Graph Representation
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/AAAI26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Deep Graph Learning for Incomplete Multi-View Clustering with Masked Graph Reconstruction Loss](https://ojs.aaai.org/index.php/AAAI/article/view/40091)
[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/40091)

Zhenghao Zhang, Jun Xie, Xingchen Chen, Tao Yu, Hongzhu Yi, Kaixin Xu, Yuanxiang Wang, **Tianyu Zong**, Xinming Wang, Jiahuan Chen, Guoqing Chao, Feng Chen, Zhepeng Wang, Jungang Xu
</div>
</div>

## Unsupervised Sentence Embedding
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/temp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JTCSE: Joint Tensor Modulus Constraints and Cross Attention for Unsupervised Contrastive Learning of Sentence Embeddings](https://arxiv.org/abs/2505.02366),
**Accepted by Neural Networks (CCF-B)**
[**arXiv**](https://arxiv.org/abs/2505.02366) · [**Code**](https://github.com/tianyuzong/JTCSE) · [**Model**](https://huggingface.co/UCASzty)

**Tianyu Zong**, Hongzhu Yi, Bingkang Shi, Yuanxiang Wang, Jungang Xu

*Improves average MAP@10 by +2.81 pts over SimCSE across 50 MTEB zero-shot retrieval tasks (evaluated on 140+ MTEB benchmarks).*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/aaai25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TNCSE: Tensor's Norm Constraints for Unsupervised Contrastive Learning of Sentence Embeddings](https://ojs.aaai.org/index.php/AAAI/article/view/34816), 
**Oral Paper, Top 4.63% of submissions!**
[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/34816) · [**Code**](https://github.com/tianyuzong/TNCSE) · [**Model**](https://huggingface.co/UCASzty) 

**Tianyu Zong**, Bingkang Shi, Hongzhu Yi, Jungang Xu

*Achieves 80.60 average Spearman correlation across 7 STS benchmarks (+4.35 pts over SimCSE-BERT-base) and strong zero-shot generalization across ~100 tasks.*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/aaai23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Ensemble Distillation Framework for Sentence Embeddings with Multilingual Round-Trip Translation](https://ojs.aaai.org/index.php/AAAI/article/view/26647)
[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/26647)

**Tianyu Zong**, Likun Zhang

*Achieves 79.27 average Spearman correlation across 7 STS benchmarks (+3.02 pts over SimCSE-BERT-base) with zero extra inference overhead.*
</div>
</div>

## Manuscripts Under Review
- **Delta-JEPA: Transition-Geometry Regularization for Action-Sensitive World Models** (*Co-author, Under Review*) — Introduces transition-geometry regularization reconstructing actions from latent state differences, achieving 87.42% average planning success rate across Push-T, Reacher, OGB-Cube, and Two-Room (+6.10 pts over DINO-WM).

# 📖 Educations
- *2023.09 - 2027.06 (Expected)*, Ph.D. Candidate in Computer Application Technology, University of Chinese Academy of Sciences (UCAS)
- *2020.09 - 2023.06*, M.S. in Electronic Information, University of Chinese Academy of Sciences (UCAS)
- *2016.09 - 2020.06*, B.Eng. in Electronic Information Engineering, North China University of Technology

# 🎖 Honors and Awards
- *2026.10* **National Scholarship for Doctoral Students (博士研究生国家奖学金)**
- *2026.06* "Merit Student" (三好学生), University of Chinese Academy of Sciences
- *2020 - 2025* Second-Class Academic Scholarship, UCAS (Awarded for 6 consecutive years)
- *2020.11* Freshman Scholarship, UCAS
- *2019.08* Third Prize, National Undergraduate Electronic Design Contest (Beijing Division)
- *2018.11* First Prize, 10th National Chinese Mathematics Competition (Non-Mathematics Major)
- *2018.09* Second Prize, Beijing Mathematical Contest in Modeling for College Students
- *2017 - 2018* First Prize (×2), 28th & 29th Beijing College Student Mathematics Competition
- *2017.11* Second Prize, 9th National Chinese Mathematics Competition (Non-Mathematics Major)

# 🗣 Academic Services & Activities
## Reviewer
- **Conferences**: AAAI (2025, 2026), ACL (2026)
- **Journals**: Neural Networks, Neurocomputing, Information Processing & Management

## Presentations
- *2025.02*, **Oral Presentation**, AAAI 2025, Philadelphia, USA
- *2023.03*, Poster Presentation, AAAI 2023, Washington, D.C., USA

## Teaching Assistant
- *Spring 2025*, Pattern Recognition and Machine Learning, UCAS
- *Fall 2024*, Deep Learning, UCAS
- *Spring 2024*, Deep Learning, UCAS
- *Spring 2025*, Deep Learning, Lijiang College of Culture and Tourism
- *Fall 2024*, Signal Processing, Lijiang College of Culture and Tourism

# 💬 Invited Talks
- *2025.02*, AAAI 2025 Conference (Oral)

# 💻 Internships
- *2026.11 - Present*, **Pre-training Algorithm Intern**, **PsiBot (灵初智能)**.
  - *Topic*: Robotic manipulation keyframe mining (fusing motion signals and vision into a two-stage filtering pipeline, raising candidate boundary coverage from 79.84% to 95.97% under ±3-frame tolerance) and multimodal temporal boundary localization (final boundary coverage 79.84% → 91.94%, F1 58.41% → 65.80%).
- *2026.09 - 2026.10*, **Video Data Pipeline Intern**, **ShengShu Technology (生数科技)**.
  - *Topic*: Video inpainting/outpainting data operators (GroundingDINO + SAM 2.1 subject localization/tracking, temporally smooth OpenCV masks, Python/FFmpeg augmentation; see [`video-subject-mask`](https://github.com/tianyuzong/video-subject-mask) & [`video-outpaint`](https://github.com/tianyuzong/video-outpaint)), GPT-image subject removal & background restoration, and motion, camera, and 13-dimension visual quality operators.
- *2025.10 - 2026.08*, **Research Intern**, **Alibaba Amap (阿里巴巴高德地图)**.
  - *Topic*: Feed-forward intrinsic decomposition and relightable 3DGS reconstruction on frozen Hunyuan WorldMirror (+4 dB / +3 dB PSNR on multi-illumination reconstruction and NVS; DeepSpeed ZeRO-1), Unreal Engine 5 + City Sample HDRI dataset pipeline, visual self-supervised pre-training (MoCo v3 / MAE), and InternVL3/Qwen3 multimodal data verification.
- *2025.07 - 2025.09*, **Embodied AI Intern**, **Qiwu Technology (启物科技)**.
  - *Topic*: Parallel VLA inference & real-time control (RTC) backend optimization (3× throughput), and LeRobot fine-tuning & RoboTwin evaluation across π₀, SmolVLA, ACT, and Diffusion Policy.
