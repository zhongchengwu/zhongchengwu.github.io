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

I am currently pursuing the Ph.D. degree (supervised by Prof. [Ting-Zhu Huang](http://www.math.uestc.edu.cn/info/1081/2041.htm) and Prof. [Liang-Jian Deng](https://liangjiandeng.github.io/)) with the School of Mathematical Sciences, [University of Electronic Science and Technology of China](https://www.uestc.edu.cn/) (UESTC), Chengdu, China.

From Sep. 2023, I am working with Prof. [Gemine Vivone](https://sites.google.com/site/vivonegemine), sponsored by the China Scholarship Council, at CNR-IMAA, Potenza, Italy.

My research interest includes image processing, tensor learning, and pansharpening.

E-mail: <wuzhch97@163.com> &emsp;

# 🎙 News 
- *2024.02*: &nbsp;One paper for pansharpening is accepted by <b>Information Fusion</b>.

# 📄 Publications 
<b>Note</b>: \* indicates the corresponding author.

- [Pansharpening via Semi-Framelet-Guided Sparse Reconstruction](https://www.sciencedirect.com/science/article/pii/S1566253524000757) <br>
  <b>Zhong-Cheng Wu</b>, Gemine Vivone\*, Ting-Zhu Huang\*, Liang-Jian Deng <br>
  *Information Fusion* (<b>IF</b>), 2024. [[Code](https://zhongchengwu.github.io)]

- [Dynamical Fusion Model with Joint Variational and Deep Priors for Hyperspectral Image Super-resolution](https://ieeexplore.ieee.org/document/10156889) <br>
  Hong-Xia Dou, <b>Zhong-Cheng Wu\*</b>, Yu-Wei Zhuo, Liang-Jian Deng, Gemine Vivone <br>
  *IEEE Geoscience and Remote Sensing Letters* (<b>GRSL</b>), 2023.

- [A Framelet Sparse Reconstruction Method for Pansharpening with Guaranteed Convergence](https://www.aimsciences.org/article/doi/10.3934/ipi.2023016) <br>
  <b>Zhong-Cheng Wu</b>, Ting-Zhu Huang\*, Liang-Jian Deng\*, Gemine Vivone <br>
  *Inverse Problems and Imaging* (<b>IPI</b>), 2023. [[PDF](https://zhongchengwu.github.io/papers/ncfsrm_ipi2023.pdf)] [[Code](https://github.com/zhongchengwu/code_ncFSRM)]

- [LRTCFPan: Low-Rank Tensor Completion Based Framework for Pansharpening](https://ieeexplore.ieee.org/abstract/document/10054514) <br>
  <b>Zhong-Cheng Wu</b>, Ting-Zhu Huang\*, Liang-Jian Deng\*, Jie Huang, Jocelyn Chanussot, Gemine Vivone <br>
  *IEEE Transactions on Image Processing* (<b>TIP</b>), 2023. [[PDF](https://zhongchengwu.github.io/papers/lrtcfpan_tip2023.pdf)] [[Code](https://github.com/zhongchengwu/code_LRTCFPan)]

- [Tensor Wheel Decomposition and Its Tensor Completion Application](https://papers.nips.cc/paper_files/paper/2022/hash/acbfe708197ff78ad04cc1beb1710979-Abstract-Conference.html) <br>
  <b>Zhong-Cheng Wu</b>, Ting-Zhu Huang\*, Liang-Jian Deng\*, Hong-Xia Dou, Deyu Meng <br>
  *Advances in Neural Information Processing Systems* (<b>NeurIPS</b>), 2022. [[PDF](https://zhongchengwu.github.io/papers/neurips_2022.pdf)] [[Appendix](https://zhongchengwu.github.io/papers/neurips_2022_appendix.pdf)] [[Poster](https://zhongchengwu.github.io/papers/Poster_TWDec.pdf)] [[Slides](https://zhongchengwu.github.io/papers/Slides_TWDec.pdf)] [[Code](https://github.com/zhongchengwu/code_TWDec)]

- [VO+Net: An Adaptive Approach Using Variational Optimization and Deep Learning for Panchromatic Sharpening](https://ieeexplore.ieee.org/abstract/document/9387460) <br>
  <b>Zhong-Cheng Wu</b>, Ting-Zhu Huang\*, Liang-Jian Deng\*, Jin-Fan Hu, Gemine Vivone <br>
  *IEEE Transactions on Geoscience and Remote Sensing* (<b>TGRS</b>), 2021. [[Project](https://liangjiandeng.github.io/Projects_Res/VOFF_2021tgrs.html)] (<span style="color:red">ESI Highly Cited Paper</span>)

- [A New Variational Approach Based on Proximal Deep Injection and Gradient Intensity Similarity for Spatio-Spectral Image Fusion](https://ieeexplore.ieee.org/abstract/document/9220783) <br>
  <b>Zhong-Cheng Wu</b>, Ting-Zhu Huang\*, Liang-Jian Deng\*, Gemine Vivone, Jia-Qing Miao, Jin-Fan Hu, Xi-Le Zhao <br>
  *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing* (<b>JSTARS</b>), 2020. [[Project](https://liangjiandeng.github.io/Projects_Res/DMPIF_2020jstars.html)]

- [Variational Pansharpening Based on Coefficient Estimation with Nonlocal Regression](https://ieeexplore.ieee.org/abstract/document/10218368) <br>
  Jin-Liang Xiao, Ting-Zhu Huang\*, Liang-Jian Deng\*, <b>Zhong-Cheng Wu</b>, Xiao Wu, Gemine Vivone <br>
  *IEEE Transactions on Geoscience and Remote Sensing* (<b>TGRS</b>), 2023. [[Code](https://github.com/Jin-liangXiao/SFNLR)]

- [A Novel Spatial Fidelity with Learnable Nonlinear Mapping for Panchromatic Sharpening](https://ieeexplore.ieee.org/document/10097537) <br>
  Rui Wen, Liang-Jian Deng\*, <b>Zhong-Cheng Wu</b>, Xiao Wu,  Gemine Vivone <br>
  *IEEE Transactions on Geoscience and Remote Sensing* (<b>TGRS</b>), 2023. [[PDF](https://liangjiandeng.github.io/papers/2023/wen-tgrs2023.pdf)] [[Code](https://github.com/liangjiandeng/-LNM-PS)]

- [A New Context-Aware Details Injection Fidelity with Adaptive Coefficients Estimation for Variational Pansharpening](https://ieeexplore.ieee.org/document/9721243) <br>
  Jin-Liang Xiao, Ting-Zhu Huang\*, Liang-Jian Deng\*, <b>Zhong-Cheng Wu</b>, Gemine Vivone <br>
  *IEEE Transactions on Geoscience and Remote Sensing* (<b>TGRS</b>), 2022. [[PDF](https://liangjiandeng.github.io/papers/2022/xiao-tgrs2022.pdf)] [[Code](https://github.com/liangjiandeng/CDIF)]

- [An Iterative Approach for Image Fusion with Dynamic Gradient Sparsity and Anisotropic Spectral-Spatial Total Variation](https://link.springer.com/article/10.1007/s11760-021-02105-y) <br>
  Tian-Jing Zhang, Liang-Jian Deng\*, <b>Zhong-Cheng Wu</b>, Chao-Chao Zheng <br>
  *Signal, Image and Video Processing* (<b>SIVP</b>), 2022.

- [High-Order Tensor Low-Rank Approximation with Application in Color Video Recovery](https://www.spiedigitallibrary.org/journals/journal-of-electronic-imaging/volume-31/issue-4/043044/High-order-tensor-low-rank-approximation-with-application-in-color/10.1117/1.JEI.31.4.043044.short) <br>
  Zhihao Wang, Wenjin Qin, <b>Zhongcheng Wu</b>, Hailin Wang, Jianjun Wang\* <br>
  *Journal of Electronic Imaging* (<b>JEI</b>), 2022.

# 🛩 Educations
- *2021.09 - Present*: &nbsp;Ph.D., Mathematics, University of Electronic Science and Technology of China (UESTC), China
- *2019.09 - 2021.06*: &nbsp;M.S., Mathematics, University of Electronic Science and Technology of China (UESTC), China
- *2015.09 - 2019.06*: &nbsp;B.S., Information and Computing Science, Anhui University of Finance and Economics (AUFE), China

# 🎖 Honors and Awards
- National Scholarship, *2023*
- Outstanding Postgraduate, *2021* and *2023*
- Academic Scholarship, *2019*, *2021*, *2022*, and *2023*
- Special Postgraduate Scholarship of Science, *2021*
- Provincial Outstanding Graduate (Top 3%), *2019* 

# 🗺 Academic Activities

## Review Editor
- Frontiers in Remote Sensing, ...

## Reviewer
- Information Fusion, IEEE TGRS, IEEE GRSL, SPIE JEI, ...
