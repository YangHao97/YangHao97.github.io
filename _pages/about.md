---
permalink: /
title: "Hao Yang Personal Homepage"
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
- *2025.08*: &nbsp;🎉🎉 Our paper "[Reshaping Representation Space to Balance the Safety and Over-rejection in Large Audio Language Models](https://arxiv.org/pdf/2505.19670)" has been accepted to EMNLP 2025. The code and dataset are coming soon at [here](https://github.com/YangHao97/RRS).
- *2025.07*: &nbsp;🎉🎉 Our paper "[Jigsaw Puzzles: Splitting Harmful Questions to Jailbreak Large Language Models in Multi-turn Interactions](https://openreview.net/pdf?id=zuNM3eoPVi)" has been accepted to COLM 2025.
- *2025.01*: &nbsp;📚📚 The repository for "[Audio Is the Achilles' Heel: Red Teaming Audio Large Multimodal Models](https://aclanthology.org/2025.naacl-long.470.pdf)" is available at [here](https://github.com/YangHao97/RedteamAudioLMMs). 
- *2025.01*: &nbsp;🎉🎉 Our paper "[Audio Is the Achilles' Heel: Red Teaming Audio Large Multimodal Models](https://aclanthology.org/2025.naacl-long.470.pdf)" has been accepted to NAACL 2025. 
- *2024.12*: &nbsp;📚📚 Our codes for "[Jigsaw Puzzles: Splitting Harmful Questions to Jailbreak Large Language Models in Multi-turn Interactions](https://openreview.net/pdf?id=zuNM3eoPVi)" are available at [here](https://github.com/YangHao97/JigSawPuzzles).
- *2024.11*: &nbsp;📚📚 Our speech-specific risk dataset is available at [here](https://github.com/YangHao97/speech_specific_risk).
- *2024.09*: &nbsp;🎉🎉 Our paper "[Towards Probing Speech-Specific Risks in Large Multimodal Models: A Taxonomy, Benchmark, and Insights](https://aclanthology.org/2024.emnlp-main.614.pdf)" has been accepted to EMNLP 2024.

# 📝 Publications 

- **[EMNLP 2025]** [Reshaping Representation Space to Balance the Safety and Over-rejection in Large Audio Language Models](https://arxiv.org/pdf/2505.19670)

  **Hao Yang**, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari

- **[NAACL 2025]** [Audio Is the Achilles' Heel: Red Teaming Audio Large Multimodal Models](https://aclanthology.org/2025.naacl-long.470.pdf)

  **Hao Yang**, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari

- **[COLM 2025]** [Jigsaw Puzzles: Splitting Harmful Questions to Jailbreak Large Language Models in Multi-turn Interactions](https://openreview.net/pdf?id=zuNM3eoPVi)

  **Hao Yang**, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari

- **[INTERSPEECH 2025]** [Continual Speech Learning with Fused Speech Features](https://www.isca-archive.org/interspeech_2025/wang25u_interspeech.pdf)

  Guitao Wang, Jinming Zhao, **Hao Yang**, Guilin Qi, Tongtong Wu, Gholamreza Haffari

- **[EMNLP 2024]** [Towards Probing Speech-Specific Risks in Large Multimodal Models: A Taxonomy, Benchmark, and Insights](https://aclanthology.org/2024.emnlp-main.614.pdf)

  **Hao Yang**, Lizhen Qu, Ehsan Shareghi, Gholamreza Haffari

- **[INTERSPEECH 2023]** [Investigating pre-trained audio encoders in the low-resource condition](https://www.isca-archive.org/interspeech_2023/yang23d_interspeech.pdf)

  **Hao Yang**, Jinming Zhao, Gholamreza Haffari, Ehsan Shareghi

- **[EMNLP 2022-Findings]** [Self-supervised rewiring of pre-trained speech encoders: Towards faster fine-tuning with less labels in speech processing](https://aclanthology.org/2022.findings-emnlp.141.pdf)

  **Hao Yang**, Jinming Zhao, Gholamreza Haffari, Ehsan Shareghi

- **[EMNLP 2022-Findings]** [RedApt: An Adaptor for wav2vec 2 Encoding: Faster and Smaller Speech Translation without Quality Compromise](https://aclanthology.org/2022.findings-emnlp.142.pdf)

  Jinming Zhao, **Hao Yang**, Gholamreza Haffari, Ehsan Shareghi

- **[INTERSPEECH 2022]** [M-adapter: Modality adaptation for end-to-end speech-to-text translation](https://www.isca-archive.org/interspeech_2022/zhao22g_interspeech.pdf)

  Jinming Zhao, **Hao Yang**, Ehsan Shareghi, Gholamreza Haffari

