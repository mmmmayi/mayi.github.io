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

I received my Ph.D. from the National University of Singapore (NUS), where I was supervised by Professor [Li Haizhou](https://www.colips.org/~eleliha/). I am currently a researcher at A*STAR, working on speech generation technologies for Southeast Asian languages. 

My current research focuses on language-model-based speech generation, where large language models predict discrete acoustic tokens to synthesize speech. I work across the full system pipeline, including large-scale pretraining post-training optimization using reinforcement learning methods such as GRPO to improve speech naturalness and robustness.

During my PhD, my research focused on speaker verification, particularly on improving robustness in noisy environments and developing explainable AI techniques to interpret speaker embedding models. My work has been published in major speech processing conferences such as ICASSP and Interspeech<a href='https://scholar.google.com/citations?user=Xt0xIP4AAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. 

I obtained my B.Eng. from Sichuan University in 2017 and M.Eng. from Shanghai Jiao Tong University in 2020. During my master’s studies, I worked on bio-acoustic signal processing, developing a deep learning system for detecting abnormal biological sounds and deploying the model in an Android application with my supervisor Professor [Li Yongfu](https://yongfu-li.github.io/biography.html). 

My research interests broadly lie in speech processing, generative speech models, and speech foundation models, with the goal of bridging cutting-edge research and practical real-world speech applications.

<!-- # 🔥 News-->
<!--- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!--- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📝 Publications 


[ExPO: Explainable Phonetic Trait-Oriented Network for Speaker Verification](https://arxiv.org/abs/2501.05729), **Yi Ma**, Shuai Wang, Tianchi Liu and Haizhou Li, IEEE Signal Processing Letters (SPL), 2025. [code](https://github.com/mmmmayi/ExPO)

[Gradient weighting for speaker verification in extreme low Signal-to-Noise Ratio](https://arxiv.org/abs/2401.02626), **Yi Ma**, Kong Aik Lee, Ville Hautamaki, Meng Ge, Haizhou Li, International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2024. [code](https://github.com/mmmmayi/Grad-W)

[How Do Neural Spoofing Countermeasures Detect Partially Spoofed Audio?](https://arxiv.org/abs/2406.02483), Tianchi Liu, Lin Zhang, Rohan Kumar Das, **Yi Ma**, Ruijie Tao, Haizhou Li, Interspeech, 2024.

[PL-EESR: Perceptual loss based end-to-end robust speaker representation extraction](https://arxiv.org/abs/2110.00940), **Yi Ma**, Kong Aik Lee, Ville Hautamaki, Haizhou Li, 2021 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU), 2021. [code](https://github.com/mmmmayi/PL-EESR)

[LungRN+ NL: An improved adventitious lung sound classification using non-local block resnet neural network with mixup data augmentation](https://www.isca-archive.org/interspeech_2020/ma20_interspeech.html), **Yi Ma**, Xinzi Xu, Yongfu Li, Interspeech, 2020.

[LungBRN: a Smart Digital Stethoscope for Detecting Respiratory Disease Using bi-ResNet Deep Learning Algorithm](https://ieeexplore.ieee.org/document/8919021), **Yi Ma**, Xinzi Xu, Qing Yu, Yuhang Zhang, Yongfu Li, Jian Zhao, Guoxing Wang, IEEE Biomedical Circuits and Systems Conference (BioCAS), 2019. [code](https://github.com/SJTU-YONGFU-RESEARCH-GRP/Lung-Sound-Classification-System-LungSys-I)

[Live Demo: LungSys - Automatic Digital Stethoscope System For Adventitious Respiratory Sound Detection](https://ieeexplore.ieee.org/document/8918752), **Yi Ma**, Xinzi Xu, Qing Yu, Yuhang Zhang, Yongfu Li, Jian Zhao, Guoxing Wang, IEEE Biomedical Circuits and Systems Conference (BioCAS), 2019. [code](https://github.com/SJTU-YONGFU-RESEARCH-GRP/Lung-Sound-Classification-System-LungSys-I)

[Enhancing speech recognition for Parkinson’s disease patient using transfer learning technique](https://link.springer.com/article/10.1007/s12204-021-2376-3), Qing Yu, **Yi Ma**,  Yongfu Li, Journal of Shanghai Jiaotong University (Science), 2022. 

[LungAttn: advanced lung sound classification using attention mechanism with dual TQWT and triple STFT spectrogram](https://iopscience.iop.org/article/10.1088/1361-6579/ac27b9/meta), Jizuo Li, Jiajun Yuan, Hansong Wang, Shijian Liu, Qianyu Guo, **Yi Ma**, Yongfu Li, Liebin Zhao and Guoxing Wang, Physiological Measurement, 2021. 

<!---# 🎖 Honors and Awards-->
<!---- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!---- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📖 Educations
- *2020.08 - now*, Ph.D. in National University of Singapore (NUS), Singapore. 
- *2017.09 - 2020.03*, M.Sc. in Shanghai Jiao Tong University, Shanghai, China.
- *2013.09 - 2017.06*, B.Eng. in Electronic Information Engineer, Sichuan Universiy, Sichuan, China.

<!--# 💬 Invited Talks-->
<!--- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!--- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

# 👔 Internships
- *2024.11 - 2025.05*,Huawei, Singapore.
- *2020.05 - 2020.08*,Pingan Technology, Shangha, China.
  
# 💻 Open Source Code
- [*Speaker Verification Framework with Passive Explanation*](https://github.com/mmmmayi/ExPO)
- [*Robust Speaker Verification Framework Under Noisy Conditions*](https://github.com/mmmmayi/Grad-W)
- [*Speaker Verification Framework trained with Metric Learning Objectives*](https://github.com/mmmmayi/LightWespeaker_Prototypical)
- [*Abnormal Acoustic Detection and Deployment on an Android Application*](https://github.com/SJTU-YONGFU-RESEARCH-GRP/Lung-Sound-Classification-System-LungSys-I)
