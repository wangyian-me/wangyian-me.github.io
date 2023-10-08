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

# About me
I am currently a first-year PhD student in computer science at the University of Massachusetts Amherst, advised by [Prof. Chuang Gan](https://people.csail.mit.edu/ganchuang/).
My primary research focus centers around Robotics and Embodied AI, with a particular emphasis on robot skill acquisition. My work primarily revolves around equipping robots with the capability to acquire versatile skills and improve their generalization abilities. The practical applications of my research span across various domains, including domestic robots and autonomous manipulation tasks.
Previous to my graduate study, I obtained my bachelor degree in Peking University when I worked as an undergraduate member in [Center on Frontiers of Computing Studies (CFCS)](https://cfcs.pku.edu.cn/english/), under the guidance of [Prof. Hao Dong](https://zsdonghao.github.io/).


# 🔥 News
- *Sep 2023*: &nbsp; Welcome to our CoRL Workshop: [TGR](https://generalist-robots.github.io/)
- *Sep 2023*: &nbsp; First-year Phd in Umass

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='https://wangyian-me.github.io/images/mixup.png' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[MIXUP-AUGMENTED META-LEARNING FOR SAMPLE-EFFICIENT FINE-TUNING OF PROTEIN SIMULATORS](https://browse.arxiv.org/pdf/2308.15116.pdf)

[Jingbang Chen\*](), **Yian Wang***, [Xingwei Qv](), [ShuangJia Zheng](https://prokia.github.io/), [Yaodong Yang](https://www.yangyaodong.com/), [Hao Dong](http://zsdonghao.github.io/), [Jie Fu](https://bigaidream.github.io/)

[**Paper**](https://browse.arxiv.org/pdf/2308.15116.pdf) [**Code**](https://github.com/Jingbang-Chen/mixup-meta-protein-simulators)
- We apply soft prompt-based learning to molecular dynamics simulations, achieving strong generalization across various conditions with limited training data. The framework includes pre-training with data mixing and prompts, followed by meta-learning-based fine-tuning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='https://wangyian-me.github.io/images/adagif2.gif' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[AdaAfford: Learning to Adapt Manipulation Affordance for 3D Articulated Objects via Few-shot Interactions](https://arxiv.org/abs/2112.00246)

**Yian Wang***, [Ruihai Wu\*](https://warshallrho.github.io), [Kaichun Mo\*](https://www.cs.stanford.edu/~kaichun), Jiaqi Ke, [Qingnan Fan](https://fqnchina.github.io/), [Leonidas J. Guibas](https://geometry.stanford.edu/member/guibas/), [Hao Dong](http://zsdonghao.github.io/)

[**Paper**](https://arxiv.org/pdf/2112.00246.pdf) [**Project**](https://hyperplane-lab.github.io/AdaAfford/) [**Code**](https://github.com/wangyian-me/AdaAffordCode)
- We propose a novel framework that learns to perform very few test-time interactions for quickly adapting the affordance priors to more accurate instance-specific posteriors by eliminating the dynamic and kinematic uncertainties.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2022</div><img src='https://wangyian-me.github.io/images/vat_mart.gif' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[VAT-Mart: Learning Visual Action Trajectory Proposals for Manipulating 3D ARTiculated Objects](https://arxiv.org/abs/2106.14440)

[Ruihai Wu\*](https://warshallrho.github.io), [Yan Zhao\*](https://www.researchgate.net/profile/Yan-Zhao-182), [Kaichun Mo\*](https://www.cs.stanford.edu/~kaichun),
[Zizheng Guo](https://guozz.cn), **Yian Wang**, [Tianhao Wu](https://moistchi.github.io/tianhaowu.github.io/), [Qingnan Fan](https://fqnchina.github.io/), [Xuelin Chen](https://xuelin-chen.github.io/), [Leonidas J. Guibas](https://geometry.stanford.edu/member/guibas/), [Hao Dong](http://zsdonghao.github.io/)

[Paper](https://arxiv.org/pdf/2106.14440.pdf) [**Project**](https://hyperplane-lab.github.io/vat-mart/) [**Code**](https://github.com/warshallrho/VAT-Mart)
- We propose an interaction-for-perception framework to predict dense geometry-aware, interaction-aware, and task-aware visual action affordance for 3D articulated objects.
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

# 🎖 Honors and Awards
- SenseTime Scholarship 2021-2022
- Pexpertmaker to Merit Student in Peking University 2021-2022	
- Yanhong Li Scholarship in Peking University 2021-2022	
- Benz Scholarship in Peking University 2020-2021		
- Lee Wai Wing Scholarship in Peking University 2019-2020
- Merit Student in Peking University 2019-2020 and 2020-2021
- Second class prize in PKU-CPC 2021
- Silver medal in National Olympiad in Informatics (NOI), China Computer Federation, 2018

# 📖 Educations
- *Sep 2023 - now*, University of Massachusetts Amherst. 
- *Aug 2019 - July 2023*, undergraduate in Peking University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *Mar 2023 - Aug 2023*, [Taichi Graphics](https://taichi-graphics.com/), where I was lucky to work with [Tiantian Liu](https://tiantianliu.cn/) and [Yuanming Hu](https://yuanming.taichi.graphics/)
- *Apr 2022 - Oct 2022*, with [Dr. Jie Fu](https://bigaidream.github.io/) in [Mila](https://mila.quebec/en/) & [BAAI](https://www.baai.ac.cn/english.html).

# other projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2020 Mahjong AI Competition</div><img src='https://wangyian-me.github.io/images/mahjong.jpg' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[King of gambler](https://github.com/kylelv2000/mahjong)

**Yian Wang**, [Kunhang Lv](https://github.com/kylelv2000), [Zhehuan Chen](https://acmlczh.github.io/)

[**Paper**](https://www.botzone.org.cn/static/IJCAI2020MahjongPPT/15-King%20of%20gambler-komqaq-paper.pdf) [**Project**](https://kylelv.com/?p=726) [**Code**](https://github.com/kylelv2000/mahjong)
- We apply Depth First Search and pruning algorithm to compute our possibility of winning and analyze our complexity by combinatorial mathematics.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Course project</div><img src='https://wangyian-me.github.io/images/pkbg.gif' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[PKBG](https://github.com/wangyian-me/PKBG)

**Yian Wang**, [Zhehuan Chen](https://acmlczh.github.io/)

[**Project**](https://github.com/wangyian-me/PKBG) [**Code**](https://github.com/wangyian-me/PKBG)
- We self-design the task setting and run reinforcement learning ([TD3](https://github.com/sfujim/TD3)) on two competing agents to see what interesting strategy they will develop.
</div>
</div>

