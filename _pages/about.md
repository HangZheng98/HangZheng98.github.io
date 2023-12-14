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

I am a fifth-year Ph.D. student in the College of Information Science & Electronic Engineering (ISEE) at [Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China, where I am jointly advised by Prof. [Zhiguo Shi](https://person.zju.edu.cn/shizg) (Vice dean of the College of ISEE), Prof. Quan Yu (Academician of the Chinese Academy of Engineering), and Prof. Chengwei Zhou. From Oct. 2022 to Oct. 2023, I was a joint training Ph.D. student in the Department of Acoustics & Signal Processing at [Aalto University](https://www.aalto.fi/en), Espoo, Finland, where I am supervised by Prof. [Sergiy Vorobyov](https://users.aalto.fi/~vorobys1/) (IEEE Fellow). 


My research interest includes *array signal processing*, *tensor signal processing*, and *AI for signal processing*. To effectively process large-scale high-dimensional array signals in future communication and sensing systems, I developed the theories of <font color=blue>sub-Nyquist tensor processing</font>, <font color=blue>efficient tensor optimization</font>, and <font color=blue>resource-efficient tensorized neural networks</font>. The proposed methods facilitate direction-of-arrival (DOA) estimation, adaptive beamforming, and channel estimation with low system costs and competitive performance, laying the foundations for wireless communication, target localization, and anti-interference.


I have published 20+ papers at top journals and international conferences with google citations <a href='https://scholar.google.com/citations?user=V97Yn3MAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

I am an active reviewer for IEEE TSP, IEEE TAES, IEEE TVT, IEEE SPL, Signal Processing, and IET Signal processing.

# 🔥 News
- *2023.08*: &nbsp;🎉 Our paper [Sub-Nyquist tensor beamformer: A coprimality constrained design](https://ieeexplore.ieee.org/abstract/document/10232921) is accepted to *IEEE Transactions on Signal Processing*
- *2023.06*: &nbsp;🎉 Our paper [Tensorized neural layer decomposition for 2-D DOA estimation](https://ieeexplore.ieee.org/abstract/document/10095288) is recognized as the [<font color=red>Top 3% paper of all accepted papers</font>](https://maifile.cn/est/a2816949397768/pdf) at *IEEE ICASSP 2023*
- *2023.03*: &nbsp;🎉 Our papers [Coarray tensor direction-of-arrival estimation](https://ieeexplore.ieee.org/document/10078271) and [Coarray tensor completion for DOA estimation](https://ieeexplore.ieee.org/document/10087326) are respectively accepted to *IEEE Transactions on Signal Processing* and *IEEE Transactions on Aerospace and Electronic Systems*

  
# 📝 Publications 

## **Journal papers**

- **H. Zheng**, C. Zhou, Z. Shi, Y. Gu, and Y. D. Zhang, "[Coarray tensor direction-of-arrival estimation](https://ieeexplore.ieee.org/document/10078271)," IEEE Trans. Signal Process., vol. 71, pp. 1128-1142, 2023. 

- **H. Zheng**, C. Zhou, Z. Shi, and G. Liao, "[Sub-Nyquist tensor beamformer: A coprimality constrained design](https://ieeexplore.ieee.org/abstract/document/10232921)," IEEE Trans. Signal Process., vol. 71, pp. 4163-4177, 2023.

- **H. Zheng**, Z. Shi, C. Zhou, and A. L. F. de Almeida, "[Coarray tensor completion for DOA estimation](https://ieeexplore.ieee.org/document/10087326)," IEEE Trans. Aerosp. Electron. Syst., vol. 59, no. 5, pp. 5472-5486, Oct. 2023. 

- **H. Zheng**, C. Zhou, S. Vorobyov, Q. Wang, and Z. Shi, "[Decomposed CNN for sub-Nyquist tensor-based 2-D DOA estimation](https://ieeexplore.ieee.org/abstract/document/10144637)," IEEE Signal Process. Lett., vol. 30, pp. 708-712, 2023.

- **H. Zheng**, C. Zhou, Z. Shi, and A. L. F. de Almeida, "[SubTTD: DOA estimation via sub-Nyquist tensor train decomposition](https://ieeexplore.ieee.org/document/9872046)," IEEE Signal Process. Lett., vol. 29, pp. 1978-1982, 2022.

- **H. Zheng**, C. Zhou, Z. Shi, and Y. Gu, "[Structured tensor reconstruction for coherent DOA estimation](https://ieeexplore.ieee.org/abstract/document/9829909)," IEEE Signal Process. Lett., vol. 29, pp. 1634-1638, 2022.

- **H. Zheng**, Z. Shi, C. Zhou, M. Haardt, and J. Chen, "[Coupled coarray tensor CPD for DOA estimation with coprime L-shaped array](https://ieeexplore.ieee.org/document/9495264)," IEEE Signal Process. Lett., vol. 28, pp. 1545-1549, July 2021.

- **H. Zheng**, C. Zhou, Y. Wang, and Z. Shi, "[Tensor beamforming for EMVS coprime planar array](https://kns.cnki.net/kcms2/article/abstract?v=18Spvz_s8rEj5ENd1JTL7jsgtrGVKFL1AImYgBDeTn23Vn479TU3qr0KoB1eTG3i5e9jlke9Yo_kxHaWEn92g21LL9zxJpT-T2XX9f_QWZ7q6quTRHRx0nLitKPpec9S7qQ5kGhSQ3Q=&uniplatform=NZKPT&language=CHS)," (EMVS互质面阵张量波束成形) Journal of Signal Processing (《信号处理》), 2023. (in Chinese)

-  F. Xu, **H. Zheng**, and S. A. Vorobyov, "[Tensor-based 2D DOA estimation for L-shaped nested array](https://ieeexplore.ieee.org/document/10292874)," IEEE Trans. Aerosp. Electron. Syst., 2023.

- L. Lin, **H. Zheng**, C. Zhou, S. He, and Z. Shi, "[Nonorthogonal waveform assisted DOA estimation for joint MIMO sensing and communication](https://asp-eurasipjournals.springeropen.com/articles/10.1186/s13634-023-00976-6)," EURASIP J. Adv. Signal Process., vol. 2023, no. 1, Art. no. 22, Feb. 2023.

- C. Zhou, **H. Zheng**, Y. Gu, Y. Wang, and Z. Shi, "[Research progress on coprime array signal processing: Direction-of-arrival estimation and adaptive beamforming](https://radars.ac.cn/cn/article/doi/10.12000/JR19068)," (互质阵列信号处理研究进展：波达方向估计与自适应波束成形) Journal of Radars (《雷达学报》), vol. 8, no. 5, pp. 558-577, Oct. 2019. (in Chinese)

-  B. Li, F. Cheng, **H. Zheng** \*, Z. Shi, and C. Zhou, "[Structural-missing tensor completion for robust DOA estimation with sensor failure](https://www.mdpi.com/2076-3417/13/23/12740)," Appl. Sci., 2023. (\*corresponding author)

-  **H. Zheng**, Z. Shi, C. Zhou, S. A. Vorobyov, and Y. Gu, "Deep tensor 2-D DOA estimation for URA," IEEE Trans. Signal Process., Under review.  

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

- C. He, **H. Zheng**, B. Li, C. Zhou, and Z. Shi, "DOA estimation via meta-learning under array sensor failures," Int. Conf. Radar, Sydney, Australia, Nov. 2023, Accepted.

- F. Cheng, **H. Zheng**, Z. Shi, and C. Zhou, "Tensorial Hankel reconstruction for coherent DOA estimation with sensor failure," IEEE Int. Conf. Commun. Technol. (ICCT), Wuxi, China, Oct. 2023, Accepted.

- L. Lin, **H. Zheng**, S. A. Vorobyov, C. Zhou, and Z. Shi, "Sensing-aided communication channel estimation with tensor-based moving target localization," IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Seoul, Korea, Apr. 2024, Accepted.

- **郑航**, 周成伟, 王勇, 史治国, "面向电磁矢量互质面阵的张量波束成形", 第十五届全国雷达学术年会, 广州, 中国, 2020 年 12 月, pp. 285-293.


# 📄 Patents
- C. Zhou, **H. Zheng**, J. Chen, Z. Shi. High resolution, accurate, two-dimensional direction-of-arrival estimation method based on coarray tensor spatial spectrum searching with coprime planar array, US 11300648, 2022-04-12. [American patent]
- Z. Shi, **H. Zheng**, C. Zhou, J. Chen. Two-dimensional direction-of-arrival estimation method for coprime planar array based on structured coarray tensor processing, US 11408960, 2022-08-09. [American patent]
- J. Chen, **H. Zheng**, Z. Shi, C. Zhou. Spatial spectrum estimation method with enhanced degree-of-freedom based on block sampling tensor construction for coprime planar array, US 11422177, 2022-08-23. [American patent]
- 史治国, **郑航**, 周成伟, 陈积明, 王勇. 基于互相关张量的三维互质立方阵列波达方向估计方法, ZL 202110065604.4, 2022-02-18. [Chinese patent]
- **郑航**, 周成伟，颜成钢，陈剑，史治国，陈积明. 基于耦合张量分解的 L 型互质阵列波达方向估计方法, ZL 202110781692.8, 2022-03-22. [Chinese patent]
- **郑航**, 周成伟，颜成钢，史治国，王勇，陈积明. 基于结构化虚拟域张量信号处理的互质面阵二维波达方向估计方法, ZL 202010370072.0, 2022-09-20. [Chinese patent]
- **郑航**, 王勇，周成伟，颜成钢，史治国，陈积明. 基于平面互质阵列块采样张量信号构造的自由度增强型空间谱估计方法, ZL 202010370913.8, 2022-10-04. [Chinese patent]
- **郑航**, 周成伟，史治国, 王勇，陈积明. 基于平面互质阵列虚拟域张量空间谱搜索的高分辨精确二维波达方向估计方法, ZL 202010371305.9, 2022-12-27. [Chinese patent]
- **郑航**, 史治国, 陈积明, 颜成钢, 周成伟, 周金芳. 基于最小化准则的电磁矢量互质面阵张量功率谱估计方法, ZL 202011499625.9, 2023-06-27. [Chinese patent]
- 史治国, **郑航**, 陈积明, 颜成钢, 周成伟, 王勇. 基于乘性张量波束扫描的电磁矢量互质面阵多维参数估计方法, ZL 202011490509.0, 2023-06-27. [Chinese patent]
- 史治国, 陈剑锋, 单国锋, **郑航**. 一种自动探测测向无人机的方法, ZL 202010786192.9, 2023-07-07. [Chinese patent]
- 史治国, **郑航**, 周成伟, 陈积明, 王勇. 相互相関テンソルに基づく三次元の互いに素のキュービックアレイの到来方向推定方法, JP 7327840, 2023-08-07. [Japanese patent]

# 🎖 Honors and Awards
- *2023.10*: 2023年“信息与通信工程学科”全国博士生论坛优秀口头报告
- *2023.10*：National Scholarship for Graduate Excellence / 研究生国家奖学金 
- *2023.08*: 第八届中国科协优秀科技论文 
- *2023.06*: [ICASSP 2023 Top 3% of all accepted papers](https://maifile.cn/est/a2816949397768/pdf)
- *2022.09*: [ICAUS 2022 Best paper award](https://maifile.cn/est/a3176949404664/pdf)
- *2020.12*: [ISAP 2020 Best paper award](https://maifile.cn/est/a3156949401013/pdf)
- *2022.12*: [《Journal of Radars》2019 Highly cited paper](https://maifile.cn/est/a2586949405559/pdf) /《雷达学报》2019年度高被引论文
- *2021.12*: [Chu Kochen Scholarship](https://maifile.cn/est/a2666949403508/pdf) (12 graduate students at Zhejiang University each year) / 竺可桢奖学金 (浙江大学研究生最高层次荣誉)
- *2021.12*: Scholarship for ISEE Excellent Students
- *2023.05*, *2021.06*: 2次获华为菁英奖学金
- Graduate of Merit, Award of Honor for Graduate
- Supported by the China Scholarship Council (CSC) for joint training at Aalto University
- 全国数学建模竞赛上海市一等奖, 全国二等奖
- "创青春"上海市大学生创业大赛创业计划类金奖
- "挑战杯"全国大学生创业大赛银奖
- "互联网+"大学生创新创业大赛上海市铜奖
- 壳牌汽车节能马拉松竞赛国际第二名, 最佳设计奖 (同济大学志远车队电控组组长)


# 📖 Educations
- *2019.09 - now*, **Ph.D. student**, College of Information Science & Electronic Engineering, Zhejiang University, Hangzhou, China
- *2022.10 - 2023.10*, **Joint training Ph.D. student**, Department of Acoustics & Signal Processing, Aalto University, Espoo, Finland
- *2015.09 - 2019.07*, **Bachelor**, College of Transportation Engineering, Tongji University, Shanghai, China

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

This work was presented at IEEE ICASSP 2023, and recognized as the Top 3% paper. The extended paper is submitted to IEEE TSP.
