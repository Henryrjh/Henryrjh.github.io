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

<div style="text-align: right; margin-bottom: 20px;"><a href="{{ '/zh/' | relative_url }}" style="padding: 5px 10px; background-color: #eee; color: #333; border-radius: 5px; text-decoration: none; font-weight: bold;">🇨🇳 切换至纯中文版</a></div>

I am a Ph.D. student (Master-Doctor Combined Program) at the School of Electronic Information, Wuhan University (2020–present). My main research interests include super-resolution, multimodal matching, stereo matching, and deep learning(AI). Currently, I focus on 3D image reconstruction and explore solutions based on Large Language Models (LLMs).


# 🔥 News
- *2026.05*: &nbsp;🎉🎉 Our paper has been accepted to TGRS!
- *2026.01*: &nbsp;🎉🎉 Our paper has been accepted to ISPRS!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Satellite image stereo matching</div><img src='_pages/UA-SISM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Toward Reliable Disparity Estimation: Uncertainty-Aware Stereo Matching Framework for Satellite Images](https://ieeexplore.ieee.org/document/11494089)

**Jiahao Rao**; Rui Liu; Jun Chen; Xin Tian

IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2026, (**$\color{red}{\text{中科院 SCI 1区 TOP, IF=8.6}}$**) [Code](https://github.com/Henryrjh/UA-SISM)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Multi-modal image matching</div><img src='_pages/AMS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AMS-Former: Adaptive multi-scale transformer for multi-modal image matching](https://www.sciencedirect.com/science/article/pii/S0924271626000213)

**Jiahao Rao**; Rui Liu; Jianjun Guan; Xin Tian

ISPRS Journal of Photogrammetry and Remote Sensing (ISPRS), 2026 (**$\color{red}{\text{中科院 SCI 1区 TOP, IF=12.2}}$**) [Code](https://github.com/Henryrjh/AMS_Former)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Satellite image stereo matching</div><img src='_pages/TGRNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Texture-Guided Recurrent Network for Satellite Images Disparity Estimation](https://ieeexplore.ieee.org/abstract/document/11244831) 

**Jiahao Rao**; Rui Liu; Jun Chen; Xin Tian

IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (JSTARS), 2025 (**$\color{red}{\text{中科院 SCI 2区 TOP, IF=5.3}}$**) [Code](https://github.com/Henryrjh/TGRNet)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sonar blind image super-resolution</div><img src='_pages/DCRT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Various Degradation: Dual Cross-Refinement Transformer for Blind Sonar Image Super-Resolution](https://ieeexplore.ieee.org/abstract/document/10522780)

**Jiahao Rao**; Yini Peng; Jun Chen; Xin Tian

IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2024, (**$\color{red}{\text{中科院 SCI 1区 TOP, IF=8.6}}$**)
</div>
</div>

# 💡 Invention Patents

[1] [基于Faster R-CNN的电力线异物检测方法](https://kns.cnki.net/kcms2/article/abstract?v=j0ZbOfXgIAhxm55u-wufAxrXfEyR7_1V18h3Z1y9ebnHlVHtFJIOfOimY3tDU9qLTUqc5L-XjrJpE98XDsB_zABKDEMT_9QYO73F_rKNXDh2ie0DWY7rLGupG0xMfdZ-SnM2hwChZN8xMtfBqOH-H7KBWH7BNk2K4l5IufYmzckpoTDS4p_1GQ==&uniplatform=NZKPT&language=CHS)

[2] [一种基于双边生成对抗网络的线扫描图像超分辨率方法](https://kns.cnki.net/kcms2/article/abstract?v=j0ZbOfXgIAhy7MX8eELtC-RZVclPnXLvXqJC8iZcIe9iVZJLrFmwb9DmS5iZniNdsWVzXPsRgV_0tdTTgoqcz_sPfWMU3bisZYGRUJj37B6y1D_MfFZMJDsdbMvygKI646-O4rsXwFBrV14dPPn7-ipSrXZ--g5wxjgzfkcF9A1Qc4IerJltug==&uniplatform=NZKPT&language=CHS)

[3] [一种基于Transformer的合成孔径雷达图像盲超分辨率方法和装置](https://kns.cnki.net/kcms2/article/abstract?v=j0ZbOfXgIAgQiRhr5XBnOgUiEVt2ybpv3Fl-BEW2rRRAbv3JQZTPDcL0JEpxG-pltZxXsP9PcR4dG6WYI35dkXneoxyi0ri345UUkxovUXulWOnS4SK1aO5nkrfQDg-U5-fyB8-rwB6IGiLVbFFgsCAff9l7rvznhjSOOW_XSoOXesdcg84g3w==&uniplatform=NZKPT&language=CHS)

[4] [一种融合多维度自注意力的声呐图像盲超分辨率方法和设备](https://kns.cnki.net/kcms2/article/abstract?v=j0ZbOfXgIAjvMPuCoDqOt4iKgEfVNeFWF9OkvrodovB2zKurrqC9zoB8HTSLgY6AjoJkjnPPwnCmmGncTxkubqF1z47vFfZuUievtkJoLpXBnnph0S29IFrw06RugHcuj_ETYbE_f96EsqitlxfjW18ZfmeSZi9rZt3qEfrGjeLqmoKWT4fByw==&uniplatform=NZKPT&language=CHS)

[5] [一种基于多尺度几何编码和纹理解码的卫星图像视差估计方法](https://kns.cnki.net/kcms2/article/abstract?v=j0ZbOfXgIAh2HErXj62jWNe4rAcyHVN4lfoOB3TIpuPgufKbszvQbRlLmIV4STO_oqZkxygX_pt30tPNuItwTjzkcr0lHHTK5zk5ay7QSVBnWpovlzVAI43P7oI04rIkPqz27CnYhRL2JwRRJicrhLZMq2F2Gn3FNr6eEPjkay5iQ-o-5Ca2jw==&uniplatform=NZKPT&language=CHS)


# 🏆 Contest

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">数模</div><img src='/_pages/2022_math.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*2022* Second Prize in the 19th China Graduate Mathematical Contest in Modeling, “China Optics Valley · Huawei Cup” (*2022* "中国光谷_华为杯"第十九届中国研究生数学建模竞赛二等奖)

</div>
</div>


# 🎖 Honors

- *2024* — First-Class Academic Excellence Scholarship, Wuhan University (2024年武汉大学研究生一等优秀学业奖学金)

- *2022* — Second-Class Academic Excellence Scholarship, Wuhan University  (2022年武汉大学研究生二等优秀学业奖学金)

- *2021* — Runner-up in Men’s Doubles, Graduate Table Tennis Competition, Wuhan University  (2021年武汉大学研究生乒乓球比赛男双亚军)

- *2020* — Activist in Social Activities, Wuhan University  (2020年武汉大学社会活动积极分子)

- *2020* — Outstanding Graduate Student, Wuhan University  (2020年武汉大学优秀研究生)

- *2017* — Outstanding Student, Wuhan University  (2017年武汉大学优秀学生)

- *2017* — Outstanding Student Scholarship, Wuhan University  (2017年武汉大学优秀学生奖学金)

- *2016* — Freshman Scholarship for Undergraduate Students, Wuhan University  (2016年武汉大学本科新生奖学金)


# 📖 Educations
- *2020.06 - now*, School of Electronic Information, Wuhan University. (Master-Doctor Combined Program)
- *2016.09 - 2020.06*, School of Electronic Information, Wuhan University. (Undergraduate)
