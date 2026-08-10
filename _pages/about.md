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

# ✨ About Me

I am currently a first-year PhD student in system engineering at [CUHK](https://www.cuhk.edu.hk/) under the supervision of [Prof. Xixin Wu](https://www1.se.cuhk.edu.hk/~wuxx/). Previously, I received an MPhil AI degree from [HKUST](https://hkust.edu.hk/), under the supervision of [Prof. Li Liu](https://liliu-avril.github.io/) and the co-supervision of [Prof. Yi R. (May) Fung](https://mayrfung.github.io/), plus an MSc CS degree from [HKU](https://www.hku.hk/). Between the two master's studies, I worked as an RA at [ASTAPLE](https://www.astaple.com/) of [PolyU](https://www.polyu.edu.hk/) with [Prof. Haibo Hu](https://haibohu.org/). I got my BEng degree in software engineering at [ECNU](https://english.ecnu.edu.cn/), where I began my research career under the supervision of [Prof. Dehui Du](https://scholar.google.com/citations?user=9WHLtvoAAAAJ&hl=en&oi=ao). It is also my great pleasure to work with close co-authors [Zi Liang](https://liangzid.github.io/research.html) (PolyU), [Ziyu Zhou](https://zhouziyu02.github.io/) (HKUST), [Yu Huang](https://hardenyu21.github.io/) (CityU), [Weilin Lin](https://linweiii.github.io/) (HKUST(GZ)), and [Nanjun Zhou](https://quantum-bitss.github.io/) (ZJU).

My research interests include AI Security and Multimodal Large Language Models. Specifically, I used to study adversarial attacks and defenses across time series classification, image classification, and speech recognition. Together with close co-authors, I have also dabbled in model extraction, backdoor, data poisoning, agent security, etc. Recently, I have been interested in MLLM post-training and inference-time security, especially regarding safety alignment and modality gap under multimodal inputs. I would always be open to discussions and potential collaborations. Please feel free to email me!


# 🔥 News
- *2026.08*: Reported for duty at CUHK! Let's write the new story together ⭐
- *2026.07*: Graduated from HKUST(GZ)! My sincere thanks to everyone for all the help and support, especially to my respected supervisor, Prof. Liu. Will always miss the precious two years 😭
- *2026.07*: One paper benchmarking text-to-audio-video accepted by ACMMM'26 as Oral. Congratulations to Prof. Liu, Tianxin, and Wentao 🎉
- *2026.05*: One paper on universal jailbreak of audio language models accepted by ICML'26. Many thanks to Prof. Liu, Prof. Wu, Yu, and Zi 🎉
- *2026.03*: Been awarded the Lizhi Innovative Talent Scholarship! My great thanks to HKUST(GZ) Info Hub, Lizhi Group, and Prof. Liu 🙌
- *2026.03*: One paper on accuracy-robustness trade-off in adversarial training accepted by CVPR'26 as Findings. Many thanks to Prof. Hu, Prof. Liu, Prof. Ye, and Zi 🎉
- *2026.01*: One paper on adversarial fine-tuning of speech foundation models accepted by ICASSP'26 as Oral. Many thanks to Prof. Liu 🎉


# 📝 Publications 

## As 1st Author:

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1em;">ICML'26</div><img src='images/Image-ICML26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Acoustic Interference: A New Paradigm Weaponizing Acoustic Latent Semantic for Universal Jailbreak against Large Audio Language Models](https://openreview.net/forum?id=FygaF16KNo)

**<u>Yanyun Wang</u>**\*, Yu Huang\*, Zi Liang, Xixin Wu, Li Liu<sup>†</sup>

In *43rd International Conference on Machine Learning*, 2026.

[[Project Page](https://flaai.github.io/AIA_page/)] &nbsp;&nbsp; [[Slides](https://github.com/FlaAI/ywang/blob/main/files/Slides_ICML26.pptx)] &nbsp;&nbsp; [[Poster](https://github.com/FlaAI/ywang/blob/main/files/Poster_ICML26.pdf)] &nbsp;&nbsp; [[Code](https://github.com/FlaAI/AIA)]
</div>
</div>

## As Co-Author:

- **[Preprint]** <u>Adversarial Attacks on Deep OCR Systems</u>, Wenbo Sun, **<u>Yanyun Wang</u>**, Jiahao MA, Shuxin Zhuang, Rong Feng, Shiqin Tang, and Zi Liang<sup>†</sup>. 2026.

- **[Preprint]** [Can a Single Message Paralyze the AI Infrastructure? The Rise of AbO-DDoS Attacks through Targeted Mobius Injection](https://arxiv.org/abs/2605.11442), Zi Liang, Ronghua Li, **<u>Yanyun Wang</u>**, Qingqing Ye, and Haibo Hu<sup>†</sup>. *Arxiv Preprint*, 2026.

- **[ACMMM'26 Oral]** [PhyAVBench: A Challenging Audio Physics-Sensitivity Benchmark for Physically Grounded Text-to-Audio-Video Generation](https://arxiv.org/abs/2512.23994), Tianxin Xie, Wentao Lei, Kai Jiang, Guanjie Huang, Pengfei Zhang, Chunhui Zhang, Fengji Ma, Haoyu He, Han Zhang, Jiangshan He, Jinting Wang, Linghan Fang, Lufei Gao, Orkesh Ablet, Peihua Zhang, Ruolin Hu, Shengyu Li, Weilin Lin, Xiaoyang Feng, Xinyue Yang, Yan Rong, **<u>Yanyun Wang</u>**, Zihang Shao, Zelin Zhao, Chenxing Li, Shan Yang, Wenfu Wang, Meng Yu, Dong Yu, and Li Liu<sup>†</sup>. In *34th ACM International Conference on Multimedia*, 2026.

- **[AAAI'26]** [Revitalizing Canonical Pre-Alignment for Irregular Multivariate Time Series Forecasting](https://ojs.aaai.org/index.php/AAAI/article/view/40149), Ziyu Zhou, Yiming Huang, **<u>Yanyun Wang</u>**, Yuankai Wu, James Kwok, and Yuxuan Liang<sup>†</sup>. In *40th AAAI Conference on Artificial Intelligence*, 2026.

- **[NeurIPS'25 Spotlight]** [Virus Infection Attack on LLMs: Your Poisoning Can Spread "VIA" Synthetic Data](https://proceedings.neurips.cc/paper_files/paper/2025/hash/e6c5195dac675f03d0fcf3955bcdd3c9-Abstract-Conference.html), Zi Liang, Qingqing Ye, Xuan Liu, **<u>Yanyun Wang</u>**, Jianliang Xu, and Haibo Hu<sup>†</sup>. In *39th Annual Conference on Neural Information Processing Systems*, 2025.

- **[NeurIPS'25]** [BackdoorDM: A Comprehensive Benchmark for Backdoor Learning in Diffusion Model](https://proceedings.neurips.cc/paper_files/paper/2025/hash/ba9b181cd30b4f1819583be24fdfeb17-Abstract-Datasets_and_Benchmarks_Track.html), Weilin Lin, Nanjun Zhou, **<u>Yanyun Wang</u>**, Jianze Li, Hui Xiong, and Li Liu<sup>†</sup>. In *39th Annual Conference on Neural Information Processing Systems*, 2025.

- **[ACL'25 Main]** ["Yes, My LoRD." Guiding Language Model Extraction with Locality Reinforced Distillation](https://aclanthology.org/2025.acl-long.73/), Zi Liang, Qingqing Ye, **<u>Yanyun Wang</u>**, Sen Zhang, Yaxin Xiao, Ronghua Li, Jianliang Xu, and Haibo Hu<sup>†</sup>. In *63rd Annual Meeting of the Association for Computational Linguistics*, 2025.

- **[AAAI'22 Workshop]** [Efficient Adversarial Sequence Generation for RNN with Symbolic Weighted Finite Automata](https://ceur-ws.org/Vol-3087/paper_19.pdf), Mingjun Ma, Dehui Du<sup>†</sup>, Yuanhao Liu, **<u>Yanyun Wang</u>**, and Yiyang Li. In *SafeAI Workshop @ 36th AAAI Conference on Artificial Intelligence*, 2022.

# 📖 Educations
- *2026.08 - Now*, Ph.D. in System Engineering, The Chinese University of Hong Kong. 
- *2024.09 - 2026.07*, M.Phil. in Artificial Intelligence, The Hong Kong University of Science and Technology (Guangzhou).
- *2022.09 - 2023.10*, M.Sc. in Computer Science, The University of Hong Kong.
- *2018.09 - 2022.07*, B.Eng. in Software Engineering, East China Normal University.

# 💻 Internships
- *2026.06 - 2026.08*, LLM Research Intern, [Bairong Intelligence](https://www.brgroup.com/?locale=en), Beijing.
- *2026.03 - 2026.06*, MLLM Data Intern, [ByteDance Seed](https://seed.bytedance.com/en/), Beijing.
- *2023.10 - 2024.06*, Research Assistant, [Applied Security, Trust And Privacy Lab for Enterprise](https://www.astaple.com/), Hong Kong.
- *2021.08 - 2021.11*, NLP Algorithm Intern, [Ping An Technology](https://tech.pingan.com/), Shanghai.
- *2020.07 - 2020.08*, Software Development Intern, [Dareway Intelligent Technology](https://www.dareway.cn/#/), Jinan.

# 🎖 Honors and Awards
- *2026*, Postgraduate Studentship Award (48 months), The Chinese University of Hong Kong.
- *2026*, Lizhi Innovative Talent Scholarship, The Hong Kong University of Science and Technology (Guangzhou) & Lizhi Group.
- *2025*, Second-Class Award, The 15th Guangdong-Hong Kong-Macao Conference on Image and Graphics.
- *2024*, Postgraduate Studentship Award (24 months), The Hong Kong University of Science and Technology (Guangzhou).
- *2022*, Excellent Graduate Award, East China Normal University.
- *2022*, Excellent Bachelor's Degree Thesis Award, Software Engineering Institute, East China Normal University.
- *2021*, People’s Choice Award, School of Computing Summer Workshop, National University of Singapore.
- *2021*, Excellent Undergraduate Student, East China Normal University.
- *2021*, Second-class Scholarship, East China Normal University.
- *2020*, Excellent Undergraduate Student, East China Normal University.
- *2020*, First-class Scholarship, East China Normal University.

# 💬 Services
- Conference Program Committee:
  - AAAI Conference on Artificial Intelligence (AAAI): 2027, 2026, 2025

- Conference Reviewer: 
  - IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR): 2026, 2025, 2024
  - ACM International Conference on Multimedia (ACMMM): 2026
  - IEEE/CVF International Conference on Computer Vision (ICCV): 2025
  - European Conference on Computer Vision (ECCV): 2026
  - British Machine Vision Conference (BMVC): 2026
  - RSI Workshop @ International Conference on Learning Representations (ICLR): 2026

- Journal Reviewer:
  - IEEE Transactions on Knowledge and Data Engineering (TKDE)
  - Neural Networks (NN)
