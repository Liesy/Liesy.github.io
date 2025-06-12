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

I am a second-year PhD student at the Media Synthesis and Forensics Lab (formerly known as Multimedia Computing Group), [Instutite of Computing Technology](http://www.ict.ac.cn/), [Chinese Academy of Sciences](http://www.cas.cn/), advised by professor [Juan Cao](https://scholar.google.com/citations?user=fSBdNg0AAAAJ) and assistant professor (researcher) [Qiang Sheng](https://sheng-qiang.github.io).

My research interest includes toxic content detection, jailbreaking, alignment, and fake news detection, in the era of large language models.

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=D09OAbQAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> -->

<a href='https://scholar.google.com/citations?user=D09OAbQAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News

- _2025.04_ &nbsp;🎉🎉 One co-author paper got accepted by SIGIR 2025.
- _2025.02_ &nbsp;🎉🎉 My scholar profile reached 100 citations!

# 📖 Educations

- _2023.09 - now_, PhD Candidate
  - Institute of Computing Technology, Chinese Academy of Sciences.
- _2019.09 - 2023.06_, Bachelor of Engineering
  - School of Computer Science and Technology, Shandong University.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/early-stop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Judgment to Interference: Early Stopping LLM Harmful Outputs via Streaming Content Monitoring](https://arxiv.org/abs/2506.09996)

<u><font size=4>Yang Li</font></u>, Qiang Sheng, Yehan Yang, Xueyao Zhang, Juan Cao

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- **Data:** We construct **FineHarm**, a dataset consisting of 29K prompt-response pairs with fine-grained annotations to provide reasonable supervision for token-level training.
- **Model:** we propose the **Streaming Content Monitor (SCM)**, which is trained with dual supervision of response- and token-level labels and can follow the output stream of LLM to make a timely judgment of harmfulness.
</div>
</div>

- \[**SIGIR 2025**\] [LLM-Generated Fake News Induces Truth Decay in News Ecosystem: A Case Study on Neural News Recommendation](https://arxiv.org/pdf/2504.20013)

  Beizhe Hu, Qiang Sheng, Juan Cao, <u><font size=4>Yang Li</font></u>, Danding Wang

- \[**AAAI 2024**\] [Bad Actor, Good Advisor: Exploring the Role of Large Language Models in Fake News Detection](https://github.com/ICTMCG/ARG)

  Beizhe Hu, Qiang Sheng, Juan Cao, Yuhui Shi, <u><font size=4>Yang Li</font></u>, Danding Wang, Peng Qi

- \[**Preprint**\] [For a More Comprehensive Evaluation of 6Dof Object Pose Tracking](https://arxiv.org/abs/2309.07796)

  <u><font size=4>Yang Li</font></u>, Fan Zhong, Xin Wang, Shuangbing Song, Jiachen Li, Xueying Qin, Changhe Tu

# 🎖 Honors and Awards

- _2025_ Merit Student, University of Chinese Academy of Sciences.
- _2024_ Second-Class Academic Scholarship, University of Chinese Academy of Sciences.
- _2023_ Freshman Scholarship of [E Fund](https://www.efunds.com.cn/index.shtml) Financial Technology.
- _2023_ First-Class Academic Scholarship, University of Chinese Academy of Sciences.
- _2022_ Second Prize of Shandong Province, China Undergraduate Mathematical Contest in Modeling.
- _2022_ Third-Class Academic Scholarship, Shandong University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📚 Academic Services

- _Conf. Reviewer/PC Member_
  - TheWebConf (WWW) 2025
