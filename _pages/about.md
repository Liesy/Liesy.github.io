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
{% assign url = gsDataBaseUrl | append: "main/_data/google_scholar/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. student at the Media Synthesis and Forensics Lab (formerly known as Multimedia Computing Group), [Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS)](http://www.ict.ac.cn/), advised by Professor [Juan Cao](https://scholar.google.com/citations?user=fSBdNg0AAAAJ) and Associate Professor [Qiang Sheng](https://sheng-qiang.github.io). Previously, I received my Bachelor's degree in Artificial Intelligence from [Shandong University](https://www.sdu.edu.cn/).

> My research interests focus on the integrity and safety of LLM-generated content, which is a critical challenge for building reliable and responsible AI systems.
>
> Currently, I am mainly working on **LLM-generated text detection**, with broader interests spanning fake news detection and harmful content moderation.
>
> Feel free to reach out if you are interested in academic collaboration or have any questions about my papers!

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=D09OAbQAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> -->

<a href='https://scholar.google.com/citations?user=D09OAbQAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=40A1FF&style=for-the-badge&label=citations" class="scholar-badge"></a>

# 🔥 News

- _May 2026_ &nbsp; One co-authored paper got accepted by ICML 2026.
- _Apr. 2026_ &nbsp;🎉 One first-authored paper and one co-authored paper got accepted by [ACL 2026](https://2026.aclweb.org/). See you in San Diego AGAIN!
- _Sep. 2025_ &nbsp;🎉 One first-authored paper got accepted by [NeurIPS 2025](https://neurips.cc/Conferences/2025). See you in [San Diego](https://maps.app.goo.gl/bY9UaC2EcsWQCy946)!
- _Aug. 2025_ &nbsp; One co-authored paper got accepted by EMNLP 2025 Findings.
- _Apr. 2025_ &nbsp; One co-authored paper got accepted by SIGIR 2025.
- _Feb. 2025_ &nbsp;🎉 My scholar profile reached 100 citations!
- _Dec. 2023_ &nbsp; One co-authored paper got accepted by AAAI 2024.

# 📖 Education

- _Sep. 2023 - Present_ Ph.D. Student in Computer Science
  - Institute of Computing Technology, Chinese Academy of Sciences.
  - Integrated Ph.D. Program _Expected graduation: Jun. 2028_
- _Sep. 2019 - Jun. 2023_ Bachelor of Engineering in Artificial Intelligence
  - School of Computer Science and Technology, Shandong University.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><div class="badge badge-oral">Oral</div><img src='images/race.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond the Final Actor: Modeling the Dual Roles of Creator and Editor for Fine-Grained LLM-Generated Text Detection](https://race.yang-li.cn/)

<u><font size=4>Yang Li</font></u>, Qiang Sheng, Zhengjia Wang, Yehan Yang, Danding Wang, Juan Cao

- **Focus:** We study the rigorous four-class fine-grained detection setting that explicitly distinguishes LLM-Polished Human Text and Humanized LLM Text.
- **Method:** We propose **RACE**, which combines RST-based creator logic modeling with EDU-level editor style modeling for fine-grained LLM-generated text detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/early-stop.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Judgment to Interference: Early Stopping LLM Harmful Outputs via Streaming Content Monitoring](https://scm.yang-li.cn/)

<u><font size=4>Yang Li</font></u>, Qiang Sheng, Yehan Yang, Xueyao Zhang, Juan Cao

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- **Data:** We construct **FineHarm**, a dataset consisting of 29K prompt-response pairs with fine-grained annotations to provide reasonable supervision for token-level training.
- **Model:** We propose the **Streaming Content Monitor (SCM)**, which is trained with dual supervision of response- and token-level labels and can follow the output stream of LLM to make a timely judgment of harmfulness.
</div>
</div>

- `ICML 2026` [FactGuard: Agentic Video Misinformation Detection via Reinforcement Learning](https://arxiv.org/abs/2602.22963)

  Zehao Li, Hongwei Yu, Hao Jiang, Qiang Sheng, Yilong Xu, Baolong Bi, <u><font size=4>Yang Li</font></u>, Zhenlong Yuan, Yujun Cai, Zhaoqi Wang

- `ACL 2026` `Oral` [Logical Consistency as a Bridge: Improving LLM Hallucination Detection via Label Constraint Modeling between Responses and Self-Judgments](https://summerrice.github.io/LaaB/)

  Hao Mi, Qiang Sheng, Shaofei Wang, Beizhe Hu, Yifan Sun, Zhengjia Wang, Hengqi Zeng, <u><font size=4>Yang Li</font></u>, Danding Wang, Juan Cao

- `EMNLP 2025 Findings` [Forewarned is Forearmed: Pre-Synthesizing Jailbreak-like Instructions to Enhance LLM Safety Guardrail to Potential Attacks](https://arxiv.org/abs/2508.20038)

  Sheng Liu, Qiang Sheng, Danding Wang, <u><font size=4>Yang Li</font></u>, Guang Yang, Juan Cao

- `SIGIR 2025` [LLM-Generated Fake News Induces Truth Decay in News Ecosystem: A Case Study on Neural News Recommendation](https://beanandrew.github.io/projects/TruthDecay)

  Beizhe Hu, Qiang Sheng, Juan Cao, <u><font size=4>Yang Li</font></u>, Danding Wang

- `AAAI 2024` [Bad Actor, Good Advisor: Exploring the Role of Large Language Models in Fake News Detection](https://github.com/ICTMCG/ARG)

  Beizhe Hu, Qiang Sheng, Juan Cao, Yuhui Shi, <u><font size=4>Yang Li</font></u>, Danding Wang, Peng Qi

- `Preprint` [For a More Comprehensive Evaluation of 6Dof Object Pose Tracking](https://arxiv.org/abs/2309.07796)

  <u><font size=4>Yang Li</font></u>, Fan Zhong, Xin Wang, Shuangbing Song, Jiachen Li, Xueying Qin, Changhe Tu

# 🎖 Honors and Awards

## Honors

- _May 2025_ Merit Student, University of Chinese Academy of Sciences.

## Scholarships

- _Dec. 2025_ Excellent Prize of the President Scholarship, ICT, CAS
- _Oct. 2025_ First-Class Academic Scholarship, University of Chinese Academy of Sciences.
- _Oct. 2024_ Second-Class Academic Scholarship, University of Chinese Academy of Sciences.
- _Dec. 2023_ [E Fund FinTech](https://www.efunds.com.cn/index.shtml) Entrance Scholarship.
- _Oct. 2023_ First-Class Academic Scholarship, University of Chinese Academy of Sciences.
- _Oct. 2022_ Third-Class Academic Scholarship, Shandong University.

## Other Awards

- _2022_ Second Prize of Shandong Province, China Undergraduate Mathematical Contest in Modeling.

# 💻 Open Source Projects

<div class="repo-card-container">
  <a href="https://github.com/Liesy/EasyMGTD" class="repo-card">
    <div class="repo-card-header">
      <span class="repo-name">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="currentColor"><path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"/></svg>
        EasyMGTD
      </span>
      <span class="repo-role-badge repo-role-author">Author</span>
    </div>
    <p class="repo-desc">An easy-to-use Python framework to run machine-generated-text-detection baselines.</p>
    <div class="repo-stats">
      <span class="repo-stat">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="currentColor"><path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Z"/></svg>
        <span id="stars-Liesy-EasyMGTD">–</span>
      </span>
    </div>
  </a>
  <a href="https://github.com/dinobot22/antigravity-ssh-proxy" class="repo-card">
    <div class="repo-card-header">
      <span class="repo-name">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="currentColor"><path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"/></svg>
        antigravity-ssh-proxy
      </span>
      <span class="repo-role-badge repo-role-contributor">Contributor</span>
    </div>
    <p class="repo-desc">SSH proxy extension for Antigravity. Routes remote server traffic to your local proxy via reverse tunneling—no root privileges required—restoring AI functionality on remote servers in restricted network environments.</p>
    <div class="repo-stats">
      <span class="repo-stat">
        <svg viewBox="0 0 16 16" width="16" height="16" fill="currentColor"><path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Z"/></svg>
        <span id="stars-dinobot22-antigravity-ssh-proxy">–</span>
      </span>
    </div>
  </a>
</div>

# 💬 Invited Talks

- _Nov. 12, 2025_ NeurIPS 2025 Pre-conference \| LLM Safety, Alignment and Trustworthy AI (NeurIPS 2025 预讲会 \| LLM 安全、对齐与可信 AI). \| [\[Video (Starts at 32:00)\]](https://www.bilibili.com/video/BV1NYUqBKEcX/?vd_source=f27763ddf5f3901a62791a68408fad7d)

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📚 Academic Services

- _Conf. Reviewer/PC Member_
  - TheWebConf (WWW) 2025
  - ACL Rolling Review (Oct. 2025)

<script>
// Mark selected inline code badges with dedicated classes
// so CSS can apply distinct backgrounds.
document.querySelectorAll('li code.highlighter-rouge').forEach(function(el) {
  const badgeText = el.textContent.trim();
  if (badgeText === 'Preprint') {
    el.classList.add('badge-preprint');
  }
  if (badgeText === 'Oral') {
    el.classList.add('badge-oral');
  }
});

// Fetch GitHub star counts for open source project cards.
// Elements with id="stars-{owner}-{repo}" are populated automatically.
document.querySelectorAll('[id^="stars-"]').forEach(function(el) {
  var parts = el.id.replace('stars-', '').split('-');
  var owner = parts.shift();
  var repo  = parts.join('-');
  fetch('https://api.github.com/repos/' + owner + '/' + repo)
    .then(function(r) { return r.json(); })
    .then(function(d) {
      if (typeof d.stargazers_count === 'number') {
        el.textContent = d.stargazers_count.toLocaleString();
      }
    })
    .catch(function() { /* keep placeholder on error */ });
});
</script>
