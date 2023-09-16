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

I am a fifth-year Ph.D. student in the College of Information Science & Electronic Engineering (ISEE) at [Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China, where I am jointly advised by Prof. [Zhiguo Shi](https://person.zju.edu.cn/shizg) (Vice dean of the College of ISEE), Prof. Quan Yu (Academician of the Chinese Academy of Engineering), and Prof. Chengwei Zhou. From Oct. 2022 ~ Oct. 2023, I was a joint training Ph.D. student in the Department of Acoustics & Signal Processing at [Aalto University](https://www.aalto.fi/en), Espoo, Finland, where I am supervised by Prof. [Sergiy Vorobyov](https://users.aalto.fi/~vorobys1/) (IEEE Fellow). 


My research interest includes array signal processing, tensor signal processing, and AI for signal processing. To overcome the challenge of large-scale high-dimensional array signal processing, I develop the theories of sub-Nyquist tensor processing, efficient tensor optimization, and resource-efficient tensorized neural networks. The proposed methods facilitate direction-of-arrival (DOA) estimation, adaptive beamforming, and channel estimation with low system costs and competitive performance, laying foundations for wireless communication, target localization, and anti-interference.

I have published more than 20 papers at top journals and international conferences with google citations <a href='https://scholar.google.com/citations?user=s7AazQUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 📝 Publications 

**Journal papers**

- **H. Zheng**, C. Zhou, Z. Shi, Y. Gu, and Y. D. Zhang, "[Coarray tensor direction-of-arrival estimation](https://ieeexplore.ieee.org/document/10078271)," IEEE Trans. Signal Process., vol. 71, pp. 1128-1142, 2023. 

- **H. Zheng**, C. Zhou, Z. Shi, and G. Liao, "[Sub-Nyquist tensor beamformer: A coprimality constrained design](https://ieeexplore.ieee.org/abstract/document/10232921)," IEEE Trans. Signal Process., 2023.

- **H. Zheng**, Z. Shi, C. Zhou, and A. L. F. de Almeida, "[Coarray tensor completion for DOA estimation](https://ieeexplore.ieee.org/document/10087326)," IEEE Trans. Aerosp. Electron. Syst., Mar. 2023. 

- **H. Zheng**, C. Zhou, S. Vorobyov, Q. Wang, and Z. Shi, "Decomposed CNN for sub-Nyquist tensor-based 2-D DOA estimation," IEEE Signal Process. Lett., vol. 30, pp. 708-712, 2023.

- **H. Zheng**, C. Zhou, Z. Shi, and A. L. F. de Almeida, "SubTTD: DOA estimation via sub-Nyquist tensor train decomposition," IEEE Signal Process. Lett., vol. 29, pp. 1978-1982, 2022.

- **H. Zheng**, C. Zhou, Z. Shi, and Y. Gu, "Structured tensor reconstruction for coherent DOA estimation," IEEE Signal Process. Lett., vol. 29, pp. 1634-1638, 2022.

- **H. Zheng**, Z. Shi, C. Zhou, M. Haardt, and J. Chen, "Coupled coarray tensor CPD for DOA estimation with coprime L-shaped array," IEEE Signal Process. Lett., vol. 28, pp. 1545-1549, July 2021.

- **H. Zheng**, C. Zhou, Y. Wang, and Z. Shi, "Tensor beamforming for EMVS coprime planar array," Journal of Signal Processing, Accepted. (in Chinese)

- L. Lin, **H. Zheng**, C. Zhou, S. He, and Z. Shi, "Nonorthogonal waveform assisted DOA estimation for joint MIMO sensing and communication," EURASIP J. Adv. Signal Process., vol. 2023, no. 1, Art. no. 22, Feb. 2023.

- C. Zhou, **H. Zheng**, Y. Gu, Y. Wang, and Z. Shi, "Research progress on coprime array signal processing: Direction-of-arrival estimation and adaptive beamforming," Journal of Radars, vol. 8, no. 5, pp. 558-577, Oct. 2019. (in Chinese)

-  B. Li, F. Cheng, **H. Zheng**, Z. Shi, and C. Zhou, "Structural-missing tensor completion for robust DOA estimation with sensor failure," IET Signal Process., Minor revision. (*corresponding author)

-  **H. Zheng**, Z. Shi, C. Zhou, S. A. Vorobyov, and Y. Gu, "Deep tensor 2-D DOA estimation for URA," IEEE Trans. Signal Process., Under review.

-  F. Xu, **H. Zheng**, and S. A. Vorobyov, "Tensor-based 2D DOA estimation for L-shaped nested array," IEEE Trans. Aerosp. Electron. Syst., Major revision.

**Conference papers**

- **H. Zheng**, C. Zhou, Y. Gu, and Z. Shi, "Two-dimensional DOA estimation for coprime planar array: A coarray tensor-based solution," in Proc. IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Barcelona, Spain, May 2020, pp. 4562-4566.

- **H. Zheng**, C. Zhou, Y. Wang, and Z. Shi, "2-D DOA estimation for coprime cubic array: A cross-correlation tensor perspective," in Proc. Int. Symp. Antennas & Propag. (ISAP), Osaka, Japan, Jan. 2021, pp. 447-448. <font color=red>(Best Paper Award)</font>

-  **H. Zheng**, C. Zhou, Y. Wang, J. Zhou, and Z. Shi, "Sample fourth-order cumulant tensor denoising for DOA estimation with coprime L-shaped array," in Proc. Asilomar Conf. Signals, Syst., Comput., Pacific Grove, CA, Nov. 2021, pp. 1668-1672.

-  **H. Zheng**, C. Zhou, Z. Shi, and C. Yan, "Joint coprime weights optimization for sub-Nyquist tensor beamforming," in Proc. IEEE Radar Conf., New York, USA, Mar. 2022, pp. 1-6.

-  **H. Zheng**, C. Zhou, A. L. F. de Almeida, Y. Gu, and Z. Shi, "DOA estimation via coarray tensor completion with missing slices," in Proc. IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Singapore, May 2022, pp. 5053-5057.

-  **H. Zheng**, C. Zhou, S. A. Vorobyov, and Z. Shi, "Tensorized neural layer decomposition for 2-D DOA estimation," in Proc. IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Rhodes Island, Greece, June 2023. <font color=red>(Top 3% paper of all accepted papers)</font>

- **郑航**, 周成伟, 王勇, 史治国, "面向电磁矢量互质面阵的张量波束成形", 第十五届全国雷达学术年会, 广州, 中国, 2020 年 12 月, pp. 285-293.

- Y. Wang, **H. Zheng**, C. Zhou, C. Yan, and Z. Shi, "Joint DOD and DOA estimation via coupled CPD with sparse MIMO radar for IIoT," in Proc. CIE Int. Conf. Radar, Haikou, China, Dec. 2021, pp. 1566-1570.

- F. Cheng, **H. Zheng**, Z. Shi, and C. Zhou, "Fiber-missing tensor completion for DOA estimation with sensor failure," in Proc. Int. Conf. Autonomous Unmanned Systems, Xian, China, Sep. 2022, pp. 3457-3466. <font color=red>(Best Paper Award)</font>

- L. Lin, Z. Zhang, **H. Zheng**, C. Zhou, and Z. Shi, "DOA estimation for joint sensing and communication with nonorthogonal waveform," in Proc. Asilomar Conf. Signals, Syst., Comput., Pacific Grove, CA, Nov. 2022, pp. 298-302.

- L. Lin, **H. Zheng**, C. Zhou, and Z. Shi, "Channel covariance matrix construction for DOA estimation with limited communication symbols," in Proc. IEEE Radar Conf., TX, USA, May 2023, pp. 1-5.

- C. He, **H. Zheng**, B. Li, C. Zhou, and Z. Shi, "DOA estimation via meta-learning under array sensor failures," Int. Conf. Radar, Sydney, Australia, Nov. 2023, Accepted.

- F. Cheng, **H. Zheng**, Z. Shi, and C. Zhou, "Tensorial Hankel reconstruction for coherent DOA estimation with sensor failure," IEEE Int. Conf. Commun. Technol. (ICCT), Wuxi, China, Oct. 2023, Accepted.

- L. Lin, **H. Zheng**, S. A. Vorobyov, C. Zhou, and Z. Shi, "Sensing-aided communication channel estimation with tensor-based moving target localization," IEEE Int. Conf. Acoust., Speech, Signal Process. (ICASSP), Seoul, Korea, Apr. 2024, Submitted.

# 🎖 Honors and Awards

- ISAP 2020 Best paper award
- ICAUS 2022 Best paper award
- ICASSP 2023 Top 3% of all accepted papers
- 《Journal of Radars》 2019 Highly cited paper
- Chu Kochen Scholarship (12 graduate students at Zhejiang University each year)
- Scholarship for ISEE Excellent Students
- Graduate of Merit, Award of Honor for Graduate
- Supported by the China Scholarship Council for joint training at Aalto university

# 📖 Educations
- *2019.09 - now*, **Ph.D. student**, College of Information Science & Electronic Engineering, Zhejiang University, Hangzhou, China
- *2022.10 - 2023.10*, **Joint training Ph.D. student**, Department of Acoustics & Signal Processing, Aalto University, Espoo, Finland
- *2015.09 - 2019.07*, **Bachelor**, College of Transportation Engineering, Tongji University, Shanghai, China

# 💬 Research Highlights

