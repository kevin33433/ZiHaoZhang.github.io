---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
## 2023
- L. Hu, G. Li*, A. Hu, and D.W.K.Ng, “Exploiting Malicious RIS for Secret Key Acquisition in Physical-layer Key Generation,” IEEE Wireless Commun. Lett., pp. 1–5, 2023.

- Y. Sun, G. Li*, H. Luo, Y. Xing, S. Dang and A. Hu, "Location-Invariant Radio Frequency Fingerprint for Base Station Recognition", IEEE Wireless Communications Letters, DOI:10.1109/LWC.2023.3283800, 2023.
  
- L. Hu, C. Sun, G. Li*, A. Hu, and D.W.K.Ng, Reconfigurable Intelligent Surface-aided Secret Key Generation in Multi-Cell Systems, accepted by IEEE Trans. on Comm., 2023.

- Q. Meng, G. Li, J. Shi, and A. Hu, " Enhancing RF Fingerprinting with a Simulated Attack Detection Strategy for Few Labeled Signals," 2023 IEEE 23rd International Conference on Communication Technology (ICCT), Wuxi, China, 2023.

- H. Sun, G. Li, H. Li, A. Hu, Y. Cheng, Y. Tian, and S. He, "A Physical-Layer Key Generation Scheme for Non-Square Channel Matrices Based on PMI," 2023 IEEE/CIC International Conference on Communications in China (ICCC), Dalian, China, 2023, pp. 1-6, doi: 10.1109/ICCC57788.2023.10233395.

- L. Hu, G. Li*, X. Qian, A. Hu and D. W. K. Ng, "Reconfigurable Intelligent Surface-Assisted Secret Key Generation in Spatially Correlated Channels," in IEEE Trans. on Wireless Comm., 2023, doi: 10.1109/TWC.2023.3296076.

- L. Yang, G. Li, T. Guo, H. Xu, and A. Hu, "Physical-layer Secret Key Generation for Dual-task Scenarios," China Communications.

- Z. Zhang, G. Li, J. Shi, H. Li and A. Hu, "Real-World Aircraft Recognition based on RF Fingerprinting with Few Labeled ADS-B Signals," in IEEE Transactions on Vehicular Technology, doi: 10.1109/TVT.2023.3314491.

- H. Li, G. Li et al., "RIS-Assisted Physical-Layer Key Generation with Discrete Phase Shift Optimization," in IEEE Vehicular Technology Conference (VTC) Workshop, Hong Kong, China, 2023.
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
