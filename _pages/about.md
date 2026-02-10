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

I am **Zihan Wang**, an incoming **M.S. student at Tsinghua University (Sep. 2026)**.  
I received my B.Eng. in Computer Science and Technology from **Xi’an Jiaotong University** (GPA **3.97/4.30**, Rank **5/193**).

My research interests center on **NLP / Large Language Models**, with a focus on **alignment**, **tool-using agents**, and **reasoning**.  
More broadly, I am interested in building **intrinsically-motivated and self-improving agents**, especially for **code** and **scientific research** settings.

Contact: **zethive0225@gmail.com**  |  WeChat: **wishme25**  |  Phone: **(+86) 18223149213**  
You can find my publications and citation stats on  
<a href='https://scholar.google.com/citations?user=eToPcFsAAAAJ&hl=zh-CN'>Google Scholar <strong><span id='total_cit'></span></strong></a>
( badge: <a href='https://scholar.google.com/citations?user=eToPcFsAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> ).

---

# 🔥 News
- *2026.09*: 🎓 Incoming M.S. student at **Tsinghua University (Shenzhen)**.
- *2025*: 📌 **EMNLP 2025 (Main)** — *Alignment for Efficient Tool Calling of Large Language Models*.
- *2025*: 📌 **ICML 2025** — *Reducing Tool Hallucination via Reliability Alignment*.

---

# 🧭 Research Topics
- **Agent alignment for tool use**: cost-aware tool calling, knowledge boundary estimation, robust multi-turn function calling  
- **Reliability & hallucinations**: tool hallucination taxonomy, reliability-oriented post-training  
- **Reasoning & decision making**: improving long-horizon behaviors under verifiable signals  
- **AI for scientific research**: LLM agents for deep research workflows and automation

---

# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Alignment for Efficient Tool Calling of Large Language Models**  
Hongshen Xu*, **Zihan Wang***, Zichen Zhu, Lei Pan, Xingyu Chen, Lu Chen, Kai Yu

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2503.06708)</span>

<div class="badge">EMNLP 2025 (Main)</div>

- Proposes a **multi-objective alignment** framework combining **probabilistic knowledge boundary estimation** with **dynamic decision making** to reduce unnecessary tool calls while preserving performance.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Reducing Tool Hallucination via Reliability Alignment**  
Hongshen Xu, Su Zhu, **Zihan Wang**, Hang Zheng, Da Ma, Ruisheng Cao, Shuai Fan, Lu Chen, Kai Yu

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2412.04141)</span>

<div class="badge">ICML 2025</div>

- Defines and categorizes tool hallucinations (tool-selection vs tool-usage) and introduces **reliability alignment** to improve robust tool interaction and efficiency.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Memento: Fine-tuning LLM Agents without Fine-tuning LLMs**  
Huichi Zhou*, Yihang Chen*, Siyuan Guo, Xue Yan, Kin Hei Lee, **Zihan Wang**, Ka Yiu Lee, Guchun Zhang, Kun Shao, Linyi Yang†, Jun Wang†

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2508.16153) [\[Code\]](https://github.com/Agent-on-the-Fly/Memento)</span>

<div class="badge">Technical Report</div>

- A memory-based continual improvement framework enabling agents to learn from experience **without updating model weights**.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Delusions of Large Language Models**  
Hongshen Xu, Zixv Yang, Zichen Zhu, Kunyao Lan, **Zihan Wang**, Mengyue Wu, Ziwei Ji, Lu Chen, Pascale Fung, Kai Yu

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2503.06709)</spa
