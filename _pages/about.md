---
permalink: /
title: "123"
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

# 📖 Biography

I am a 2nd-year PhD student at the Department of Data Science & AI, Monash University (2023 - now), supervised by Prof. Gholamreza Haffari, Dr. Ehsan Shareghi and Dr. Lizhen Qu.

My research interest focuses on the safety issues on audio LMMs and speech-specific risks. We red team current audio LMMs to reveal potential vulnerabilities and explore effective safeguarding mechanism for constructing safer audio LMMs.


# 🔥 News
- *2025.01*: &nbsp;🎉🎉 Our paper "[Audio Is the Achilles' Heel: Red Teaming Audio Large Multimodal Models](https://arxiv.org/pdf/2410.23861)" has been accepted to NAACL 2025. 
- *2024.12*: &nbsp;📚📚 Our codes for "[Jigsaw Puzzles: Splitting Harmful Questions to Jailbreak Large Language Models](https://arxiv.org/pdf/2410.11459)" are available at [here](https://github.com/YangHao97/JigSawPuzzles). 

# 📝 Publications 

- [Audio Is the Achilles' Heel: Red Teaming Audio Large Multimodal Models](https://arxiv.org/pdf/2410.23861)

  Hao Yang, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari
  
  **NAACL 2025**

- [Jigsaw Puzzles: Splitting Harmful Questions to Jailbreak Large Language Models](https://arxiv.org/pdf/2410.11459)

  Hao Yang, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari

- [Towards Probing Speech-Specific Risks in Large Multimodal Models: A Taxonomy, Benchmark, and Insights](https://arxiv.org/pdf/2406.17430)

  Hao Yang, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari
  
  **EMNLP 2024**

- [Investigating pre-trained audio encoders in the low-resource condition](https://arxiv.org/pdf/2305.17733)

  Hao Yang, Jinming Zhao, Gholamreza Haffari, Ehsan Shareghi
  
  **INTERSPEECH 2023**

- [Self-supervised rewiring of pre-trained speech encoders: Towards faster fine-tuning with less labels in speech processing](https://arxiv.org/pdf/2210.13030)

  Hao Yang, Jinming Zhao, Gholamreza Haffari, Ehsan Shareghi
  
  **EMNLP 2022-Findings**

- [RedApt: An Adaptor for wav2vec 2 Encoding: Faster and Smaller Speech Translation without Quality Compromise](https://arxiv.org/pdf/2210.08475)

  Jinming Zhao, Hao Yang, Gholamreza Haffari, Ehsan Shareghi
  
  **EMNLP 2022-Findings**

- [M-adapter: Modality adaptation for end-to-end speech-to-text translation](https://arxiv.org/pdf/2207.00952)

  Jinming Zhao, Hao Yang, Ehsan Shareghi, Gholamreza Haffari
  
  **Interspeech 2022**

