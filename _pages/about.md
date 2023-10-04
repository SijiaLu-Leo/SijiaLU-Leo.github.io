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

<!-- 我是复旦大学的一名在读博士生👨‍🎓。高中毕业于衡水中学。毕业🎓后，有幸进入到电子科技大学（成都的那个🐼🥘🌨） 数学物理基础科学实验班学习，并在成都与女朋友👩‍🎓💏🍀度过了四年的时光（感恩成电，遇见成都，并不存在秀恩爱）。

在博士期间，我的主要的研究方向为**类脑人工智能**，同时也对目标识别以及其他人工智能相关的领域感兴趣。目前的研究方向中，涉及到**脉冲神经网络（Spiking Neural Network）**、**竞争学习（Competitive Learning）**、**计算神经科学**等相关的知识。并且，现在我的主要研究聚焦于**无监督学习**中。

我的爱好是各种球类运动⛹️‍🏀🏓🏸，最近也比较喜欢游泳🏊‍♀️🏊。

文化的最终目标，是在人世间普及爱和善良。 -->

I am a PhD student 👨‍🎓 at Fudan University. After high school, I was fortunate to enter the UESTC (University of Electronic Science and Technology of China, the one in Chengdu 🐼🥘🌨) to study in the experimental class of basic science in mathematics and physics, and spent four years in Chengdu with my girlfriend 👩‍🎓💏🍀.

During my doctoral period, my main research direction was **Brain-like Artificial Intelligence**, and I am interested in object recognition and other artificial intelligence-related fields. The current research direction involves **Spiking Neural Network**, **Competitive Learning**, **Computational Neuroscience** and other related knowledge. And, now my main research focuses on **unsupervised learning**.

My hobbies are various ball games ⛹️‍🏀🏓🏸, and recently I also like swimming 🏊‍♀️🏊.

I believe, the ultimate goal of knowledge is to spread love and kindness in the world.

<!--
I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- *2023.07*: &nbsp;🎉 Graduated from Fudan University 👨‍🎓👩‍🎓
- *2023.01*: &nbsp;🎉 Happy New Year 🎆🎆🎆!
- *2022.03*: &nbsp;🎉 One first-authored paper about equivalence between Linear LIF and ReLU-AN model is accepted by Frontier in neuroscience.
- *2018.09*: &nbsp;🎉 I entered Fudan University to study for a Ph.D.
- *2018.07*: &nbsp;🎉 I got my Bachelor of Science degree from UESTC.

# 📝 Publications 

## 🎓 Spiking Neural Network
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Yufei Guo\* **, Xinyi Tong\*, Yuanpei Chen, Liwen Zhang, Xiaode Liu, Zhe Ma, Xuhui Huang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Frontiers in Neuroscience</div><img src='images/theequivalenceofCLIF.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Linear Leaky-Integrate-and-Fire Neuron Model Based Spiking Neural Networks and Its Mapping Relationship to Deep Neural Networks](https://www.frontiersin.org/articles/10.3389/fnins.2022.857513/full)

**Sijia Lu**\*, Feng Xu\*
  
- We proposed a mapping relationship between the Linear LIF model and ReLU-AN model, bridged the Gap between SNNs and DNNs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACES-2022</div><img src='images/weights_visulization_with_step-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A brain-inspired unsupervised learning algorithm for SAR Target Classification](https://ieeexplore.ieee.org/document/10065164)

**Sijia Lu**\*, Feng Xu\*
  
Inspired by STDP, this paper presents a Phase-dependent plasticity (PDP) unsupervised learning algorithm. Combined with phase information, this method can introduce STDP into the ANNs. Our method can achieve a classification accuracy of 98.47% on the MSTAR dataset. PDP unsupervised algorithm is a practical attempt to combine ANNs with Spike Neural Networks (SNNs).
</div>
</div>

<!-- 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/reloss.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reducing Information Loss for Spiking Neural Networks]()

**Yufei Guo**\*, Yuanpei Chen\*, Liwen Zhang, YingLei Wang, Xiaode Liu, Xinyi Tong, Yuanyuan Ou, Xuhui Huang, Zhe Ma
  
- This work aims at addressing the information loss problem caused by the ''Hard Reset'' mechanism of neurons and the 0/1 spike quantification. Then, the SRIF
model, which will drive the membrane potential to a dynamic reset potential, and the MPR that can adjust the membrane potential to a new value closer to quantification spikes than itself are proposed. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/real.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Real Spike: Learning Real-valued Spikes for Spiking Neural Networks]()

**Yufei Guo**\*, Liwen Zhang\*, Yuanpei Chen, Xinyi Tong, Xiaode Liu, YingLei Wang, Xuhui Huang, Zhe Ma
  
- We proposed Real Spike, which aims at enhancing the representation capacity for an SNN by learning real-valued spikes during training and transferring the
rich representation capacity into inference-time SNN by re-parameterizing the shared convolution kernel to different ones.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/recdis.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RecDis-SNN: Rectifying Membrane Potential Distribution for Directly Training Spiking Neural Networks](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_RecDis-SNN_Rectifying_Membrane_Potential_Distribution_for_Directly_Training_Spiking_Neural_CVPR_2022_paper.pdf)

