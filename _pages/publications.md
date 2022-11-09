---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

---
[**A  Study of Modeling Rising Intonation in Cantonese Neural Speech Synthesis**](https://www.isca-speech.org/archive/pdfs/interspeech_2022/bai22c_interspeech.pdf) \\
**Qibing Bai**, Tom Ko, Yu Zhang. \\
Interspeech, 2022.

**[LightHuBERT: Lightweight and Configurable Speech RepresentationLearning with Once-for-All Hidden-Unit BERT](https://www.isca-speech.org/archive/pdfs/interspeech_2022/wang22t_interspeech.pdf)** \\
\*Rui Wang, **\*Qibing Bai**, Junyi Ao, Long Zhou, Zhixiang Xiong, Zhihua Wei, Yu Zhang, Tom Ko, Haizhou Li. \\
Interspeech, 2022.

[**Leveraging Pseudo-labeled Data to Improve Direct Speech-to-Speech Translation**](https://www.isca-speech.org/archive/pdfs/interspeech_2022/dong22b_interspeech.pdf) \\
Qianqian Dong, Fengpeng Yue, Tom Ko, Mingxuan Wang, **Qibing Bai**, Yu Zhang. \\
Interspeech, 2022.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
