---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**[Hardening Password-Based Credential Databases"](https://doi.org/10.1109/TIFS.2023.3324326)**. Y. Song, C. Xu, Y. Zhang, and S. Li. IEEE Transactions on Information Forensics and Security, 2023.

**[HealthFort: A Cloud-Based eHealth System with Conditional Forward Transparency and Secure Provenance via Blockchain](https://doi.org/10.1109/TMC.2022.3199048)**. S. Li, Y. Zhang, C. Xu, Y. Song, N. Cheng, Z. Liu, Y. Du, and X. Shen. IEEE Transactions on Mobile Computing, 2022.

**[Badge: Blockchain-Assisted Secure Authenticated Data Transmission in Mobile Edge Computing](https://doi.org/10.1109/TMC.2022.3199048)**. S. Li, Y. Zhang, N. Cheng, and Y. Song. IEEE International Conference on Communications, 2022.

**[BESURE: Blockchain-Based Cloud-Assisted eHealth System with Secure Data Provenance](https://doi.org/10.1109/IWQOS52092.2021.9521289)**. S. Li, Y. Zhang, C. Xu, N. Cheng, Z. Liu, and X. Shen. IEEE/ACM International Symposium on Quality of Service, 2021.



## Manuscripts

**EpiOracle: Privacy-Preserving Cross-Facility Early Warning for Unknown Epidemics**.  S. Li, Y. Zhang, Y. Song, K. Yang, F. Wu, F. Lyu, and Q. Tang.

**Beyond Security: Achieving Fairness in Mailmen-Assisted Timed Data Delivery**. S. Li, Y. Zhang, Y. Song, H. Liu, N. Cheng, H. Li, and K. Yang.

**There Is Always a Way Out! Destruction-Resistant Key Management: Formal Definition and Practical Instantiation**. Y. Song, Y. Zhang, S. Li, W. Li, Z. Lai, and Q. Tang. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