**Yufei Guo**\*, Xinyi Tong\*, Yuanpei Chen, Liwen Zhang, Xiaode Liu, Zhe Ma, Xuhui Huang
  
- We present a new perspective to understand the difficulty of training SNNs by analyzing three undesired shifts of membrane potential distribution in forward propagation and the MPD-Loss to penalize the undesired shifts. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2021</div><img src='images/differential.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Differentiable Spike: Rethinking Gradient-Descent for Training Spiking Neural Networks](https://proceedings.neurips.cc/paper/2021/file/c4ca4238a0b923820dcc509a6f75849b-Paper.pdf)

Yuhang Li\*, **Yufei Guo**\*, Shanghang Zhang, Shikuang Deng, Yongqing Hai, Shi Gu
  
- We propose a new family of Differentiable Spike (Dspike) functions that can adaptively evolve during training to find the optimal shape and smoothness for gradient estimation for spiking neural networks. 
</div>
</div> -->
<!-- 
## 🛠️ Computational mechanics
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Computational Mechanics 2022</div><img src='images/smoothing.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A new mesh smoothing method based on a neural network](https://link.springer.com/article/10.1007/s00466-021-02097-z)

**Yufei Guo**, Chuanrui Wang, Zhe Ma, Xuhui Huang, Kewu Sun, Rongli Zhao
  
- We present a new smoothing method. The proposed method imitates the optimization-based smoothing based on a neural network, but it calculates the optimal position of a free node straightforwardly. Hence, the proposed method is more efficient than these optimization-based smoothing methods while being comparable in terms of mesh quality.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Mathematical Modelling 2021</div><img src='images/balls.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive surface mesh remeshing based on a sphere packing method and a node insertion/deletion method](https://www.sciencedirect.com/science/article/abs/pii/S0307904X21002353?via%3Dihub)

**Yufei Guo**\*, Yongqing Hai\*
  
- We present a triangular mesh remeshing method based on a sphere packing method and a node insertion/deletion method for surface meshes. The proposed method remeshes the surface mesh without projection of local areas, the intersection of fronts, Lloyd relaxation, and other complicated calculations, and the proposed method can generate a high-quality mesh without dependence on the quality of the original mesh, which make the method efficient and effective.
</div>
</div>

- [Enhanced optimal delaunay triangulation methods with connectivity regularization](http://www.amjcu.zju.edu.cn/amjcub/2020-2029/202203/453-469.pdf), Yongqing Hai, **Yufei Guo**\*, Rongli Zhao, Kewu Sun, Feifei Shang, **Appl. Math. J. Chinese Univ. 2022**, Corresponding Author.
- [A CAE-oriented mesh hole-filling algorithm focusing on geometry and quality](https://www.emerald.com/insight/content/doi/10.1108/EC-07-2021-0411/full/html), Yongqing Hai, **Yufei Guo**\*, Mo Dong, **Engineering Computations 2022**, Corresponding Author.
- [Triangular Mesh Boolean Operation Method for Finite Element Analysis](https://www.china-simulation.com/CN/10.16182/j.issn1004731x.joss.20-0957), **Yufei Guo**, kang Zhao, Yongqing Hai, **Journal of System Simulation 2022**, First Author.
- [An Improved Advancing-front-Delaunay Method for Triangular Mesh Generation](https://link.springer.com/article/10.1007/s00466-021-02097-z), **Yufei Guo**, Xuhui Huang, Zhe Ma, Rongli Zhao, Kewu Sun, **Computer Graphics International Conference 2021**, First Author.
- [Regular Position-Oriented Method for Mesh Smoothing](https://link.springer.com/article/10.1007/s10338-020-00201-z), Yongqing Hai, **Yufei Guo**\*, Siyuan Cheng, Yunpeng Hai, **Acta Mechanica Solida Sinica 2020**, Corresponding Author.
- [Direct modifications of tetrahedral meshes](https://www.emerald.com/insight/content/doi/10.1108/EC-12-2019-0573/full/html), **Yufei Guo**, Yongqing Hai, Jianfei Liu, **Engineering Computations 2020**, First Author.
- [Surface Adaptive Mesh Generation for STL Models Based on Ball-Packing Method](https://www.jcad.cn/jcadcms/show.action?code=publish_402880124b362464014b3c4d819803a1&newsid=3b5491011cd34af2bb3043a6ef810cec), **Yufei Guo**, Feifei Shang, Jianfei Liu, **Journal of Computer-Aided Design and Computer Graphics 2018**, First Author.
 -->
# 💬 Invited Talks
<!-- - *2022.08*, I am invited to talk about Spiking Neural Networks at the conference on intelligence and aerospace.
- *2022.07*, I am invited to talk about Spiking Neural Networks at the conference on mathematics and aerospace. -->

# 🎖 Honors and Awards
- *2019.10* Samsung Scholarship.
- *2018.06* Outstanding Graduate of University of Electronic Science and Technology of China
- *2017.10* China National Scholarship.  

# 📖 Educations
- *2018.09 - 2023.07*, Doctor, Fudan University, Shanghai. 
- *2014.09 - 2018.06*, Undergraduate, University of Electronic Science and Technology of China, Chengdu. 

# 💻 Academic Services
- **Chairman** of IEEE Fudan University Student Branch and IEEE GRSS Fudan Student Chapter
