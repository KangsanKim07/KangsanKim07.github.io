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
---

**Kangsan Kim (김강산)** (kangsan.kim \[at] kaist \[dot] ac \[dot] kr), and here is my [CV (Curriculum Vitae)](assets/Curriculum_Vitae.pdf).

---

I am a Ph.D. student in the Graduate School of AI at KAIST ([MLAI lab](https://www.mlai-kaist.com)), fortunate to be advised by Prof. [Sung Ju Hwang](http://www.sungjuhwang.com). 

My research focuses on developing autonomous AI agents that can perceive, reason, and act in the real world, spanning coding, computer use, and embodied agents. I have previously worked on building memory in these agents that accumulates from past experience, enabling self-evolution, as well as retrieving knowledge from heterogeneous multimodal sources. Recently, I have also been interested in training agents through reinforcement learning to optimize behavior for specific tasks and objectives.

# 🔥 News
- *2026.04*: &nbsp;📖 Memory Transfer Learning, which studies cross-domain memory transfer in coding agents, is released on [arxiv](https://arxiv.org/abs/2604.14004).
- *2026.04*: &nbsp;🇺🇸 UniversalRAG got accepted to ACL 2026 Main!
- *2026.03*: &nbsp;📖 MA-EgoQA: Multi-Agent Egocentric Video QA is released on [arxiv](https://arxiv.org/abs/2603.09827).
- *2026.02*: &nbsp;🇺🇸 WorldMM got accepted to CVPR 2026 Highlight, and HoliSafe got accepted to CVPR 2026 Findings!
- *2025.07*: &nbsp;<img src="assets/nyu.png" alt="NYU" width="20" style="vertical-align: middle;" /> Joined NYU as a visiting student under Prof. [Mengye Ren](https://mengyeren.com).
- *2025.05*: &nbsp;📖 HoliSafe is released on [arXiv](https://www.arxiv.org/abs/2506.04704).
- *2025.05*: &nbsp;🇦🇹 VideoRAG got accepted to ACL Findings 2025.
<!-- - *2025.04*: &nbsp;📖 UniversalRAG is released on [arXiv](https://arxiv.org/abs/2504.20734). -->
<!-- - *2025.02*: &nbsp;🇺🇸 VideoICL got accepted to CVPR 2025. -->

# 📝 Publications 

- <b>Memory Transfer Learning: How Memories are Transferred Across Domains in Coding Agents</b><br>
[[project page]](https://memorytransfer.github.io/) [[paper]](https://arxiv.org/abs/2604.14004) [[code]](https://github.com/KangsanKim07/MemoryTransferLearning) <br>
&#x200B;<span style="color:darkblue">**Kangsan Kim**</span>, Minki Kang, Taeil Kim, Yanlai Yang, Mengye Ren†, Sung Ju Hwang† <br>
**under review** 2026

- <b>MA-EgoQA: Question Answering over Egocentric Videos from Multiple Embodied Agents</b><br>
[[project page]](https://ma-egoqa.github.io/) [[paper]](https://arxiv.org/abs/2603.09827) [[code]](https://github.com/KangsanKim07/MA-EgoQA) <br>
&#x200B;<span style="color:darkblue">**Kangsan Kim**</span>, Yanlai Yang, Suji Kim, Woongyeong Yeo, Youngwan Lee, Mengye Ren†, Sung Ju Hwang† <br>
**under review** 2026

- <b>WorldMM: Dynamic Multimodal Memory Agent for Long Video Reasoning</b> <br>
[[project page]](https://worldmm.github.io/) [[paper]](https://arxiv.org/abs/2512.02425) [[code]](https://github.com/wgcyeo/WorldMM) <br>
&#x200B;Woongyeong Yeo\*, <span style="color:darkblue">**Kangsan Kim\***</span>, Jaehong Yoon†, Sung Ju Hwang† <br>
Conference on Computer Vision and Pattern Recognition (**CVPR**) 2026 <span style="color:darkred">**Highlight**</span>

- <b>HoliSafe: Holistic Safety Benchmarking and Modeling for Vision-Language Model</b> <br>
[[project page]](https://youngwanlee.github.io/holisafe/) [[paper]](https://www.arxiv.org/abs/2506.04704) [[code]](https://github.com/youngwanLEE/holisafe) <br>
&#x200B;Youngwan Lee, <span style="color:darkblue">**Kangsan Kim**</span>, Kwanyong Park, Ilchae Jung, Sujin Jang, Seanie Lee, Yong-Ju Lee, Sung Ju Hwang <br>
Findings of Conference on Computer Vision and Pattern Recognition (**CVPR Findings**) 2026

- <b>UniversalRAG: Retrieval-Augmented Generation over Corpora of Diverse Modalities and Granularities</b> <br>
[[project page]](https://universalrag.github.io/) [[paper]](https://arxiv.org/abs/2504.20734) [[code]](https://github.com/wgcyeo/UniversalRAG) <br>
&#x200B;Woongyeong Yeo\*, <span style="color:darkblue">**Kangsan Kim\***</span>, Soyeong Jeong, Jinheon Baek, Sung Ju Hwang <br>
Annual Meeting of the Association for Computational Linguistics (**ACL**) 2026

- <b>VideoRAG: Retrieval-Augmented Generation over Video Corpus</b> <br>
[[paper]](https://arxiv.org/abs/2501.05874) [[poster]](assets/poster/VideoRAG.pdf) [[code]](https://github.com/starsuzi/VideoRAG) <br>
&#x200B;Soyeong Jeong\*, <span style="color:darkblue">**Kangsan Kim\***</span>, Jinheon Baek\*, Sung Ju Hwang <br>
Findings of the Association for Computational Linguistics (**ACL Findings**) 2025

- <b>VideoICL: Confidence-based Iterative In-context Learning for Out-of-Distribution Video Understanding</b> <br>
[[paper]](https://arxiv.org/abs/2412.02186) [[poster]](https://drive.google.com/file/d/1bSE0MZVCmNDr8i_FSfOsGmgKpLCaS9Kf/view?usp=sharing) [[code]](https://github.com/KangsanKim07/VideoICL) <br>
&#x200B;<span style="color:darkblue">**Kangsan Kim\***</span>, Geon Park\*, Youngwan Lee, Woongyeong Yeo, Sung Ju Hwang <br>
Conference on Computer Vision and Pattern Recognition (**CVPR**) 2025

(*: equal contribution, †: equal advising)

# 💻 Experiences
- <b>Visiting Ph.D. Student, [New York University](https://www.nyu.edu)</b> <br>
*2025.07 - 2025.10*, Brooklyn, NY, USA  <br>
Advisor: Prof. [Mengye Ren](https://mengyeren.com) <br>
Studying question answering over egocentric video streams from multiple embodied agents. (MA-EgoQA)

- <b>Computer Vision Engineer Intern, [B GARAGE](https://www.bgarage.ai/)</b> <br>
*2022.10 - 2023.07*, San Jose, CA, USA <br>
Developed an ultra-fast edge instance segmentation model that can segment anything in the warehouse.

- <b>Machine Learning(NLP) Scientist Intern, [NAVER](https://papago.naver.com/)</b> <br>
*2021.07 - 2021.10*, Remote <br>
Built and improved end-to-end Korean-English speech translation model.

# 📖 Educations
- *2024.03 - Current*, Ph.D. in Artificial Intelligence, Korea Advanced Institute of Science and Technology (KAIST).
- *2018.03 - 2024.02*, B.S. in Computer Science, Korea Advanced Institute of Science and Technology (KAIST). 

# 🏆 Honors and Awards
- *2023.06* Qualcomm-KAIST Innovation Award. 
- *2020.09* Dean’s List, College of Engineering. 

# 💬 Invited Talks
- <b>WorldMM: Dynamic Multimodal Memory Agent for Long Video Reasoning</b> <br>
*2026.01*, Multimodal Weekly hosted by TwelveLabs, Online | [[post]](https://www.linkedin.com/posts/twelvelabs_multimodalweekly-activity-7417644198042148864--AA6/)
- <b>VideoRAG: Retrieval-Augmented Generation over Video Corpus, and Beyond</b> <br>
*2025.09*, Multimodal Weekly hosted by TwelveLabs, Online | [[post]](https://www.linkedin.com/posts/twelvelabs_multimodalweekly-activity-7371294497265213440-CNY-?utm_source=share&utm_medium=member_desktop&rcm=ACoAADq_WTEBJ1arpdNe6GtaINJTvwqeAxpc-vo)
- <b>Video as a Knowledge Source: Video-based Retrieval-Augmented Generation in Diverse Scenarios</b> <br>
*2025.09*, NYU Global AI Frontier Lab, Brooklyn, NY, USA

# 💯 Academic Service
- Reviewer of ARR Jan 2026, ICML 2026, and NeurIPS 2026