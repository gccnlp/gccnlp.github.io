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

I am a final year direct-entry PhD student at the Institute of Information Engineering, Chinese Academy of Sciences, under the joint supervision of Professors Peng Fu, Zheng Lin, and Weiping Wang.
My research interests include parameter-efficient fine-tuning and efficient training of large language models.


# 🔥 News
- *2026.09*: &nbsp;🎉🎉 Three papers are accepted by NIPS 2026.
- *2026.08*: &nbsp;🎉🎉 Two papers are accepted by EMNLP 2026.
- *2026.05*: &nbsp;🎉🎉 One paper is accepted by ACL 2026.
- *2025.08*: &nbsp;🎉🎉 Our [Trans-PEFT](https://arxiv.org/pdf/2506.06844) is selected for the [ACL2025 SAC Highlights Award (Top 1.5%)](https://2025.aclweb.org/program/awards/#sac-highlights).
- *2025.08*: &nbsp;🎉🎉 Two papers are accepted by EMNLP 2025.
- *2025.05*: &nbsp;🎉🎉 Three papers are accepted by ACL 2025.

# 📝 Selected Publications ([Full List](https://scholar.google.com.hk/citations?user=SxrbtkwAAAAJ))
## 📄 Technical Reports

- **[Technical Report 2026]** [EasyVideoR1: Easier RL for Video Understanding](https://arxiv.org/abs/2604.16893)

- **[Technical Report 2026]** [ERNIE 5.0 Technical Report](https://arxiv.org/abs/2602.04705)


## ⚡ Efficient Post-Training

- **[Preprint]** [CompassOPD: Cross-Family On-Policy Distillation via Within-Family Likelihood Shifts](https://arxiv.org/abs/2609.10154)
  <br>**Naibin Gu**, Qingyi Si, Chenxu Yang, Chuanyu Qin, Junhao Zhou, Peng Fu, Zheng Lin, Weiping Wang

- **[NeurIPS 2026]** [Co-Evolving Policy Distillation](https://arxiv.org/abs/2604.27083)
  <br>**Naibin Gu**, Chenxu Yang, Qingyi Si, Chuanyu Qin, Dingyu Yao, Peng Fu, Zheng Lin, Weiping Wang, Nan Duan, Jiaqi Wang

- **[ACL 2025 Oral]** [Adapt Once, Thrive with Updates: Transferable Parameter-Efficient Fine-Tuning on Evolving Base Models](https://arxiv.org/abs/2506.06844) — **🥇 <span style="color: #c0392b;">SAC Highlights Award, Top 1.5%</span>**
  <br>**Naibin Gu**, Peng Fu, Xiyu Liu, Ke Ma, Zheng Lin, Weiping Wang

- **[ACL 2025]** [BeamLoRA: Beam-Constraint Low-Rank Adaptation](https://arxiv.org/abs/2502.13604)
  <br>**Naibin Gu**, Zhenyu Zhang, Xiyu Liu, Peng Fu, Zheng Lin, Shuohuan Wang, Yu Sun, Hua Wu, Weiping Wang, Haifeng Wang

- **[EMNLP 2025]** [CBP-Tuning: Efficient Local Customization for Black-box Large Language Models](https://arxiv.org/abs/2509.12112)
  <br>Jiaxuan Zhao<sup>*</sup>, **Naibin Gu**<sup>*</sup>, Yuchen Feng, Xiyu Liu, Peng Fu, Zheng Lin, Weiping Wang

- **[Findings of ACL 2024]** [Light-PEFT: Lightening Parameter-Efficient Fine-Tuning via Early Pruning](https://aclanthology.org/2024.findings-acl.447/)
  <br>**Naibin Gu**, Peng Fu, Xiyu Liu, Bowen Shen, Zheng Lin, Weiping Wang

- **[ACL 2023]** [A Gradient Control Method for Backdoor Attacks on Parameter-Efficient Tuning](https://aclanthology.org/2023.acl-long.194/)
  <br>**Naibin Gu**, Peng Fu, Xiyu Liu, Zhengxiao Liu, Zheng Lin, Weiping Wang

- **[EMNLP 2025]** [Weights-Rotated Preference Optimization for Large Language Models](https://aclanthology.org/2025.emnlp-main.1329/)
  <br>Chenxu Yang, Ruipeng Jia, Mingyu Zheng, **Naibin Gu**, Zheng Lin, Siyuan Chen, Weichong Yin, Hua Wu, Weiping Wang


## 🧩 Efficient Model Architectures

- **[Findings of EMNLP 2026]** [CoRe-MoE: Compact Reusable MoE for Continual Multimodal Instruction Tuning](https://arxiv.org/abs/2608.27867)
  <br>Runze Liu<sup>*</sup>, **Naibin Gu**<sup>*</sup>, Mingxu Ai, Yuqing Li, Peng Fu, Zheng Lin, Weiping Wang

- **[Preprint]** [Mixture of Universal Experts: Scaling Virtual Width via Depth-Width Transformation](https://arxiv.org/abs/2603.04971)
  <br>Yilong Chen<sup>*</sup>, **Naibin Gu**<sup>*</sup>, Junyuan Shang, Zhenyu Zhang, Yuchen Feng, Jiawei Sheng, Tingwen Liu, Shuohuan Wang, Yu Sun, Hua Wu, Haifeng Wang

- **[Preprint]** [Elastic MoE: Unlocking the Inference-Time Scalability of Mixture-of-Experts](https://arxiv.org/abs/2509.21892)
  <br>**Naibin Gu**, Zhenyu Zhang, Yuchen Feng, Yilong Chen, Peng Fu, Zheng Lin, Shuohuan Wang, Yu Sun, Hua Wu, Weiping Wang, Haifeng Wang

- **[EMNLP 2026]** [Advantageous Parameter Expansion Training Makes Better Large Language Models](https://arxiv.org/abs/2505.24241)
  <br>**Naibin Gu**, Yilong Chen, Zhenyu Zhang, Peng Fu, Zheng Lin, Shuohuan Wang, Yu Sun, Hua Wu, Weiping Wang, Haifeng Wang

- **[CVPR 2026]** [Blink: Dynamic Visual Token Resolution for Enhanced Multimodal Understanding](https://arxiv.org/abs/2512.10548)
  <br>Yuchen Feng<sup>*</sup>, Zhenyu Zhang<sup>*</sup>, **Naibin Gu**, Yilong Chen, Peng Fu, Zheng Lin, Shuohuan Wang, Yu Sun, Hua Wu, Weiping Wang, Haifeng Wang

- **[ACL 2025]** [DIVE into MoE: Diversity-Enhanced Reconstruction of Large Language Models from Dense into Mixture-of-Experts](https://arxiv.org/abs/2506.09351)
  <br>Yuchen Feng<sup>*</sup>, Bowen Shen<sup>*</sup>, **Naibin Gu**, Jiaxuan Zhao, Peng Fu, Zheng Lin, Weiping Wang


## 🤝 Other Collaborative Papers

- **[IJCAI 2026]** [Causal Path Alignment: Anchoring the Optimization Trajectory for Controllable In-Parameter Knowledge Editing](https://www.ijcai.org/proceedings/2026/655)
  <br>Xiyu Liu, Zhengxiao Liu, **Naibin Gu**, Zheng Lin, Weiping Wang

- **[AAAI 2025]** [Relation Also Knows: Rethinking the Recall and Editing of Factual Associations in Auto-Regressive Transformer Language Models](https://arxiv.org/abs/2408.15091)
  <br>Xiyu Liu, Zhengxiao Liu, **Naibin Gu**, Zheng Lin, Wanli Ma, Ji Xiang, Weiping Wang

<small><sup>*</sup> Equal contribution.</small>

# 📖 Educations
* **Sept. 2022 - Now**: PhD student, Institute of Information Engineering (IIE), CAS & UCAS.
* **Sept. 2018 - Jun. 2022**: Bachelor of Computer Science, China Agricultural University.

# 💻 Internships
- *2026.01 - *, Tech Genius Team (TGT) Intern at the Multimodal Understanding Department, JD Explore Academy. Mentor: [Qingyi Si](https://phoebussi.github.io/)
- *2025.06 - 2026.01*, ERNIE Star Top Talent Research Intern at the NLP Department, Baidu Inc. Mentor: [Haifeng Wang](https://haifengwang.net/) and [Zhenyu Zhang](https://zhenyu.ac.cn/)
- *2024.10 - 2025.05*, Research Intern at the NLP Department, Baidu Inc. Mentor: [Zhenyu Zhang](https://zhenyu.ac.cn/)
