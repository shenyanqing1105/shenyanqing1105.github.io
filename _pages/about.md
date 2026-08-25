---
permalink: /
title: ""
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

<div class="intro" markdown="1">
I am currently a Zstar Researcher at the [Beijing Academy of Artificial Intelligence (BAAI)](https://www.baai.ac.cn/en).
I received the Ph.D. degree from the [National Key Laboratory of Human-Machine Hybrid Augmented Intelligence](http://www.aiar.xjtu.edu.cn/), Xi'an Jiaotong University ([XJTU](http://en.xjtu.edu.cn/)), in December 2025, under the supervision of [Prof. Nanning Zheng](https://gr.xjtu.edu.cn/en/web/nnzheng).
I received the B.E. degree in electronic and information engineering from Xi’an Jiaotong University.
My research interests mainly include **embodied AI** and **world models**.
I have published several papers in T-PAMI, CVPR, RA-L, ICRA, IROS, and so on. I am lucky to have had opportunities to work with [Assoc. Prof. Sanping Zhou](https://scholar.google.com/citations?user=2Drvv44AAAAJ&hl=zh-CN) and [Assist. Prof. Shitao Chen](https://gr.xjtu.edu.cn/web/stchen).

I am lucky to have opportunities to work at Robotic Systems Lab ([RSL](https://rsl.ethz.ch/)) as a visiting Ph.D. student, supervised by [Assoc. Prof. Marco Hutter](https://rsl.ethz.ch/the-lab/people/person-detail.MTIxOTEx.TGlzdC8yNDQxLC0xNDI1MTk1NzM1.html), [Dr. Cesar Cadena](https://www.n.ethz.ch/~cesarc/), and [Dr. Olga Vysotska](https://inf.ethz.ch/people/people-atoz/person-detail.MzI1MTU3.TGlzdC8zMDQsLTIxNDE4MTU0NjA=.html). RSL family members are sooooo nice. That's what I'd like to call destiny.
</div>

# 🔥 News

{:.news-list}
* *2026.08* Our team released [PRM-as-a-Judge 1.5](https://prm-as-a-judge.github.io/index.html), a toolkit for dense robot trajectory evaluation.
* *2026.07* Our team released [Orca](https://orca-wm.github.io/), a world model for next-state prediction.
* *2026.03* I joined the [Beijing Academy of Artificial Intelligence (BAAI)](https://www.baai.ac.cn/en) as a Zstar Researcher.
* *2025.12* I received the Ph.D. degree from Xi'an Jiaotong University.
* *2025.03* One first-author paper is accepted by T-PAMI 2025.
* *2025.02* One first-author paper is accepted by CVPR 2025 (highlight🌟, ~top 10%).
* *2024.11* I was awarded the CMCC scholarship (Top 1%).
* *2024.01* One paper is accepted by ICRA 2024.
* *2023.02* One first-author paper is accepted by CVPR 2023.

# 💼 Experiences

{:.meta-list}
* Zstar Researcher (智星研究员), Beijing Academy of Artificial Intelligence ([BAAI](https://www.baai.ac.cn/en)), 2026.03-present

# 📖 Educations

{:.meta-list}
* Ph.D, Institute of Artificial Intelligence and Robotics, Xi'an Jiaotong University, 2019.09-2025.12
* Visiting Ph.D, Robotic Systems Lab, ETH Zurich, 2023.12-2024.12
* B.S., Electronic and Information Engineering, Xi'an Jiaotong University, 2015.09-2019.06

# 📝 Selected Publications

<div class="paper-box">
<div class="paper-box-image"><div><div class="badge badge-arxiv">arXiv 2026</div><img src="images/prm-as-a-judge.png" alt="PRM-as-a-Judge 1.5"></div></div>
<div class="paper-box-text">
<p class="paper-title">PRM-as-a-Judge 1.5: A Toolkit for Robot Process Assessment</p>
<p class="paper-authors">Yuyang Liu<sup>*</sup>, <b>Yanqing Shen<sup>*</sup></b>, Ruike Chen, Jifan Zhao, et al.</p>
<p class="paper-links">
<a href="https://arxiv.org/pdf/2608.14284">Paper</a>
<a href="https://prm-as-a-judge.github.io/index.html">Project</a>
<a href="https://github.com/YuyangLiu2003/PRM-as-a-Judge">Code</a>
</p>
</div>
</div>

<div class="paper-box">
<div class="paper-box-image"><div><div class="badge badge-arxiv">arXiv 2026</div><img src="images/orca.png" alt="Orca"></div></div>
<div class="paper-box-text">
<p class="paper-title">Orca: The World is in Your Mind</p>
<p class="paper-authors">Yihao Wang, Yuheng Ji, Mingyu Cao, <b>Yanqing Shen</b>, et al.</p>
<p class="paper-links">
<a href="https://arxiv.org/pdf/2606.30534">Paper</a>
<a href="https://orca-wm.github.io/">Project</a>
<a href="https://github.com/orca-wm/Orca">Code</a>
</p>
</div>
</div>

<div class="paper-box">
<div class="paper-box-image"><div><div class="badge badge-tpami">T-PAMI 2025</div><img src="images/structvpr++.png" alt="StructVPR++"></div></div>
<div class="paper-box-text">
<p class="paper-title">StructVPR++: Distill Structural and Semantic Knowledge with Weighting Samples for Visual Place Recognition</p>
<p class="paper-authors"><b>Yanqing Shen</b>, Sanping Zhou, Jingwen Fu, Ruotong Wang, Shitao Chen, Nanning Zheng*</p>
</div>
</div>

<div class="paper-box">
<div class="paper-box-image"><div><div class="badge badge-cvpr">CVPR 2025 highlight</div><img src="images/forestlpr.png" alt="ForestLPR"></div></div>
<div class="paper-box-text">
<p class="paper-title">ForestLPR: LiDAR Place Recognition in Forests Attentioning Multiple BEV Density Images</p>
<p class="paper-authors"><b>Yanqing Shen</b>, Turcan Tuna, Cesar Cadena, Marco Hutter, Nanning Zheng*</p>
<p class="paper-links">
<a href="https://arxiv.org/pdf/2503.04475">Paper</a>
<a href="https://github.com/shenyanqing1105/ForestLPR-CVPR2025">Code</a>
<a href="https://mp.weixin.qq.com/s?__biz=MzkyMDY0OTc1NA==&mid=2247526300&idx=1&sn=e40c08bc8fc4dd77dab970866e386771&chksm=c0131f9ee03e0131d21b82ee9d8cb7ca0ea616cefb36e6b025f5bb1533a320352ef25072be1b&mpshare=1&scene=1&srcid=0310KXDK0YOHoKEt3TmXm6p8&sharer_shareinfo=1295a753d652a521a1632db30693d45c&sharer_shareinfo_first=1295a753d652a521a1632db30693d45c#rd">中文解读</a>
</p>
</div>
</div>

<div class="paper-box">
<div class="paper-box-image"><div><div class="badge badge-cvpr">CVPR 2023</div><img src="images/structvpr.png" alt="StructVPR"></div></div>
<div class="paper-box-text">
<p class="paper-title">StructVPR: Distill Structural Knowledge with Weighting Samples for Visual Place Recognition</p>
<p class="paper-authors"><b>Yanqing Shen</b>, Sanping Zhou, Jingwen Fu, Ruotong Wang, Shitao Chen, Nanning Zheng*</p>
<p class="paper-links">
<a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Shen_StructVPR_Distill_Structural_Knowledge_With_Weighting_Samples_for_Visual_Place_CVPR_2023_paper.pdf">Paper</a>
<a href="https://blog.csdn.net/gfdlxa/article/details/130730434">中文解读</a>
</p>
</div>
</div>

<div class="paper-box">
<div class="paper-box-image"><div><div class="badge badge-cvpr">CVPR 2022</div><img src="images/transvpr.jpg" alt="TransVPR"></div></div>
<div class="paper-box-text">
<p class="paper-title">TransVPR: Transformer-based Place Recognition with Multi-level Attention Aggregation</p>
<p class="paper-authors"><b>Ruotong Wang<sup>1</sup></b>, <b>Yanqing Shen<sup>1</sup></b>, Weiliang Zuo, Sanping Zhou, Nanning Zheng*</p>
<p class="paper-links">
<a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_TransVPR_Transformer-Based_Place_Recognition_With_Multi-Level_Attention_Aggregation_CVPR_2022_paper.pdf">Paper</a>
</p>
</div>
</div>

# 🏅 Selected Honors and awards

{:.meta-list}
* **National Scholarship**, Xi’an Jiaotong University, (2016, 2017, 2018, 2020, 2023)

  top1%, Issued by Ministry of Education of the People's Republic of China
* CMCC Scholarship, top 1%, 2024
* Acedamic star of the [AIAR](http://www.aiar.xjtu.edu.cn/), 2020
* Freshman Scholarship, Xi’an Jiaotong University, 2019
* Academic Scholarship, Xi’an Jiaotong University, 2019
* Outstanding Undergraduate Graduates in Xi’an Jiaotong University, 2019
* Outstanding Student, Xi’an Jiaotong University, (2016, 2017, 2018, 2020)

# ✨ Hobbies

🏀 Basketball (I am a big fan of [Stephen Curry](https://en.wikipedia.org/wiki/Stephen_Curry) since 2015), 🏸 Badminton, 🥾 Hiking, 💪 Fitness, 📺 Watching comedy variety (⭐ 喜单, 🎤 脱友, 😂 喜人, 🐒 新西游记)
