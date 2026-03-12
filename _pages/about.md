---
permalink: /
title: "About me"
subtitle: "Honglin Lin (林泓霖)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %} {% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %} {% else %} {% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %} {% endif %} {% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a first-year Ph.D. student at [School of Artificial Intelligence, Shanghai Jiao Tong University (SAI, SJTU)](https://soai.sjtu.edu.cn/), jointly trained with [Shanghai AI Laboratory](https://www.shlab.org.cn/), supervised by [Dr. Lijun Wu](https://apeterswu.github.io/), [Dr. Conghui He](https://conghui.github.io/), and [Prof. Yanfeng Wang](https://cmic.sjtu.edu.cn/wangyanfeng/). I received my B.S. degree from [School of Artificial Intelligence, Beijing University of Posts and Telecommunications (BUPT)](https://ai.bupt.edu.cn/en/). I'm also a core contributor of [OpenDataArena](https://opendataarena.github.io/).
My research interests are mainly in LLMs, VLMs and Post-training.

# 🔥 News
- 2026.03: We release the data curation pipeline of [MMFineReason](https://mmfinereason.github.io/). Check out the [code](https://github.com/LHL3341/MMFineReason)!
- 2026.01: The [technical report](https://arxiv.org/abs/2601.21821) of [MMFineReason](https://mmfinereason.github.io/) is released. We close the multimodal reasoning gap via open data-centric methods. Our [datasets](https://huggingface.co/collections/OpenDataArena/mmfinereason) have got **20k+** downloads!
- 2025.12: The [technical report](https://arxiv.org/abs/2512.14051) of [OpenDataArena](https://opendataarena.github.io/) is released. Thanks to all collaborators!
- 2025.09: [Caco](https://neurips.cc/virtual/2025/loc/san-diego/poster/117205) is accepted by NeurIPS 2025! We scale code-assisted CoT and instruction data to enhance LLM reasoning.
- 2025.08: [MetaLadder](https://aclanthology.org/anthology-files/anthology-files/pdf/findings/2025.findings-emnlp.232.pdf) is accepted by EMNLP 2025! As a preliminary example of test-time scaling, we enhance math reasoning by transferring analogical-problem knowledge.
- 2025.08: We release [OpenDataArena](https://opendataarena.github.io/) – a fair, open, and transparent arena for data.
- 2025.07: We empirically explore the generalization of multi-domain reasoning data (math, code, puzzle) in RL. Check out [our report](https://arxiv.org/abs/2507.17512)!
- 2025.06: [CVG-Text](https://openaccess.thecvf.com/content/ICCV2025/papers/Ye_Where_am_I_Cross-View_Geo-localization_with_Natural_Language_Descriptions_ICCV_2025_paper.pdf) is accepted by ICCV 2025! We tackle cross-view geo-localization via multimodal alignment between images and natural language descriptions.
- 2025.05: Grateful to have several works accepted to ACL 2025: [MathFusion](https://arxiv.org/abs/2503.16212), [LEMMA](https://arxiv.org/abs/2503.17439), [CipherBank](https://aclanthology.org/2025.findings-acl.309/), [GRA](https://aclanthology.org/2025.acl-long.566/). These works all focus on data synthesis and reasoning in LLMs. Thanks to all collaborators!
- 2025.01: [LOKI](https://arxiv.org/abs/2410.09732) is accepted by ICLR 2025 Spotlight. Thanks to all collaborators!
- 2024.05: [ContextBLIP](https://aclanthology.org/2024.findings-acl.961) is accepted by Findings of ACL 2024! We propose doubly contextual alignment for contrastive image retrieval from complex descriptions.

# 📝 Publications

- `NeurIPS 2025` [Scaling Code-Assisted Chain-of-Thoughts and Instructions for Model Reasoning](https://neurips.cc/virtual/2025/loc/san-diego/poster/117205), **Honglin Lin**\*, Qizhi Pei*, Xin Gao, Zhuoshi Pan, Yu Li, Juntao Li, Conghui He, Lijun Wu†
- `EMNLP 2025` [MetaLadder: Ascending Mathematical Solution Quality via Analogical-Problem Reasoning Transfer](https://aclanthology.org/anthology-files/anthology-files/pdf/findings/2025.findings-emnlp.232.pdf), **Honglin Lin**, Zhuoshi Pan, Yu Li, Qizhi Pei, Xin Gao, Mengzhang Cai, Conghui He, Lijun Wu†
- `ICCV 2025` [Where am I? Cross-View Geo-localization with Natural Language Descriptions](https://openaccess.thecvf.com/content/ICCV2025/papers/Ye_Where_am_I_Cross-View_Geo-localization_with_Natural_Language_Descriptions_ICCV_2025_paper.pdf), Junyan Ye\*, **Honglin Lin**\*, Leyan Ou, Dairong Chen, Zihao Wang, Qi Zhu, Conghui He, Weijia Li†
- `ICLR 2025` [LOKI: A Comprehensive Synthetic Data Detection Benchmark using Large Multimodal Models](https://arxiv.org/abs/2410.09732), Junyan Ye, Baichuan Zhou, Zilong Huang, Junan Zhang, Tianyi Bai, Hengrui Kang, Jun He, **Honglin Lin**, Zihao Wang, Tong Wu, Zhizheng Wu, Yiping Chen, Dahua Lin, Conghui He, Weijia Li†
- `ACL 2024` [ContextBLIP: Doubly Contextual Alignment for Contrastive Image Retrieval from Linguistically Complex Descriptions](https://aclanthology.org/2024.findings-acl.961), **Honglin Lin**\*, Siyu Li*, Guoshun Nan†, Chaoyue Tang, Xueting Wang, Jingxin Xu, Rong Yankai, Zhouzhili Zhouzhili, Yutong Gao, Qimei Cui, Xiaofeng Tao
- `Tech Report` [MMFineReason: Closing the Multimodal Reasoning Gap via Open Data-Centric Methods](https://arxiv.org/abs/2601.21821), **Honglin Lin**\*, Zheng Liu*, Yun Zhu*, Chonghan Qin, Juekai Lin, Xiaoran Shang, Conghui He, Wentao Zhang, Lijun Wu†
- `Tech Report` [Can One Domain Help Others? A Data-Centric Study on Multi-Domain Reasoning via Reinforcement Learning](https://arxiv.org/abs/2507.17512), Yu Li\*, Zhuoshi Pan\*, **Honglin Lin**\*, Mengyuan Sun, Conghui He, Lijun Wu†
- `Tech Report` [OpenDataArena: A Fair and Open Arena for Benchmarking Post-Training Dataset Value](https://arxiv.org/abs/2512.14051), Mengzhang Cai, Xin Gao, Yu Li, **Honglin Lin**, Zheng Liu, Zhuoshi Pan, Qizhi Pei, Xiaoran Shang, Mengyuan Sun, Zinan Tang, Xiaoyang Wang, Zhanping Zhong, Yun Zhu, Dahua Lin, Conghui He, Lijun Wu†
- `Preprint` [Scientific Image Synthesis: Benchmarking, Methodologies, and Downstream Utility](https://arxiv.org/abs/2601.17027), **Honglin Lin**\*, Chonghan Qin*, Zheng Liu, Qizhi Pei, Yu Li, Zhanping Zhong, Xin Gao, Yanfeng Wang, Conghui He, Lijun Wu†
- `Preprint` [ChartVerse: Scaling Chart Reasoning via Reliable Programmatic Synthesis from Scratch](https://arxiv.org/abs/2601.13606), Zheng Liu\*, **Honglin Lin**\*, Chonghan Qin, Xiaoyang Wang, Xin Gao, Yu Li, Mengzhang Cai, Yun Zhu, Zhanping Zhong, Qizhi Pei, Zhuoshi Pan, Xiaoran Shang, Bin Cui, Conghui He, Wentao Zhang, Lijun Wu†
- `Preprint` [SciFlow-Bench: Evaluating Structure-Aware Scientific Diagram Generation via Inverse Parsing](https://arxiv.org/abs/2602.09809), Tong Zhang\*, **Honglin Lin**\*, Zhou Liu, Chong Chen, Wentao Zhang†


\* *Equal Contribution.* &ensp; † *Corresponding Author*

# 📖 Educations
- *2025.09 - Present*, Ph.D. student, [School of Artificial Intelligence, Shanghai Jiao Tong University (SAI, SJTU)](https://soai.sjtu.edu.cn/), jointly trained with [Shanghai AI Laboratory](https://www.shlab.org.cn/).
- *2021.09 - 2025.06*, B.S., [School of Artificial Intelligence, Beijing University of Posts and Telecommunications (BUPT)](https://ai.bupt.edu.cn/en/).

# 🎖 Honors and Awards
- 2nd place in Internal Reasoning Track of [CURE-Bench@NeurIPS2025](https://curebench.ai/), 2025
- Outstanding Undergraduate Awards of BUPT, 2025
- Undergraduate Student National Scholarship, 2022

# 💻 Internships
*2024.07 - Present*, [Shanghai Artificial Intelligent Laboratory](https://www.shlab.org.cn/), Shanghai, China