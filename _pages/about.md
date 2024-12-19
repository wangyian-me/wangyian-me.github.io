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
I am currently a second-year PhD student in computer science at the University of Massachusetts Amherst, advised by [Prof. Chuang Gan](https://people.csail.mit.edu/ganchuang/).
My primary research focus centers around Robotics and Embodied AI, with a particular emphasis on robot skill acquisition. My work primarily revolves around equipping robots with the capability to acquire versatile skills and improve their generalization abilities. The practical applications of my research span across various domains, including domestic robots and autonomous manipulation tasks.
Previous to my graduate study, I obtained my bachelor degree in Peking University when I worked as an undergraduate member in [Center on Frontiers of Computing Studies (CFCS)](https://cfcs.pku.edu.cn/english/), under the guidance of [Prof. Hao Dong](https://zsdonghao.github.io/).


# 🔥 News
- *Dec 2024*: &nbsp; We release [Genesis](https://genesis-embodied-ai.github.io)!!!!!!
- *Sep 2024*: &nbsp; Our paper [Architect](https://wangyian-me.github.io/Architect/) has been accepted by Neurips 2024!
- *May 2024*: &nbsp; Internship in NVIDIA!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='https://wangyian-me.github.io/images/architect.gif' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[ARCHITECT: Generating Vivid and Interactive 3D Scenes with Hierarchical 2D Inpainting](https://arxiv.org/abs/2411.09823)

**Yian Wang***, [Xiaowen Qiu\*](), [Jiageng Liu\*](), [Zhehuan Chen](), [Jiting Cai](), [Tsun-Hsuan Wang](https://zswang666.github.io/), [Yufei Wang](https://yufeiwang63.github.io/), [Zhou Xian](https://www.zhou-xian.com/)

[**Paper**](https://arxiv.org/abs/2411.09823) [**Project**](https://wangyian-me.github.io/Architect/)
- In this work, we utilize foundation visual perception models to obtain each generated object from the image and leverage pre-trained depth estimation models to lift the generated 2D image to 3D space.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='https://wangyian-me.github.io/images/banner.webp' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Generalist Robots: A Promising Paradigm via Generative Simulation](https://arxiv.org/pdf/2305.10455.pdf)

[Zhou Xian](https://www.zhou-xian.com/), [Theophile Gervet](https://theophilegervet.github.io/), [Zhenjia Xu](https://ylqiao.net/), [Tsun-Hsuan Wang](https://zswang666.github.io/), **Yian Wang**, [Yufei Wang](https://yufeiwang63.github.io/)

[**Paper**](https://arxiv.org/pdf/2305.10455.pdf)
- The purpose of this document is to share the excitement of the authors with the community and highlight a promising research direction in robotics and AI. The authors believe the proposed paradigm is a feasible path towards accomplishing the longstanding goal of robotics research: deploying robots, or embodied AI agents more broadly, in various non-factory real-world settings to perform diverse tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='https://wangyian-me.github.io/images/logo_002.webp' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[ROBOGEN: TOWARDS UNLEASHING INFINITE DATA FOR AUTOMATED ROBOT LEARNING VIA GENERATIVE SIMULATION](https://arxiv.org/pdf/2311.01455.pdf)

[Yufei Wang\*](https://yufeiwang63.github.io/), [Zhou Xian\*](https://www.zhou-xian.com/), [Feng Chen\*](https://robogen-ai.github.io), [Tsun-Hsuan Wang](https://zswang666.github.io/), **Yian Wang**, [Katerina Fragkiadaki](https://www.cs.cmu.edu/~katef/), [Zackory Erickson](https://zackory.com/), [David Held](http://davheld.github.io/), [Chuang Gan](http://people.csail.mit.edu/ganchuang/)
                            
[**Paper**](https://arxiv.org/pdf/2311.01455.pdf) [**Project**](https://robogen-ai.github.io/) [**Code**](https://github.com/Genesis-Embodied-AI/RoboGen)
- RoboGen leverages the latest advancements in foundation and generative models. Instead of directly using or adapting these models to produce policies or low-level actions, we advocate for a generative scheme, which uses these models to automatically generate diversified tasks, scenes, and training supervisions, thereby scaling up robotic skill learning with minimal human supervision.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='https://wangyian-me.github.io/images/multiply.gif' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[MultiPLY:A Multisensory Object-Centric Embodied Large Language Model in 3D World](https://arxiv.org/abs/2401.08577)

[Yining Hong](https://evelinehong.github.io), [Zishuo Zheng](), [Peihao Chen](https://peihaochen.github.io), **Yian Wang**, [Junyan Li](https://senfu.github.io), [Chuang Gan](http://people.csail.mit.edu/ganchuang/)
                            
[**Paper**](https://arxiv.org/abs/2401.08577) [**Project**](https://vis-www.cs.umass.edu/multiply/) [**Code**](https://github.com/UMass-Foundation-Model/MultiPLY)
- In this work, we enpower the LLM with multisensory perception and active observation abiltiy. We propose MultiPLY, a multisensory embodied large language model that could incorporate multisensory interactive data, including visual, audio, tactile, and thermal information into large language models, thereby establishing the correlation among words, actions, and perceptions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024 Spotlight</div><img src='https://wangyian-me.github.io/images/thinshelllabgif.gif' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[Thin-Shell Object Manipulations With Differentiable Physics Simulations](https://openreview.net/pdf?id=KsUh8MMFKQ)

**Yian Wang***, [Juntian Zheng\*](), [Zhehuan Chen](https://acmlczh.github.io), [Zhou Xian](https://www.zhou-xian.com), [Gu Zhang](https://www.gu-zhang.com), [Chao Liu](https://chaoliu.tech), [Chuang Gan](http://people.csail.mit.edu/ganchuang/)
                            
[**Paper**](https://openreview.net/pdf?id=KsUh8MMFKQ) [**Project**](https://vis-www.cs.umass.edu/ThinShellLab)
- We introduce ThinShellLab - a fully differentiable simulation platform tailored for robotic interactions with diverse thin-shell materials possessing varying material properties, enabling flexible thin-shell manipulation skill learning and evaluation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='https://wangyian-me.github.io/images/2024ICRA-coarse2fine-min.jpg' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[Articulated Object Manipulation with Coarse-to-fine Affordance for Mitigating the Effect of Point Cloud Noise](https://arxiv.org/pdf/2402.18699.pdf)

[Suhan Ling\*](), **Yian Wang***, Shiguang Wu, Yuzheng Zhuang, Tianyi Xu, Yu Li, Chang Liu, [Hao Dong](http://zsdonghao.github.io/)
                            
[**Paper**](https://arxiv.org/pdf/2402.18699.pdf) [**Project**](https://sites.google.com/view/coarse-to-fine/) 
- We leverage the property of real-world scanned point cloud that, the point cloud becomes less noisy when the camera is closer to the object. Therefore, we propose a novel coarse-to-fine affordance learning pipeline to mitigate the effect of point cloud noise in two stages.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='https://wangyian-me.github.io/images/mixup.png' alt="sym" width="500" height="300"></div></div>
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

<!--# other projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2020 Mahjong AI Competition</div><img src='https://wangyian-me.github.io/images/mahjong.jpg' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[King of gambler](https://github.com/kylelv2000/mahjong)

**Yian Wang**, [Kunhang Lv](https://github.com/kylelv2000), [Zhehuan Chen](https://acmlczh.github.io/)

[**Paper**](https://www.botzone.org.cn/static/IJCAI2020MahjongPPT/15-King%20of%20gambler-komqaq-paper.pdf) [**Project**](https://kylelv.com/?p=726) [**Code**](https://github.com/kylelv2000/mahjong)
- We apply Depth First Search and pruning algorithm to compute our possibility of winning and analyze our complexity by combinatorial mathematics.
</div>
</div> -->

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Course project</div><img src='https://wangyian-me.github.io/images/pkbg.gif' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[PKBG](https://github.com/wangyian-me/PKBG)

**Yian Wang**, [Zhehuan Chen](https://acmlczh.github.io/)

[**Project**](https://github.com/wangyian-me/PKBG) [**Code**](https://github.com/wangyian-me/PKBG)
- We self-design the task setting and run reinforcement learning ([TD3](https://github.com/sfujim/TD3)) on two competing agents to see what interesting strategy they will develop.
</div>
</div> -->

