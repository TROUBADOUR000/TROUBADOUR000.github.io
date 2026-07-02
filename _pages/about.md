---
permalink: /
title: 
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

I am currently in the **first** year of my Master’s degree in Computer Science at [Tsinghua University](https://www.tsinghua.edu.cn/), under the mentorship of Prof. [Shu-Tao Xia](https://www.sigs.tsinghua.edu.cn/xst/main.htm). I work closely with Prof. [Tao Dai](https://cstaodai.com/) and Prof. [Dawei Cheng](http://cs1.tongji.edu.cn/~dawei/). Before that, I completed my undergraduate studies in Data Science at [Tongji University](https://www.tongji.edu.cn/), with a minor in Finance at [Fudan University](https://www.fudan.edu.cn/).

My research interests focus on:

- Time Series Forecasting
- QuantitativeTrading
- LLM Agents


## 📧 Concat

email: huyf0122[at]gmail[dot]com

## 🔥 News
- *2026.05*: &nbsp;🎉🎉 Two papers are accepted by KDD 2026! One research track and one workshop.
- *2026.05*: &nbsp;🎉🎉 One paper is accepted by ICML 2026!
- *2026.01*: &nbsp;🎉🎉 Two papers are accepted by ICLR 2026!
- *2025.10*: &nbsp;🎉🎉 One paper is accepted by ICAIF 2025 Workshop as best paper!
- *2025.05*: &nbsp;🎉🎉 Two papers are accepted by ICML 2025!
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by AAAI 2025!

## 📝 Selected Publications

Notes:（*）indicates the equal contributions.


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/TSAgent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

The Landscape of Agentic Time Series Systems: Architectures, Reliability, and Frontiers

**Yifan Hu**, Jie Yang, Xilin Dai, Wanxu Cai, Kuiye Ding, Yuante Li, Qinghua Liu, Enze Ma, Zhiyuan Qu, Yixin Wang, Binyan Xu, Kexin Zhang, Peiyuan Liu, Zhijian Xu, Guibin Zhang, Yujin Tang, Yanwei Yue, Kening Zheng, Chengze Li, Hanrong Zhang, Haoyan Xu, Naiqi Li, Tao Dai, Dawei Cheng, John Paparrizos, Kaize Ding, Tian Zhou, Qiang Xu, Shu-tao Xia, Shirui Pan, Philip S Yu

[ **Paper**](https://www.researchgate.net/publication/407030432_The_Landscape_of_Agentic_Time_Series_Systems_Architectures_Reliability_and_Frontiers)   [**Code**](https://github.com/TROUBADOUR000/Awesome-Agentic-Time-Series)  ![Stars](https://img.shields.io/github/stars/TROUBADOUR000/Awesome-Agentic-Time-Series)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD Workshop on ML in Finance</div><img src='images/FinMamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

FinMamba: Market-Aware Graph Enhanced Multi-Level Mamba for Stock Movement Prediction

**Yifan Hu**, Peiyuan Liu, Yuante Li, Dawei Cheng, Naiqi Li, Tao Dai, Jigang Bao, and Shu-Tao Xia

[ **Paper**](https://arxiv.org/pdf/2502.06707)   [**Code**](https://github.com/TROUBADOUR000/FinMamba)  ![Stars](https://img.shields.io/github/stars/TROUBADOUR000/FinMamba)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/TimeAlign.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Bridging Past and Future: Distribution-Aware Alignment for Time Series Forecasting

**Yifan Hu**, Jie Yang, Tian Zhou, Peiyuan Liu, Yujin Tang, Rong Jin, Liang Sun

[ **Paper**](https://openreview.net/pdf?id=pQzQfslqlD)   [**Code**](https://github.com/TROUBADOUR000/TimeAlign)  ![Stars](https://img.shields.io/github/stars/TROUBADOUR000/TimeAlign)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/AesR1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unlocking the Essence of Beauty: Advanced Aesthetic Reasoning with Relative-Absolute Policy Optimization

Boyang Liu\*, **Yifan Hu**\*, Senjie Jin, Shihan Dou, Gonglei Shi, Jie Shao, Tao Gui, Xuanjing Huang

[ **Paper**](https://openreview.net/pdf?id=or3ZukbrKw)   [**Code**](https://github.com/ssssmark/AesR1)  ![Stars](https://img.shields.io/github/stars/ssssmark/AesR1)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICAIFW Best Paper</div><img src='images/FinTSB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

FinTSB: A Comprehensive and Practical Benchmark for Financial Time Series Forecasting

**Yifan Hu**, Yuante Li, Peiyuan Liu, Yuxia Zhu, Naiqi Li, Tao Dai, Shu-tao Xia, Dawei Cheng, and Changjun Jiang

[ **Paper**](https://arxiv.org/pdf/2502.18834)   [**Code**](https://github.com/TongjiFinLab/FinTSB)  ![Stars](https://img.shields.io/github/stars/TongjiFinLab/FinTSB)  [Awesome-Papers](https://github.com/TongjiFinLab/awesome-time-series-forecasting) ![Stars](https://img.shields.io/github/stars/TongjiFinLab/awesome-time-series-forecasting)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML, 2025</div><img src='images/TimeFilter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TimeFilter: Patch-Specific Spatial-Temporal Graph Filtration for Time Series Forecasting

**Yifan Hu**, Guibin Zhang, Peiyuan Liu, Disen Lan, Naiqi Li, Dawei Cheng, Tao Dai, Shu-Tao Xia, and Shirui Pan

[ **Paper**](https://arxiv.org/pdf/2501.13041)   [**Code**](https://github.com/TROUBADOUR000/TimeFilter)  ![Stars](https://img.shields.io/github/stars/TROUBADOUR000/TimeFilter)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI, 2025</div><img src='images/AMD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Adaptive Multi-Scale Decomposition Framework for Time Series Forecasting

**Yifan Hu**, Peiyuan Liu, Peng Zhu, Dawei Cheng, and Tao Dai

[ **Paper**](https://arxiv.org/pdf/2406.03751)   [**Code**](https://github.com/TROUBADOUR000/AMD)  ![Stars](https://img.shields.io/github/stars/TROUBADOUR000/AMD)

</div>
</div>


## 📖 Educations

- *2025.09 - 2028.07 (expected)*, MSc in Computer Science, ![](images/tsinghua.png) **Tsinghua University**
- *2021.09 - 2025.06*, Bachelor in Data Science, ![](images/tongji.png) **Tongji University**
- *2022.09 - 2024.06*, Minor in Finance, ![](images/fudan.png) **Fudan University**




## 🏆 Awards

- *2025.06*: &nbsp;Outstanding Bachelor’s Degree Graduates at Tongji University.
- *2022*: &nbsp;National Scholarship during my bachelor studying.

## 🔗 Service

- Conference Reviewer
  - 2026: NeurIPS, ICML, ICLR, AAAI
  - 2027: AAAI
