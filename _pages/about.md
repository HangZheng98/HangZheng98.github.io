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


On June 2024, I received the Ph.D. degree in the College of Information Science & Electronic Engineering (ISEE) at [Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China, where I am jointly advised by Prof. [Zhiguo Shi](https://person.zju.edu.cn/shizg) (Vice dean of the College of ISEE, IEEE Fellow), Prof. Quan Yu (Academician of the Chinese Academy of Engineering), and Prof. Chengwei Zhou. From Oct. 2022 to Oct. 2023, I was a joint training Ph.D. student in the Department of Acoustics & Signal Processing at [Aalto University](https://www.aalto.fi/en), Espoo, Finland, where I am supervised by Prof. [Sergiy Vorobyov](https://users.aalto.fi/~vorobys1/) (IEEE Fellow). 


My research interests include *Array Signal Processing*, *Tensor Signal Processing*, and *AI for Signal Processing*. I have been working on fundamental theories of <font color=blue>sub-Nyquist tensor signal processing</font>, <font color=blue>efficient tensor optimization</font>, <font color=blue>resource-efficient tensorized neural networks</font>, and their applications in <font color=blue>DOA Estimation</font>, <font color=blue>Adaptive Beamforming</font>, <font color=blue>ISAC Systems</font>. 


I have published 30+ papers at Top Journals and International Conferences with google citations <a href='https://scholar.google.com/citations?user=V97Yn3MAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 📖 Educations
- *2019.09 - 2024.06*, **Ph.D. student**, College of Information Science & Electronic Engineering, Zhejiang University, Hangzhou, China
- *2022.10 - 2023.10*, **Joint training Ph.D. student**, Department of Acoustics & Signal Processing, Aalto University, Espoo, Finland
- *2015.09 - 2019.07*, **Bachelor**, College of Transportation Engineering, Tongji University, Shanghai, China


# 🔥 News
- *2024.11*: &nbsp;🎉 Our paper [Coarray tensor direction-of-arrival estimation](https://ieeexplore.ieee.org/document/10078271) is recognized as an <font color=red>ESI Highly Cited Paper</font>.
- *2024.08*: &nbsp;🎉 Our paper [Deep tensor 2-D DOA estimation for URA](https://ieeexplore.ieee.org/document/10644148) is accepted to *IEEE Transactions on Signal Processing*
- *2023.11*: &nbsp;🎉 Our paper received the <font color=red>Excellent Scientific Papers</font> from *China Association for Science and Technology*
- *2023.08*: &nbsp;🎉 Our paper [Sub-Nyquist tensor beamformer: A coprimality constrained design](https://ieeexplore.ieee.org/abstract/document/10232921) is accepted to *IEEE Transactions on Signal Processing*
- *2023.06*: &nbsp;🎉 Our paper [Tensorized neural layer decomposition for 2-D DOA estimation](https://ieeexplore.ieee.org/abstract/document/10095288) is recognized as the <font color=red>Top 3% paper of all accepted papers</font> at *IEEE ICASSP 2023*
- *2023.03*: &nbsp;🎉 Our papers [Coarray tensor direction-of-arrival estimation](https://ieeexplore.ieee.org/document/10078271) and [Coarray tensor completion for DOA estimation](https://ieeexplore.ieee.org/document/10087326) are respectively accepted to *IEEE Transactions on Signal Processing* and *IEEE Transactions on Aerospace and Electronic Systems*

  
# 📝 Publications 

## **Journal papers**
- **H. Zheng**, Z. Shi, C. Zhou, S. A. Vorobyov, and Y. Gu, "[Deep tensor 2-D DOA estimation for URA](https://ieeexplore.ieee.org/document/10644148)," IEEE Trans. Signal Process., vol. 72, pp. 4065-4080, 2024.  

- **H. Zheng**, C. Zhou, Z. Shi, Y. Gu, and Y. D. Zhang, "[Coarray tensor direction-of-arrival estimation](https://ieeexplore.ieee.org/document/10078271)," IEEE Trans. Signal Process., vol. 71, pp. 1128-1142, 2023. <font color=red>(ESI Highly Cited Paper)</font>

- **H. Zheng**, C. Zhou, Z. Shi, and G. Liao, "[Sub-Nyquist tensor beamformer: A coprimality constrained design](https://ieeexplore.ieee.org/abstract/document/10232921)," IEEE Trans. Signal Process., vol. 71, pp. 4163-4177, 2023.

- **H. Zheng**, Z. Shi, C. Zhou, and A. L. F. de Almeida, "[Coarray tensor completion for DOA estimation](https://ieeexplore.ieee.org/document/10087326)," IEEE Trans. Aerosp. Electron. Syst., vol. 59, no. 5, pp. 5472-5486, Oct. 2023. 

- **H. Zheng**, C. Zhou, S. Vorobyov, Q. Wang, and Z. Shi, "[Decomposed CNN for sub-Nyquist tensor-based 2-D DOA estimation](https://ieeexplore.ieee.org/abstract/document/10144637)," IEEE Signal Process. Lett., vol. 30, pp. 708-712, 2023.

- **H. Zheng**, C. Zhou, Z. Shi, and A. L. F. de Almeida, "[SubTTD: DOA estimation via sub-Nyquist tensor train decomposition](https://ieeexplore.ieee.org/document/9872046)," IEEE Signal Process. Lett., vol. 29, pp. 1978-1982, 2022.

- **H. Zheng**, C. Zhou, Z. Shi, and Y. Gu, "[Structured tensor reconstruction for coherent DOA estimation](https://ieeexplore.ieee.org/abstract/document/9829909)," IEEE Signal Process. Lett., vol. 29, pp. 1634-1638, 2022.

- **H. Zheng**, Z. Shi, C. Zhou, M. Haardt, and J. Chen, "[Coupled coarray tensor CPD for DOA estimation with coprime L-shaped array](https://ieeexplore.ieee.org/document/9495264)," IEEE Signal Process. Lett., vol. 28, pp. 1545-1549, July 2021.

- L. Lin, J. Tong, H. Lin, **H. Zheng** and Z. Shi, "[Joint Target Localization and Channel Estimation for ODDM-ISAC Systems](https://ieeexplore.ieee.org/abstract/document/10930806)," IEEE Signal Processing Letters, 2025.
  
- Y. Yue, **H. Zheng**, Z. Shi and G. Liao, "[Two-stage Reconstruction for Co-array 2D DOA Estimation of Mixed Circular and Noncircular Signals](https://ieeexplore.ieee.org/abstract/document/10878439)," IEEE Transactions on Vehicular Technology, 2025.
  
- Y. Fan, Y. Wang, **H. Zheng** and Z. Shi, "[Video2mmPoint: Synthesizing mmWave Point Cloud Data from Videos for Gait Recognition](https://ieeexplore.ieee.org/abstract/document/10745215)," IEEE Sensors Journal, 2024.
  
- F. Xu, **H. Zheng**, and S. A. Vorobyov, "[Tensor-based 2D DOA estimation for L-shaped nested array](https://ieeexplore.ieee.org/document/10292874)," IEEE Trans. Aerosp. Electron. Syst., vol. 60, no. 1, pp. 604-618, 2024.

- L. Lin, **H. Zheng**, C. Zhou, S. He, and Z. Shi, "[Nonorthogonal waveform assisted DOA estimation for joint MIMO sensing and communication](https://asp-eurasipjournals.springeropen.com/articles/10.1186/s13634-023-00976-6)," EURASIP J. Adv. Signal Process., vol. 2023, no. 1, Art. no. 22, Feb. 2023.

- B. Li, F. Cheng, **H. Zheng** \*, Z. Shi, and C. Zhou, "[Structural-missing tensor completion for robust DOA estimation with sensor failure](https://www.mdpi.com/2076-3417/13/23/12740)," Appl. Sci., vol. 13, no. 23, Art. no. 12740, 2023. (\*corresponding author)


## **中文期刊论文**

- **郑航**, 史治国, 王勇, 周成伟, "[面向结构化稀疏感知的张量阵列信号处理](https://www.ejournal.org.cn/CN/10.12263/DZXB.20240504)," 《电子学报》, 2025.
  
- **郑航**, 周成伟, 王勇, 史治国, "[EMVS互质面阵张量波束成形](https://signal.ejournal.org.cn/cn/article/doi/10.16798/j.issn.1003-0530.2024.02.003),"《信号处理》, 40(2): 250-262, 2024.

- 周成伟, **郑航**, 顾宇杰, 王勇, 史治国, "[互质阵列信号处理研究进展：波达方向估计与自适应波束成形](https://radars.ac.cn/cn/article/doi/10.12000/JR19068)," 《雷达学报》, 8(5): 558-577, 2019.



## **Conference papers**

-  **H. Zheng**, C. Zhou, S. A. Vorobyov, and Z. Shi, "[Tensorized neural layer decomposition for 2-D DOA estimation](https://ieeexplore.ieee.org/document/10095288)," in Proc. IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Rhodes Island, Greece, June 2023. <font color=red>(Top 3% paper of all accepted papers)</font>

-  **H. Zheng**, C. Zhou, A. L. F. de Almeida, Y. Gu, and Z. Shi, "[DOA estimation via coarray tensor completion with missing slices](https://ieeexplore.ieee.org/document/9747012)," in Proc. IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Singapore, May 2022, pp. 5053-5057.

-  **H. Zheng**, C. Zhou, Z. Shi, and C. Yan, "[Joint coprime weights optimization for sub-Nyquist tensor beamforming](https://ieeexplore.ieee.org/document/9764278)," in Proc. IEEE Radar Conf., New York, USA, Mar. 2022, pp. 1-6.
  
- **H. Zheng**, C. Zhou, Y. Gu, and Z. Shi, "[Two-dimensional DOA estimation for coprime planar array: A coarray tensor-based solution](https://ieeexplore.ieee.org/document/9053860)," in Proc. IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Barcelona, Spain, May 2020, pp. 4562-4566.

-  **H. Zheng**, C. Zhou, Y. Wang, J. Zhou, and Z. Shi, "[Sample fourth-order cumulant tensor denoising for DOA estimation with coprime L-shaped array](https://ieeexplore.ieee.org/document/9723340)," in Proc. Asilomar Conf. Signals, Syst., Comput., Pacific Grove, CA, Nov. 2021, pp. 1668-1672.

- **H. Zheng**, C. Zhou, Y. Wang, and Z. Shi, "[2-D DOA estimation for coprime cubic array: A cross-correlation tensor perspective](https://ieeexplore.ieee.org/document/9391380)," in Proc. Int. Symp. Antennas & Propag. (ISAP), Osaka, Japan, Jan. 2021, pp. 447-448. <font color=red>(Best Paper Award)</font>

- Y. Wang, **H. Zheng**, C. Zhou, C. Yan, and Z. Shi, "[Joint DOD and DOA estimation via coupled CPD with sparse MIMO radar for IIoT](https://ieeexplore.ieee.org/document/10028145)," in Proc. CIE Int. Conf. Radar, Haikou, China, Dec. 2021, pp. 1566-1570.

- F. Cheng, **H. Zheng**, Z. Shi, and C. Zhou, "[Fiber-missing tensor completion for DOA estimation with sensor failure](https://link.springer.com/chapter/10.1007/978-981-99-0479-2_319)," in Proc. Int. Conf. Autonomous Unmanned Systems, Xian, China, Sep. 2022, pp. 3457-3466. <font color=red>(Best Paper Award)</font>

- L. Lin, Z. Zhang, **H. Zheng**, C. Zhou, and Z. Shi, "[DOA estimation for joint sensing and communication with nonorthogonal waveform](https://ieeexplore.ieee.org/document/10052043)," in Proc. Asilomar Conf. Signals, Syst., Comput., Pacific Grove, CA, Nov. 2022, pp. 298-302.

- L. Lin, **H. Zheng**, C. Zhou, and Z. Shi, "[Channel covariance matrix construction for DOA estimation with limited communication symbols](https://ieeexplore.ieee.org/document/10149637)," in Proc. IEEE Radar Conf., TX, USA, May 2023, pp. 1-5.

- C. He, **H. Zheng**, B. Li, C. Zhou, and Z. Shi, "[DOA estimation via meta-learning under array sensor failures](https://ieeexplore.ieee.org/document/10371100)," in Proc. Int. Conf. Radar, Sydney, Australia, Nov. 2023.

- F. Cheng, **H. Zheng**, Z. Shi, and C. Zhou, "[Tensorial Hankel reconstruction for coherent DOA estimation with sensor failure](https://ieeexplore.ieee.org/abstract/document/10419453)," in Proc. IEEE Int. Conf. Commun. Technol. (ICCT), Wuxi, China, Oct. 2023, pp. 221-225.

- L. Lin, **H. Zheng**, S. A. Vorobyov, C. Zhou, and Z. Shi, "[Sensing-aided communication channel estimation with tensor-based moving target localization](https://ieeexplore.ieee.org/abstract/document/10448481)," in Proc. IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Seoul, Korea, Apr. 2024, pp. 8606-8610.

- Y. Ren, **H. Zheng** and Z. Shi, "[Tensor-Based Subspace Fusion for Direct Position Determination](https://ieeexplore.ieee.org/abstract/document/10681969)," in Proc. IEEE/CIC International Conference on Communications in China (ICCC), Hangzhou, China, 2024, pp. 208-212.

- F. Qian, **H. Zheng**, C. Zhou and Z. Shi, "[Spatial Sectorized Neural Network for 2-D DOA Estimation in the Full Azimuth](https://ieeexplore.ieee.org/abstract/document/10715211)," in Proc. European Signal Processing Conference (EUSIPCO), Lyon, France, 2024, pp. 1147-1151.


# 📄 Patents
- **H. Zheng**, C. Zhou, Z. Shi, and J. Chen. Method for estimation direction of arrival of an L-type coprime array based on coupled tensor decomposition, US 12117545, 2024-10-15.
- C. Zhou, **H. Zheng**, J. Chen, Z. Shi. High resolution, accurate, two-dimensional direction-of-arrival estimation method based on coarray tensor spatial spectrum searching with coprime planar array, US 11300648, 2022-04-12. 
- Z. Shi, **H. Zheng**, C. Zhou, J. Chen. Two-dimensional direction-of-arrival estimation method for coprime planar array based on structured coarray tensor processing, US 11408960, 2022-08-09. 
- J. Chen, **H. Zheng**, Z. Shi, C. Zhou. Spatial spectrum estimation method with enhanced degree-of-freedom based on block sampling tensor construction for coprime planar array, US 11422177, 2022-08-23. 
- Z. Shi, **H. Zheng**, C. Zhou, J. Chen, Y. Wang. Three-dimensional co-prime cubic array direction-of-arrival estimation method based on a cross-correlation tensor, US 11879986, 2024-01-23. 
- 史治国, **郑航**, 周成伟, 陈积明, 王勇. 基于互相关张量的三维互质立方阵列波达方向估计方法, ZL 202110065604.4, 2022-02-18.
- **郑航**, 周成伟，颜成钢，陈剑，史治国，陈积明. 基于耦合张量分解的 L 型互质阵列波达方向估计方法, ZL 202110781692.8, 2022-03-22.
- **郑航**, 周成伟，颜成钢，史治国，王勇，陈积明. 基于结构化虚拟域张量信号处理的互质面阵二维波达方向估计方法, ZL 202010370072.0, 2022-09-20.
- **郑航**, 王勇，周成伟，颜成钢，史治国，陈积明. 基于平面互质阵列块采样张量信号构造的自由度增强型空间谱估计方法, ZL 202010370913.8, 2022-10-04.
- **郑航**, 周成伟，史治国, 王勇，陈积明. 基于平面互质阵列虚拟域张量空间谱搜索的高分辨精确二维波达方向估计方法, ZL 202010371305.9, 2022-12-27.
- **郑航**, 史治国, 陈积明, 颜成钢, 周成伟, 周金芳. 基于最小化准则的电磁矢量互质面阵张量功率谱估计方法, ZL 202011499625.9, 2023-06-27.
- 史治国, **郑航**, 陈积明, 颜成钢, 周成伟, 王勇. 基于乘性张量波束扫描的电磁矢量互质面阵多维参数估计方法, ZL 202011490509.0, 2023-06-27.
- 史治国, 陈剑锋, 单国锋, **郑航**. 一种自动探测测向无人机的方法, ZL 202010786192.9, 2023-07-07.
- J. Chen, Z. Shi, **H. Zheng**, C. Zhou. Composite tensor beamforming method for electromagnetic vector coprime planar array, US 11841448, 2023-12-12.


# 🎖 Honors and Awards
- *2025.01*: 中国电子教育学会优秀博士学位论文
- *2023.11*: Excellent Scientific Papers from China Association for Science and Technology（中国科协优秀科技论文） 
- *2023.06*: IEEE ICASSP 2023 Top 3% of all accepted papers
- *2022.09*: ICAUS 2022 Best paper award
- *2020.12*: IEICE ISAP 2020 Best paper award
- *2023.10*：National Scholarship for Graduate Excellence（研究生国家奖学金）
- *2021.12*: Chu Kochen Scholarship（浙江大学研究生竺可桢奖学金）
- *2023.05*, *2021.06*: 华为菁英奖学金
- 全国数学建模竞赛上海市一等奖, 全国二等奖
- "创青春"上海市大学生创业大赛创业计划类金奖
- "挑战杯"全国大学生创业大赛银奖
- "互联网+"大学生创新创业大赛上海市铜奖


# 💬 Research Highlights

## Sub-Nyquist tensor DOA estimation
<div class='paper-box'><div class='paper-box-image'><div><img src='images/DOA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
- Derive the high-order co-array tensor from sub-Nyquist tensor signals, and achieve co-array tensor-based direction-of-arrival estimation with *<font color=blue>high accuracy</font>*, *<font color=blue>super resolution</font>* and *<font color=blue>increased degrees-of-freedom</font>*
- Optimize the uniqueness condition of co-array tensor decomposition, and identify multiple sources that exceed the number of physical array sensors
- Complete the coarray tensor with missing slices to exploit the full co-array information

Analytical and numerical results are presented in our papers published in IEEE TSP, IEEE TAES, and IEEE ICASSP.
</div>
</div>

## Sub-Nyquist tensor beamforming
<div class='paper-box'><div class='paper-box-image'><div><img src='images/Beamforming.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Develop the principle of tensor signal filtering with sparse array, thereby enhancing the signal-of-interest with reduced system burden
- Enhance mainlobe while suppressing sidelobes in the beampattern by solving tensor beamformer weight optimization problems
- Improve output signal-to-interference-plus-noise ratio (SINR) for *<font color=blue>strong anti-interference</font>*

The algorithm for beamforming design and results are presented in our papers published on IEEE TSP and Radarconf.
</div>
</div>

## Tensorized neural networks for signal processing
<div class='paper-box'><div class='paper-box-image'><div><img src='images/TNN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Design tensorized neural networks to efficiently learn inherent features from multi-dimensional array signals, leading to *<font color=blue>robust performance in non-ideal situations</font>* such as low signal-to-noise (SNR) ratio and limited snapshots
- Highly compress the parameters in tensorized neural layers, and *<font color=blue>accelerate the training speed</font>* of the tensorized neural network

This work was presented at IEEE ICASSP 2023, and recognized as the Top 3% paper. The extended work is published on IEEE TSP.
