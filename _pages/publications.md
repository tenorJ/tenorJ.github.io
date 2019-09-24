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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Journal Papers**
* **L. Jiao**, N. Wang, P. Wang, A. Alipour-Fanid, J. Tang, K. Zeng, Physical Layer Key Generation in 5G Wireless Networks, to appear in IEEE Wireless Communications Magazine, 2019
* N. Wang, **L. Jiao**, A. Alipour-Fanid, M. Dabaghchian, K. Zeng, Pilot Contamination Attack Detection for NOMA in 5G Mm-Wave Massive MIMO Networks, IEEE Transactions on Information Forensics and Security, 2019
* N. Wang, P. Wang, A. Alipour-Fanid, **L. Jiao**, K. Zeng, Physical Layer Security of 5G Wireless Networks for IoT: Challenges and Opportunities, IEEE Internet of Things Journal, 2019


**Conference Papers**
* **L. Jiao**, N. Wang, and K. Zeng. "Secret Beam: Robust Secret Key Agreement for mmWave Massive MIMO 5G Communication." 2018 IEEE Global Communications Conference (GLOBECOM). IEEE, 2018.
* **L. Jiao**, J. Tang, and K. Zeng. "Physical Layer Key Generation Using Virtual AoA and AoD of mmWave Massive MIMO Channel." 2018 IEEE Conference on Communications and Network Security (CNS). IEEE, 2018.
* N. Wang, **L. Jiao**, K. Zeng. "Pilot Contamination Attack Detection for NOMA in Mm-Wave and Massive MIMO 5G Communication." 2018 IEEE Conference on Communications and Network Security (CNS). IEEE, 2018.
* J. Tang, **L. Jiao**, N. Wang, P. Wang, K. Zeng and H. Wen, "Mobility Improves NOMA Physical Layer Security," 2018 IEEE Global Communications Conference (GLOBECOM), Abu Dhabi, United Arab Emirates, 2018, pp. 1-6.
* N. Wang, **L. Jiao**, P. Wang, M. Dabaghchian and K. Zeng, "Efficient Identity Spoofing Attack Detection for IoT in mm-Wave and Massive MIMO 5G Communication," 2018 IEEE Global Communications Conference (GLOBECOM), Abu Dhabi, United Arab Emirates, 2018, pp. 1-6.
