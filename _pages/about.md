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

I was born in Inner Mongolia, China. I received the B.Sc. degree in electronic science and technology from Shanghai University of Electric Power in 2017 and the M.Sc. degree in integrated circuit engineering from Shanghai Jiao Tong University in 2021. I am currently pursuing the Ph.D. degree in electronic science and technology with Tsinghua University. My research interest includes AI hardware accelerator and side-channel security.

<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
<span id="busuanzi_container_site_pv">This page has been visited <span id="busuanzi_value_site_pv"></span> times.</span>

<span class='anchor' id='-news'></span>

# 🔥 News
- *2025.08*: &nbsp;🎉 One poster on extracting neural network model outputs using the independently developed [CrackNuts](https://cracknuts.io/en/) board has been accepted for presentation at [CHES 2025](https://ches.iacr.org/2025/). See you in Kuala Lumpur!

- *2025.08*: &nbsp;🎉 Our paper on a self-attention hardware accelerator was accepted by [ASICON 2025](http://www.asicon.org/).

- *2025.08*: &nbsp;📢 Start new semester.

- *2025.07*: &nbsp;🎉 Our papers on NN and Transformer hardware implementations and SCA analysis were accepted by [ICICM 2025](https://icicm.net/index.html).

- *2025.06*: &nbsp;🎉 Our research project focusing on SCAs against edge hardware for large AI models has been successfully approved!

- *2025.05*: &nbsp;🎉 I passed the doctoral qualifying examination and officially became a PhD candidate!!!

- *2025.03*: &nbsp;🎉 One paper on attacking the DNN systolic array via side-channel star map has been published on IEEE TCAD!

- *2025.02*: &nbsp;🎉 One paper on attacking the DNN accelerator via 3D power surface has been accepted by [HOST 2025](http://www.hostsymposium.org/)! See you in San Jose!
  
- *2025.02*: &nbsp;📢 Start new semester.

- *2024.11*: &nbsp;🎉 I have been awarded the First-Class Comprehensive Scholarship of Tsinghua University.

- *2024.03*: &nbsp;🧑‍🏫 Teaching assistant of the Analog Electronic Technology.

<!--
# 📝 Publications

- `[C] IACR CHES` <span style="color:blue">**Le Wu**</span>, Liji Wu, Xiangmin Zhang, Yuyang Pan, and Jian Wu, "Cracking the AI Nut: From Output Extraction to Shuffling Countermeasure (Poster)" in 2025 IACR Cryptographic Hardware and Embedded Systems (CHES 2025).
- `[J] IEEE TCAD`  <span style="color:blue">**Le Wu**</span>, Liji Wu, Xiangmin Zhang, ["Catch the Star: Weight Recovery Attack using Side-Channel Star Map against DNN Accelerator,"](https://ieeexplore.ieee.org/document/10926892) in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (IEEE TCAD), Early Access, doi: 10.1109/TCAD.2025.3551652.
- `[C] IEEE HOST`  <span style="color:blue">**Le Wu**</span>, Liji Wu, Zhiwei Ba, Xiangmin Zhang, ["An Input Recovery Side-Channel Attack on DNN Accelerator with Three-Dimensional Power Surface,"](https://ieeexplore.ieee.org/document/11050042) in 2025 IEEE International Symposium on Hardware Oriented Security and Trust (HOST 2025), San Jose, CA, USA, 2025, pp. 1-11, doi: 10.1109/HOST64725.2025.11050042.
- `[J] IEEE TVLSI`  <span style="color:blue">**Le Wu**</span>, Liji Wu, Xiangmin Zhang, Munkhbaatar Chinbat, ["Dual-Rail Precharge Logic-Based Side-Channel Countermeasure for DNN Systolic Array,"](https://ieeexplore.ieee.org/document/10506805) in IEEE Transactions on Very Large Scale Integration (VLSI) Systems, Volume: 32, Issue: 9, September 2024, doi: 10.1109/TVLSI.2024.3387986.
- `[J] Microelectronics & Computer`  <span style="color:blue">**Le Wu**</span>， Wu Liu， Liang Hong，["Investigation on disturbance characteristics and test algorithm of SONOS embedded flash memory,"](https://kns.cnki.net/kcms2/article/abstract?v=JtACmXrF273jwcjBDv1I92Xd1thQe9fe1aeOnSir1m9c8G3OWmjCKEbK3IlHyklWeX2cCkuH8l7FYd6a64rVHvzYeP8r--oto5z5m593wFXpbuuRagUV_MKs4kIfhLLRabBkfY5Nu1RmuYj3T0FIDFaCxEE0cF_3G4ebnd-loZLzP864xlXmBBmcx37RlAHi&uniplatform=NZKPT&language=CHS) Microelectronics & Computer, 2021, 38(05), doi: 10.19304/j.cnki.issn1000-7180.2021.05.002. (In Chinese)
- `[C] IEEE ASICON` Zhenkun Li, Liji Wu, Yi Yang, Tianling Ren, <span style="color:blue">**Le Wu**</span>, and Xiangmin Zhang, "A 16×16 High-Utilization Systolic Array Hardware Accelerator for Long-Sequence Flash-Attention Computation in Transformer" in 2025 IEEE 16th International Conference on ASIC (ASICON 2025).
- `[C] IEEE ICICM` Runquan Shao, Liji Wu, Jing Hu, <span style="color:blue">**Le Wu**</span>, and Xiangmin Zhang, "Hardware Design and Side-Channel Security Analysis on the Key Computational Block for YOLOv11," in 2025 10th International Conference on Integrated Circuits and Microsystems (ICICM 2025).
- `[C] IEEE ICICM` Wentao Wang, Liji Wu, Jing Hu, <span style="color:blue">**Le Wu**</span>, and Xiangmin Zhang, "Hardware Implementation and Side-Channel Security Analysis for High-Precision AI Tansformer Encoder," in 2025 10th International Conference on Integrated Circuits and Microsystems (ICICM 2025).
- `[C] IEEE ICICM` Zhiwei Ba, Liji Wu, Jing Hu,  <span style="color:blue">**Le Wu**</span>, Xiangmin Zhang, ["Multi-Head Attention Hardware Implementation and Side-Channel Security Analysis for Transformer,"](https://ieeexplore.ieee.org/document/10814141) in 2024 9th International Conference on Integrated Circuits and Microsystems (ICICM 2024), doi: 10.1109/ICICM63644.2024.10814141.
- `[C] IEEE ASID` Yan Liu, Liji Wu, Zhenhui Zhang, Xiangmin Zhang, Jing Zhou, Yifan Yang,  <span style="color:blue">**Le Wu**</span>, [Hardware Design of PQC Classic McEliece Finite Field Operations and Encryption Module](https://ieeexplore.ieee.org/document/10426507) in IEEE 17th International Conference on Anti-counterfeiting, Security, and Identification (ASID 2023), 2023, pp. 67-71, doi: 10.1109/ASID60355.2023.10426507.
- `[C] IEEE ASID` Munkhbaatar Chinbat, Liji Wu, Xiangmin Zhang, Altantsooj Batsukh, Yifan Yang,  <span style="color:blue">**Le Wu**</span>, [Evaluating Side-Channel Attack Vulnerabilities in Post-Quantum CRYSTALS-Kyber Hardware Based on Simple Power Analysis](https://ieeexplore.ieee.org/document/10426450) in IEEE 17th International Conference on Anti-counterfeiting, Security, and Identification (ASID 2023), 2023, pp. 46-49, doi: 10.1109/ASID60355.2023.10426450.
-->
# 📝 Publications

## 2025
- ⭐️ `[C] IACR CHES` <span style="color:blue">**Le Wu**</span>, Liji Wu, Xiangmin Zhang, Yuyang Pan, and Jian Wu, "Cracking the AI Nut: From Output Extraction to Shuffling Countermeasure (Poster)" in 2025 IACR Cryptographic Hardware and Embedded Systems (CHES 2025).
  
- ⭐️ `[J] IEEE TCAD`  <span style="color:blue">**Le Wu**</span>, Liji Wu, Xiangmin Zhang, ["Catch the Star: Weight Recovery Attack using Side-Channel Star Map against DNN Accelerator,"](https://ieeexplore.ieee.org/document/10926892) in IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (IEEE TCAD), vol. 44, no. 10, pp. 3697-3709, Oct. 2025, doi: 10.1109/TCAD.2025.3551652.

- ⭐️ `[C] IEEE HOST`  <span style="color:blue">**Le Wu**</span>, Liji Wu, Zhiwei Ba, Xiangmin Zhang, ["An Input Recovery Side-Channel Attack on DNN Accelerator with Three-Dimensional Power Surface,"](https://ieeexplore.ieee.org/document/11050042) in 2025 IEEE International Symposium on Hardware Oriented Security and Trust (HOST 2025), San Jose, CA, USA, 2025, pp. 1-11, doi: 10.1109/HOST64725.2025.11050042.

- `[C] IEEE ASICON` Zhenkun Li, Liji Wu, Yi Yang, Tianling Ren, <span style="color:blue">**Le Wu**</span>, and Xiangmin Zhang, "A 16×16 High-Utilization Systolic Array Hardware Accelerator for Long-Sequence Flash-Attention Computation in Transformer" in 2025 IEEE 16th International Conference on ASIC (ASICON 2025).

- `[C] IEEE ICICM` Runquan Shao, Liji Wu, Jing Hu, <span style="color:blue">**Le Wu**</span>, and Xiangmin Zhang, "Hardware Design and Side-Channel Security Analysis on the Key Computational Block for YOLOv11," in 2025 10th International Conference on Integrated Circuits and Microsystems (ICICM 2025).
  
- `[C] IEEE ICICM` Wentao Wang, Liji Wu, Jing Hu, <span style="color:blue">**Le Wu**</span>, and Xiangmin Zhang, "Hardware Implementation and Side-Channel Security Analysis for High-Precision AI Tansformer Encoder," in 2025 10th International Conference on Integrated Circuits and Microsystems (ICICM 2025).

- `[C] Elsevier SMC-IoT` Yi Wu, Yuyang Pan, Jie Wang, Lihong Nai, <span style="color:blue">**Le Wu**</span>, Ruizhe Li, Yifan Yang, Ying Tan, Hong Yu, Liji Wu, Xiangmin Zhang, Liangsen Yu, and Yanzhao Li, "Modeling and Application of High-Stability, High-Performance Multi-Data Transceiver Mechanisms: A Case Study on Optimizing Signal Acquisition System Performance for Hardware Security," in the 4th International Conference on Sensing, Measurement, Communication and Internet of Things Technologies (SMC-IoT 2025)

## 2024
- ⭐️ `[J] IEEE TVLSI`  <span style="color:blue">**Le Wu**</span>, Liji Wu, Xiangmin Zhang, Munkhbaatar Chinbat, ["Dual-Rail Precharge Logic-Based Side-Channel Countermeasure for DNN Systolic Array,"](https://ieeexplore.ieee.org/document/10506805) in IEEE Transactions on Very Large Scale Integration (VLSI) Systems, Volume: 32, Issue: 9, September 2024, doi: 10.1109/TVLSI.2024.3387986.
  
- `[C] IEEE ICICM` Zhiwei Ba, Liji Wu, Jing Hu,  <span style="color:blue">**Le Wu**</span>, Xiangmin Zhang, ["Multi-Head Attention Hardware Implementation and Side-Channel Security Analysis for Transformer,"](https://ieeexplore.ieee.org/document/10814141) in 2024 9th International Conference on Integrated Circuits and Microsystems (ICICM 2024), doi: 10.1109/ICICM63644.2024.10814141.
  
## 2023
- `[C] IEEE ASID` Yan Liu, Liji Wu, Zhenhui Zhang, Xiangmin Zhang, Jing Zhou, Yifan Yang,  <span style="color:blue">**Le Wu**</span>, [Hardware Design of PQC Classic McEliece Finite Field Operations and Encryption Module](https://ieeexplore.ieee.org/document/10426507) in IEEE 17th International Conference on Anti-counterfeiting, Security, and Identification (ASID 2023), 2023, pp. 67-71, doi: 10.1109/ASID60355.2023.10426507.
  
- `[C] IEEE ASID` Munkhbaatar Chinbat, Liji Wu, Xiangmin Zhang, Altantsooj Batsukh, Yifan Yang,  <span style="color:blue">**Le Wu**</span>, [Evaluating Side-Channel Attack Vulnerabilities in Post-Quantum CRYSTALS-Kyber Hardware Based on Simple Power Analysis](https://ieeexplore.ieee.org/document/10426450) in IEEE 17th International Conference on Anti-counterfeiting, Security, and Identification (ASID 2023), 2023, pp. 46-49, doi: 10.1109/ASID60355.2023.10426450.

## 2021
- ⭐️ `[J] Microelectronics & Computer`  <span style="color:blue">**Le Wu**</span>， Wu Liu， Liang Hong，["Investigation on disturbance characteristics and test algorithm of SONOS embedded flash memory,"](https://kns.cnki.net/kcms2/article/abstract?v=JtACmXrF273jwcjBDv1I92Xd1thQe9fe1aeOnSir1m9c8G3OWmjCKEbK3IlHyklWeX2cCkuH8l7FYd6a64rVHvzYeP8r--oto5z5m593wFXpbuuRagUV_MKs4kIfhLLRabBkfY5Nu1RmuYj3T0FIDFaCxEE0cF_3G4ebnd-loZLzP864xlXmBBmcx37RlAHi&uniplatform=NZKPT&language=CHS) Microelectronics & Computer, 2021, 38(05), doi: 10.19304/j.cnki.issn1000-7180.2021.05.002. (In Chinese)


# 🎖 Honors and Awards
- *2024* First-Class Comprehensive Scholarship of Tsinghua University. 

# 📖 Educations
- *2022.09 - now*, the Ph.D. degree, electronic science and technology, Tsinghua University (THU), Beijing, China.
- *2018.09 - 2021.07*, the M.Sc. degree, integrated circuit engineering, Shanghai Jiao Tong University (SJTU), Shanghai, China.
- *2013.09 - 2017.07*, the B.Sc. degree, electronic science and technology, Shanghai University of Electric Power (SHIEP), Shanghai, China.
  
<span class='anchor' id='-projects'></span>
# 🛠️ Projects
- *2025.07 - now* Research on AI-assisted side-channel attack technology for edge-side large model hardware, the Initiative Scientific Research Program, School of Integrated Circuits, Tsinghua University
- *2022.09 - 2024.09* Research on AI Hardware Security and Side-Channel Attack Technology, the Initiative Scientific Research Program, School of Integrated Circuits, Tsinghua University
- *2019.09 - 2021.03* RISC-V based SONOS Flash testchip, tape-out with HLMC 55nm.


# 💻 Internships
- *2019.09 - 2021.03* Digital IC Design Engineer, Design Service Department (DS), Shanghai Huali Microelectronics Co.
