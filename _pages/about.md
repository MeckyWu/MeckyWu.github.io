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

I am a postdoctoral research fellow at [AI^2](https://invent.ai.princeton.edu/about), [Princeton AI Lab](https://ai.princeton.edu/ai-lab), working on the principled understanding of large language models and their application to engineering including design and control. I work closely with Prof. [Mengdi Wang](https://ece.princeton.edu/people/mengdi-wang) at Princeton.  

Previously, I earned my Ph.D. in Computer Science from [University of California, Los Angeles (UCLA)](https://www.ucla.edu/), where I was advised by Prof. [Quanquan Gu](http://web.cs.ucla.edu/~qgu/index.html). Before that, I earned my Bachelor of Science from EECS at Peking University *summa cum laude*, where I was very fortunate to be advised by Prof. [Liwei Wang](http://www.liweiwang-pku.com).

My research interest covers various aspects of machine learning. Currently, I am particularly interested in applying insights from reinforcement learning and control theory to LLM training and inference, in the context of alignment and reasoning. You can find my curriculum vitae [here](https://raw.githubusercontent.com/MeckyWu/MeckyWu.github.io/main/pdf/CV.pdf).

# 🔥 News

- *2024.06-09*: This summer, I had an internship at Meta Gen AI, where I worked on LLM alignment and reward modeling. 
- *2024.05*: &nbsp;🎉🎉 2 papers accepted to ICML 2024. 
- *2024.01*: &nbsp;🎉🎉 2 papers accepted to ICLR 2024. 
- *2023.08*: &nbsp; It is my great honor to have been awarded the UCLA Dissertation Year Fellowship! 
- *2023.07*: &nbsp;🎉🎉 1 paper accepted to ICML 2023, Hawaii. 
- *2022.09*: &nbsp;🎉🎉 2 papers accepted to NeurIPS 2022, New Orleans. 

# 📝 Publications & Preprints


- [General Preference Modeling with Preference Representations for Aligning Language Models](https://arxiv.org/abs/2410.02197), **preprint**  
Yifan Zhang\*, Ge Zhang\*, **Yue Wu\***, Kangping Xu, Quanquan Gu

- [Self-Play Preference Optimization for Language Model Alignment](https://arxiv.org/abs/2405.00675), **preprint**  
**Yue Wu\***, Zhiqing Sun\*, Huizhuo Yuan\*, Kaixuan Ji, Yiming Yang, Quanquan Gu

- [Borda Regret Minimization for Generalized Linear Dueling Bandits](https://arxiv.org/pdf/2303.08816), **ICML 2024**  
**Yue Wu**, Tao Jin, Qiwei Di, Hao Lou, Farzad Farnoud, Quanquan Gu

- [Protein Conformation Generation via Force-Guided SE (3) Diffusion Models](https://arxiv.org/pdf/2403.14088), **ICML 2024**  
Yan Wang, Lihao Wang, Yuning Shen, Yiqun Wang, Huizhuo Yuan, **Yue Wu**, Quanquan Gu

- [Variance-Aware Regret Bounds for Stochastic Contextual Dueling Bandits](https://arxiv.org/pdf/2310.00968), **ICLR 2024**  
Qiwei Di, Tao Jin, **Yue Wu**, Heyang Zhao, Farzad Farnoud, Quanquan Gu

- [DNA-GPT: Divergent N-Gram Analysis for Training-Free Detection of GPT-Generated Text](https://arxiv.org/pdf/2305.17359), **ICLR 2024**  
Xianjun Yang, Wei Cheng, **Yue Wu**, Linda Petzold, William Yang Wang, Haifeng Chen

- [Personalized Federated Learning under Mixture of Distributions](https://arxiv.org/pdf/2305.01068), **ICML 2023**  
**Yue Wu**, Shuaicheng Zhang, Wenchao Yu, Yanchi Liu, Quanquan Gu, Dawei Zhou, Haifeng Chen, Wei Cheng

- [Uniform-PAC Guarantees for Model-Based RL with Bounded Eluder Dimension](https://proceedings.mlr.press/v216/wu23b/wu23b.pdf), **UAI 2023**  
**Yue Wu\***, Jiafan He\*, Quanquan Gu

- [Active Ranking without Strong Stochastic Transitivity](https://proceedings.neurips.cc/paper_files/paper/2022/file/020e313d40a7c060ed07a10cef287750-Paper-Conference.pdf),  **NeurIPS 2022**  
Hao Lou, Tao Jin, **Yue Wu**, Pan Xu, Quanquan Gu, Farzad Farnoud 

- [Towards Understanding the Mixture-of-Experts Layer in Deep Learning](https://arxiv.org/pdf/2208.02813), **NeurIPS 2022**  
Zixiang Chen, Yihe Deng, **Yue Wu**, Quanquan Gu, Yuanzhi Li

- [Adaptive Sampling for Heterogeneous Rank Aggregation from Noisy Pairwise Comparisons](https://proceedings.mlr.press/v151/wu22f/wu22f.pdf), **AISTATS 2022**  
**Yue Wu\***, Tao Jin\*, Hao Lou, Pan Xu, Farzad Farnoud, Quanquan Gu

- [Nearly Minimax Optimal Regret for Learning Infinite-horizon Average-reward MDPs with Linear Function Approximation](https://proceedings.mlr.press/v151/wu22a/wu22a.pdf), **AISTATS 2022**  
**Yue Wu**, Dongruo Zhou, Quanquan Gu, 

- [A Finite-Time Analysis of Two Time-Scale Actor-Critic Methods](https://proceedings.neurips.cc/paper/2020/file/cc9b3c69b56df284846bf2432f1cba90-Paper.pdf),  **NeurIPS 2020**  
**Yue Wu**, Weitong Zhang, Pan Xu, Quanquan Gu, 

- [Towards Understanding the Spectral Bias of Deep Learning](https://arxiv.org/pdf/1912.01198), **IJCAI 2021**  
Yuan Cao\*, Zhiying Fang\*, **Yue Wu\***, Dingxuan Zhou, Quanquan Gu

- [To What Extent Do Different Neural Networks Learn the Same Representation: A Neuron Activation Subspace Match Approach](https://proceedings.neurips.cc/paper/2018/file/5fc34ed307aac159a30d81181c99847e-Paper.pdf), **NeurIPS 2019 Spotlight**  
Lunjia Hu, Jiayuan Gu, **Yue Wu**, Zhiqiang Hu, Liwei Wang

# 📖 Teaching
- *2021 Winter* Teaching Assistant, UCLA CS161: [Introduction to Artificial Intelligence](https://uclaml.github.io/CS161-Winter2021/)
- *2022 Winter* Teaching Assistant, UCLA CS161: [Introduction to Artificial Intelligence](https://uclaml.github.io/CS161-Winter2022/)

# 💬 Academic Service
- Reviewers of NeurIPS, ICML, ICLR, AISTATS, AAAI, IJCAI, and other conferences/journals in machine learning/data mining.
- Senior PC members of AAAI'23
