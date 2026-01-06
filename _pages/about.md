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
I received my B.Eng. in Computer Science and Technology from **Xi'an Jiaotong University** (GPA **3.97/4.30**, Rank **5/193**).

My research focuses on **Large Language Models (LLMs)** and **NLP**, particularly **alignment**, **agents**, and **reasoning**.  
I also work on **data-centric approaches** (data selection, mixing, and synthesis) and recently explore **self-evolving agents** and **AI for scientific research**.

You can find my publications and citation stats on  
<a href='https://scholar.google.com/citations?user=eToPcFsAAAAJ&hl=zh-CN'>Google Scholar <strong><span id='total_cit'></span></strong></a>
( badge: <a href='https://scholar.google.com/citations?user=eToPcFsAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> ).

---

# 🔥 News
- *2026.09*: &nbsp;🎓 Incoming M.S. student at **Tsinghua University**.
- *2025*: &nbsp;📌 **EMNLP 2025 (Main)**: *Alignment for Efficient Tool Calling of Large Language Models*.
- *2025*: &nbsp;📌 **ICML 2025**: *Reducing Tool Hallucination via Reliability Alignment*.

---

# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Alignment for Efficient Tool Calling of Large Language Models**  
Hongshen Xu*, **Zihan Wang***, Zichen Zhu, Lei Pan, Xingyu Chen, Lu Chen, Kai Yu

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2503.06708)</span>

<div class="badge">EMNLP 2025 (Main)</div>

- Aligns tool calling with **knowledge boundaries** to improve efficiency and reduce unnecessary tool usage.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Reducing Tool Hallucination via Reliability Alignment**  
Hongshen Xu, Su Zhu, **Zihan Wang**, Hang Zheng, Da Ma, Ruisheng Cao, Shuai Fan, Lu Chen, Kai Yu

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2412.04141)</span>

<div class="badge">ICML 2025</div>

- Introduces **reliability-oriented alignment** to mitigate tool hallucinations and improve tool-use robustness.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Memento: Fine-tuning LLM Agents without Fine-tuning LLMs**  
Huichi Zhou*, Yihang Chen*, Siyuan Guo, Xue Yan, Kin Hei Lee, **Zihan Wang**, Ka Yiu Lee, Guchun Zhang, Kun Shao, Linyi Yang†, Jun Wang†

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2508.16153) [\[Code\]](https://github.com/Agent-on-the-Fly/Memento)</span>

<div class="badge">Technical Report</div>

- A memory-based continual-learning framework that enables LLM agents to improve from experience **without updating model weights**.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-text' markdown="1">

**Delusions of Large Language Models**  
Hongshen Xu, Zixv Yang, Zichen Zhu, Kunyao Lan, **Zihan Wang**, Mengyue Wu, Ziwei Ji, Lu Chen, Pascale Fung, Kai Yu

<span style="float:right">[\[ArXiv\]](https://arxiv.org/abs/2503.06709)</span>

<div class="badge">Manuscript / In Progress</div>

- Investigates high-confidence hallucination phenomena (“delusions”) and analyzes underlying causes and behaviors.
  </div>
</div>

---

# 🎖 Honors and Awards
- *2022–2023*: National Scholarship
- *2023–2024*: Finalist, Outstanding Award — American College Students Mathematical Modeling Competition
- *2023–2024*: Provincial First Prize — National College Students' Mathematical Competition
- *2023–2024*: Outstanding Volunteer Award
- *2024–2025*: Baidu Artificial Intelligence and Big Data Elite Class

---

# 📖 Education
- *Sep. 2026 (incoming)*, **Tsinghua University**, M.S.
- *Sep. 2022 – Jul. 2026*, **Xi'an Jiaotong University**, B.Eng. in Computer Science and Technology

---

# 💻 Research Experience (Selected)
- **CreativeBench: Benchmarking and Enhancing Machine Creativity via Self-Evolving Challenges** — First Author, *ACL 2026 (Under Review)*
- **LLM Pre-training: Data Selection & Mixing** — Engineering (Megatron-DeepSpeed; 100B tokens; multi-domain mixing/ordering)
