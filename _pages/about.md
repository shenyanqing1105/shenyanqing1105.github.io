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

I am a Ph.D. student at the [National Key Laboratory of Human-Machine Hybrid Augmented Intelligence](http://www.aiar.xjtu.edu.cn/), Xi'an Jiaotong University ([XJTU](http://en.xjtu.edu.cn/)), under the supervision of [Prof. Nanning Zheng](https://gr.xjtu.edu.cn/en/web/nnzheng).
I received the B.E. degree in electronic and information engineering from Xi’an Jiaotong University.
My research interests mainly include **place recognition, SLAM, representation learning** and **autonomous vehicle**. Now I am learning embodied AI.
I have published several papers in T-PAMI, CVPR, RA-L, ICRA, IROS, and so on. I am lucky to have opportunities to work with [Assoc. Prof. Sanping Zhou](https://scholar.google.com/citations?user=2Drvv44AAAAJ&hl=zh-CN) and [Assist. Prof ShitaoChen](https://gr.xjtu.edu.cn/web/stchen).

I am lucky to have opportunities to work at Robotic Systems Lab ([RSL](https://rsl.ethz.ch/)) as a visiting Ph.D. student, supervised by [Assoc. Prof. Marco Hutter](https://rsl.ethz.ch/the-lab/people/person-detail.MTIxOTEx.TGlzdC8yNDQxLC0xNDI1MTk1NzM1.html), [Dr. Cesar Cadena](https://www.n.ethz.ch/~cesarc/), and [Dr. Olga Vysotska](https://inf.ethz.ch/people/people-atoz/person-detail.MzI1MTU3.TGlzdC8zMDQsLTIxNDE4MTU0NjA=.html). RSL family members are sooooo nice. That's what I'd like to call destiny.

[CV_CN](../files/CV-CN.pdf), [CV_EN](../files/CV-EN.pdf)

# 🔥 News

---

* *2025.03* :  One first-author paper is accepted by T-PAMI 2025.
* *2025.02* :  One first-author paper is accepted by CVPR 2025 (highlight🌟, ~top 10%).
* *2024.11* :  I was awarded the CMCC scholarship (Top 1%).
* *2024.01* :  One paper is accepted by ICRA 2024.
* *2023.02* :  One first-author paper is accepted by CVPR 2023.

# 📖 Educations

---

* Ph.D, Institute of Artificial Intelligence and Robotics, Xi'an Jiaotong University, 2019.09-2025.12
* Visiting Ph.D, Robotic Systems Lab, ETH Zurich, 2023.12-2024.12
* B.S., Electronic and Information Engineering, Xi'an Jiaotong University, 2015.09-2019.06

# 📝 Selected Publications

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2025</div><img src='images/structvpr++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4> <b>StructVPR++: Distill Structural and Semantic Knowledge with Weighting Samples for Visual Place Recognition </b> </font>
<p style="margin-bottom: 10px;">
<font size=2> <b> Yanqing Shen </b>, Sanping Zhou, Jingwen Fu, Ruotong Wang, Shitao Chen, Nanning Zheng* </font>
</p>

[<font size=2> [Paper] </font>]()

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 highlight</div><img src='images/forestlpr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4> <b> ForestLPR: LiDAR Place Recognition in Forests Attentioning Multiple BEV Density Images </b> </font>
<p style="margin-bottom: 10px;">
<font size=2> <b> Yanqing Shen </b>, Turcan Tuna, Cesar Cadena, Marco Hutter, Nanning Zheng* </font>
</p>

<font size=2>
In this work, we propose a robust LiDAR-based place recognition method for natural forests, ForestLPR. The cross-sectional images are represented by BEV density images of horizontal slices of the point cloud at different heights. Our approach utilizes a visual transformer as the shared backbone to produce sets of local descriptors and introduces a multi-BEV interaction module to attend to information at different heights adaptively.
</font>

[<font size=2> [Paper] </font>](https://arxiv.org/pdf/2503.04475) 
[<font size=2> [Code] </font>](https://github.com/shenyanqing1105/ForestLPR-CVPR2025) 
[<font size=2> [中文解读] </font>](https://mp.weixin.qq.com/s?__biz=MzkyMDY0OTc1NA==&mid=2247526300&idx=1&sn=e40c08bc8fc4dd77dab970866e386771&chksm=c0131f9ee03e0131d21b82ee9d8cb7ca0ea616cefb36e6b025f5bb1533a320352ef25072be1b&mpshare=1&scene=1&srcid=0310KXDK0YOHoKEt3TmXm6p8&sharer_shareinfo=1295a753d652a521a1632db30693d45c&sharer_shareinfo_first=1295a753d652a521a1632db30693d45c#rd)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/structvpr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4> <b>StructVPR: Distill Structural Knowledge with Weighting Samples for Visual Place Recognition </b> </font>
<p style="margin-bottom: 10px;">
<font size=2> <b> Yanqing Shen </b>, Sanping Zhou, Jingwen Fu, Ruotong Wang, Shitao Chen, Nanning Zheng* </font>
</p>

[<font size=2> [Paper] </font>](https://openaccess.thecvf.com/content/CVPR2023/papers/Shen_StructVPR_Distill_Structural_Knowledge_With_Weighting_Samples_for_Visual_Place_CVPR_2023_paper.pdf) 
[<font size=2> [中文解读] </font>](https://blog.csdn.net/gfdlxa/article/details/130730434)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/transvpr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4> <b>TransVPR: Transformer-based Place Recognition with Multi-level Attention Aggregation </b> </font>
<p style="margin-bottom: 10px;">
<font size=2> <b> Ruotong Wang<sup>1</sup> </b>, <b> Yanqing Shen<sup>1</sup> </b>, Weiliang Zuo, Sanping Zhou, Nanning Zheng* </font>
</p>

[<font size=2> [Paper] </font>](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_TransVPR_Transformer-Based_Place_Recognition_With_Multi-Level_Attention_Aggregation_CVPR_2022_paper.pdf) 


</div>
</div>

# 🏅 Selected Honors and awards

---

* **National Scholarship**, Xi’an Jiaotong University, (2016, 2017, 2018, 2020, 2023)

  top1%, Issued by Ministry of Education of the People's Republic of China
* CMCC Scholarship, top 1%, 2024
* Acedamic star of the [AIAR](http://www.aiar.xjtu.edu.cn/), 2020
* Freshman Scholarship, Xi’an Jiaotong University, 2019
* Academic Scholarship, Xi’an Jiaotong University, 2019
* Outstanding Undergraduate Graduates in Xi’an Jiaotong University, 2019
* Outstanding Student, Xi’an Jiaotong University, (2016, 2017, 2018, 2020)

# Hobbies

---

🏀Basketball (I am a big fan of [Stephen Curry](https://en.wikipedia.org/wiki/Stephen_Curry) since 2015)
