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

> 📢 **I am actively seeking Postdoctoral positions in the United States or Canada (available starting in 2027).** 
> If your lab is working on Multimodal AI, World Models, Embodied AI, or 3D Vision, I would love to connect! Please feel free to reach out to me at [zongtianyu20@mails.ucas.ac.cn](mailto:zongtianyu20@mails.ucas.ac.cn).

My name is **Tianyu Zong** (宗天禹). I am a Ph.D. student in Computer Application Technology at the [University of Chinese Academy of Sciences (UCAS)](https://www.ucas.ac.cn/), advised by Prof. [Jungang Xu](https://people.ucas.edu.cn/~xujg), and I expect to graduate in 2027. My research interests lie in **Multimodal Representation Learning, World Models, and Embodied AI**, with a core focus on learning robust and generalizable representations from complex multimodal data. I received my Master's degree in Electronic Information from UCAS in 2023 and my Bachelor's degree in Electronic Information Engineering from North China University of Technology in 2020.


# 🔥 News
- *2026.04*: &nbsp;🎉🎉 My first-author paper **L2Dir** has been accepted by **ACL 2026 Main Conference**!
- *2026.04*: &nbsp;🎉🎉 Two co-authored papers have been accepted by **ACL 2026** (Main & Findings).
- *2025.11*: &nbsp;🎉🎉 A co-authored paper has been accepted by **AAAI 2026**.
- *2025.10*: &nbsp;🚀 I joined **Alibaba Amap** as a Research Intern, working on feed-forward relighting 3D reconstruction for world models.
- *2025.07*: &nbsp;🚀 I joined **Qiwu Technology** as an Embodied AI Intern, focusing on VLA pre-training.
- *2025.01*: &nbsp;🎉🎉 I am invited by **AAAI 2025** to give an **Oral** presentation in Philadelphia (Top 4.6% of submissions)! 
- *2024.12*: &nbsp;🎉🎉 My first-author paper **TNCSE** has been accepted by **AAAI 2025**.
- *2022.11*: &nbsp;🎉🎉 My first-author paper has been accepted by **AAAI 2023**. 

# 📝 Publications 

## Multimodal Representation Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Main</div><img src='images/ACL26ML.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

L2Dir: Integrating L2L_2-Norm and Directional Alignment for Unsupervised Contrastive Representation Learning in Multimodal Retrieval

**Tianyu Zong**, Rui Dai, Hongzhu Yi, Yuanxiang Wang, Zhenghao Zhang, Zhenyu Guan, Yujia Yang, Bingkang Shi, Yueyang Ding, Xiangxiang Chu, Kaikui Liu, Jungang Xu
</div>
</div>

## Benchmark
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Main</div><img src='images/ACL26MG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

FAIRGAMER: Evaluating Social Biases in LLM-Based Video Game NPCs

Bingkang Shi, Jen-tse Huang, Luo Long, **Tianyu Zong**, Hongzhu Yi, Yuanxiang Wang, Songlin Hu, Xiaodan Zhang, Zhongjiang Yao
</div>
</div>

## Time Series
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src='images/ACL26F.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

LLaTiSA: Towards Difficulty-Stratified Time Series Reasoning from Visual Perception to Semantics

Yueyang Ding, HaoPeng Zhang, Rui Dai, Yi Wang, **Tianyu Zong**, Kaikui Liu, Xiangxiang Chu
</div>
</div>

## Graph Representation
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/AAAI26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Deep Graph Learning for Incomplete Multi-View Clustering with Masked Graph Reconstruction Loss.](https://ojs.aaai.org/index.php/AAAI/article/view/40091)
[**Code**](https://ojs.aaai.org/index.php/AAAI/article/view/40091)

Zhenghao Zhang, Jun Xie, Xingchen Chen, Tao Yu, Hongzhu Yi, Kaixin Xu, Yuanxiang Wang, **Tianyu Zong**, Xinming Wang, Jiahuan Chen, Guoqing Chao, Feng Chen, Zhepeng Wang, Jungang Xu
</div>
</div>

## Unsupervised Sentence Embedding
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/temp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JTCSE: Joint Tensor Modulus Constraints and Cross Attention for Unsupervised Contrastive Learning of Sentence Embeddings](https://export.arxiv.org/abs/2505.02366),
*Major Revision Completed*
[**Code**](https://github.com/tianyuzong/JTCSE) and [**Model**](https://huggingface.co/UCASzty)

**Tianyu Zong**, Hongzhu Yi, Bingkang Shi, Yuanxiang Wang, Jungang Xu
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/aaai25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TNCSE: Tensor's Norm Constraints for Unsupervised Contrastive Learning of Sentence Embeddings](https://ojs.aaai.org/index.php/AAAI/article/view/34816), 
**Oral Paper, Top 4.63% of submissions!**
[**Code**](https://github.com/tianyuzong/TNCSE) and [**Model**](https://huggingface.co/UCASzty) 

**Tianyu Zong**, Bingkang Shi, Hongzhu Yi, Jungang Xu
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/aaai23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Ensemble Distillation Framework for Sentence Embeddings with Multilingual Round-Trip Translation](https://ojs.aaai.org/index.php/AAAI/article/view/26647)

**Tianyu Zong**, Likun Zhang
</div>
</div>

# 📖 Educations
- *2023.09 - Present*, Ph.D. in Computer Application Technology, University of Chinese Academy of Sciences (UCAS)
- *2020.09 - 2023.06*, M.S. in Electronic Information, University of Chinese Academy of Sciences (UCAS)
- *2016.09 - 2020.06*, B.S. in Electronic Information Engineering, North China University of Technology

# 🎖 Honors and Awards
- *2026.06* "Merit Student" (三好学生), University of Chinese Academy of Sciences
- *2020 - 2025* Second-Class Academic Scholarship, UCAS (Awarded for 6 consecutive years)
- *2020.11* Freshman Scholarship, UCAS
- *2019.08* Third Prize, National Undergraduate Electronic Design Contest (Beijing Division)
- *2018.11* First Prize, 10th National Chinese Mathematics Competition (Non-Mathematics Major)
- *2018.09* Second Prize, Beijing Mathematical Contest in Modeling for College Students
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
- *2025.10 - Present*, **Research Intern**, Alibaba Amap (高德地图). 
  - *Topic*: Feed-forward relighting 3D reconstruction and visual representation training for world models.
- *2025.07 - 2025.09*, **Embodied AI Intern**, Qiwu Technology (启物科技). 
  - *Topic*: VLA pre-training and reasoning optimization for robotic manipulation (LeRobot framework).
