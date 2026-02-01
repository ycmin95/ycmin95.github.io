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

# 👦 About Me

I am currently an Assistant Professor in Visual Information Processing and Learning ([VIPL](https://vipl.ict.ac.cn/)) group at the Institute of Computing Technology (ICT), Chinese Academy of Sciences (CAS). I received my Ph.D. from ICT, CAS in 2024, under the supervision of Prof. [Xilin Chen](https://scholar.google.com/citations?user=vVx2v20AAAAJ&hl=en&oi=ao). I also had close collaboration with Prof. [Jie Zhang](https://scholar.google.com/citations?user=hJAhF0sAAAAJ) and Prof. [Xiujuan Chai](https://scholar.google.com/citations?user=ZcL91HsAAAAJ). My research interests focus on human-centered interaction with computational systems across physical and cyber spaces, particularly in fine-grained body language understanding and human-in-the-loop agentic systems. I believe AGI will eventually emerge, and understanding how humans can effectively collaborate and coexist with intelligent agents is both an exciting and essential question. **Currently, I am actively working to promote <font color='red'>the real-world deployment of sign language technologies</font> and the evaluation of agentic frameworks. Feel free to reach out if you're interested in any of these topics or potential collaboration.**

<!-- ![Collaboration](images/collaboration.jpg) -->

<!-- During my time pursuing a Ph.D., I focus on efficient visual sequence recognition algorithm designs. For short-term recognition tasks 
(including gesture and isolated sign language recognition), we propose several approaches to adopt the sparse point cloud sequence sampled from 
the depth video for recognition. Compared to video-based algorithms, the point-cloud-based algorithm is more efficient and more sensitive to distance changes, 
and shows effectiveness in gesture recognition and action recognition tasks. After that, I am interested in long-term recognition (i.e., Continuous Sign Language Recognition (CSLR)) 
and find that current approaches are inefficient. Training a video-based CSLR model needs more than 70 hours, which is unbearable :( !!! After several attempts, we attribute the 
overfitting of the powerful alignment module to the major problem of the CTC-based CSLR optimization, which leads to insufficient training of the feature extractor. Several 
constraints are proposed to make the training process more efficient and are adopted by recent CSLR works. I am trying to provide more insights into this phenomenon. -->

<!-- I am looking for a suitable job (vision-based or sequence-based). I believe the job hunting is a two-way selection process. 
If there is a suitable position, please feel free to contact me :)

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=qc2906sAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=qc2906sAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 One paper on cross-view sign language recognition was accepted by ICRA 2026. Congratulations to [Yuting Peng](https://scholar.google.com/citations?user=-Be47NQAAAAJ&hl=zh-CN&oi=sra) and the team!
- *2026.01*: &nbsp;📣📣 We are organizing [Generative AI for Sign Language](https://genai4sl.github.io/) workshop at CVPR 2026 in Denver. We welcome submissions and encourage everyone to attend.
- *2026.01*: &nbsp;🎉🎉 A survey of multimodal hallucination evaluation and detection in VLMs was accepted by IJCV 2026. Congratulations to Zhiyuan Chen and the team!
- *2025.09*: &nbsp;🎉🎉 One paper on hallucination evalution in VLMs was accepted by ACM MM D&B 2025. Congratulations to [Yan Bei](https://scholar.google.com/citations?hl=zh-CN&user=7Xcb8hoAAAAJ&view_op=list_works&sortby=pubdate) and the team!
- *2025.06*: &nbsp;🎉🎉 Our team won [the 1st Multimodal Sign Language Recognition Challenge Challenge at ICCV'25](https://multimodal-sign-language-recognition.github.io/ICCV-2025/) in signer-independent and unseen sentence sub-tasks. Congratulations to everyone involved!
- *2025.01*: &nbsp;🎉🎉 Our team won [the Cross-View Isolated Sign Language Recognition Challenge at WWW'25](https://uq-cvlab.github.io/MM-WLAuslan-Dataset/docs/en/www) in both the RGB and RGB-D tracks. Congratulations to everyone involved!
- *2024.09*: &nbsp;🎉🎉 One paper on skeleton-aware sign language recognition was accepted by ACCV 2024. Congratulations to Yifan Yang and the team!
- *2024.06*: &nbsp;🎉🎉 One paper on vision-language pre-training in SLT was accepted by ECCV 2024. Congratulations to [Peiqi Jiao](https://scholar.google.com/citations?hl=zh-CN&user=47hdL4wAAAAJ&view_op=list_works&sortby=pubdate) and the team!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/radialCTC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Radial Embedding for Visual Sequence Learning](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5670_ECCV_2022_paper.php)

**Yuecong Min**, Peiqi Jiao, Yanan Li, Xiaotao Wang, Lei Lei, Xiujuan Chai, Xilin Chen

<strong><span class='show_paper_citations' data='qc2906sAAAAJ:u_35RYKgDlwC'></span></strong>

<!-- [**Project**](https://github.com/ycmin95/VAC_CSLR) <strong><span class='show_paper_citations' data='qc2906sAAAAJ:u_35RYKgDlwC'></span></strong> -->
- RadialCTC constrains sequence features on a hypersphere while retaining the iterative alignment mechanism of CTC, which also provides a clear geometric interpretation for CTC
- RadialCTC controls the peaky behavior with a simple angular perturbation term
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/vac.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visual Alignment Constraint for Continuous Sign Language Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Min_Visual_Alignment_Constraint_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html)

**Yuecong Min**, Aiming Hao, Xiujuan Chai, Xilin Chen

[![](https://img.shields.io/github/stars/ycmin95/VAC_CSLR?style=social&label=VAC Stars)](https://github.com/ycmin95/VAC_CSLR) [![](https://img.shields.io/github/forks/ycmin95/VAC_CSLR?style=social&label=Forks)](https://github.com/ycmin95/VAC_CSLR) \| <strong><span class='show_paper_citations' data='qc2906sAAAAJ:zA6iFVUQeVQC'></span></strong>
- VAC provides an efficient way to make CSLR models end-to-end trainable and is adopted as the baseline model by many recent works
- Two metrics to evaluate the contributions of the feature extractor and the alignment module
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/pointlstm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Efficient PointLSTM for Point Clouds Based Gesture Recognition](https://openaccess.thecvf.com/content_CVPR_2020/html/Min_An_Efficient_PointLSTM_for_Point_Clouds_Based_Gesture_Recognition_CVPR_2020_paper.html)

**Yuecong Min**, Yanxiao Zhang, Xiujuan Chai, Xilin Chen

[![](https://img.shields.io/github/stars/ycmin95/pointlstm-gesture-recognition-pytorch?style=social&label=PointLSTM Stars)](https://github.com/ycmin95/pointlstm-gesture-recognition-pytorch) [![](https://img.shields.io/github/forks/ycmin95/pointlstm-gesture-recognition-pytorch?style=social&label=Forks)](https://github.com/ycmin95/pointlstm-gesture-recognition-pytorch) \| <strong><span class='show_paper_citations' data='qc2906sAAAAJ:iH-uZ7U-co4C'></span></strong>
- PointLSTM can leverage long-term spatio-temporal relationships in irregular sequence data (e.g., point cloud) while preserving the spatial structure for irregular sequence recognition problem
- Evaluation results on 3D gesture recognition and action recognition show great potential for real-time applications
</div>
</div>

- Learning View-Invariant Sign Language Representations via Dual-Stream Contrastive Learning. Yuting Peng, **Yuecong Min**, Xilin Chen, accepted by IEEE International Conference on Robotics and Automation, 2026.

- [A Survey of Multimodal Hallucination Evaluation and Detection.](https://arxiv.org/abs/2507.19024) Zhiyuan Chen, **Yuecong Min**, Jie Zhang, Bei Yan, Jiahao Wang, Xiaozhen Wang, Shiguang Shan, accepted by International Journal of Computer Vision, 2026.

- [SHALE: A Scalable Benchmark for Fine-grained Hallucination Evaluation in LVLMs.](https://dl.acm.org/doi/abs/10.1145/3746027.3758308) Bei Yan, Zhiyuan Chen, **Yuecong Min**, Jie Zhang, Jiahao Wang, Xiaozhen Wang, Shiguang Shan, Proceedings of the 33rd ACM International Conference on Multimedia, Dataset and Benchmark Track, 2025.

- [Synthetic View Augmentation for Sign Language Recognition.](https://dl.acm.org/doi/abs/10.1145/3701716.3717520) Yuting Peng, Peiqi Jiao, Honggang Zou, **Yuecong Min**, Xilin Chen, Companion Proceedings of the ACM on Web Conference, 2025.

- [S2Net: Skeleton-aware SlowFast Network for Efficient Sign Language Recognition.](https://openaccess.thecvf.com/content/ACCV2024/html/Yang_S2Net_Skeleton-aware_SlowFast_Network_for_Efficient_Sign_Language_Recognition_ACCV_2024_paper.html) Yifan Yang, **Yuecong Min**, Xilin Chen, Asian Conference on Computer Vision (ACCV), 2024.
- [Visual Alignment Pre-training for Sign Language Translation.](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/5894_ECCV_2024_paper.php) Peiqi Jiao, **Yuecong Min**, Xilin Chen, European Conference on Computer Vision (ECCV), 2024. 
- [Adaptive Keyframe Selection for Continuous Sign Language Recognition.](https://www.sciengine.com/SSI/doi/10.1360/SSI-2022-0467) **Yuecong Min**, Xilin Chen, SCIENTIA SINICA Informationis, 2023.        
- [CoSign: Exploring Co-occurrence Signals in Skeleton-based Continuous Sign Language Recognition.](https://openaccess.thecvf.com/content/ICCV2023/html/Jiao_CoSign_Exploring_Co-occurrence_Signals_in_Skeleton-based_Continuous_Sign_Language_Recognition_ICCV_2023_paper.html) Peiqi Jiao, **Yuecong Min**, Yanan Li, Xiaotao Wang, Lei Lei, Xilin Chen, International Conference on Computer Vision (ICCV), 2023.
- [Self-Mutual Distillation Learning for Continuous Sign Language Recognition.](https://openaccess.thecvf.com/content/ICCV2021/html/Hao_Self-Mutual_Distillation_Learning_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html) Aiming Hao, **Yuecong Min**, and Xilin Chen, International Conference on Computer Vision (ICCV), 2021.
- [Teaching Chinese Sign Language with A Smartphone.](https://www.sciencedirect.com/science/article/pii/S2096579621000309) Yanxiao Zhang, **Yuecong Min**, Xilin Chen, Virtual Reality &amp; Intelligent Hardware, 2021.
- [FlickerNet: Adaptive 3D Gesture Recognition from Sparse Point Clouds.](https://bmvc2019.org/wp-content/uploads/papers/0326-paper.pdf) **Yuecong Min**, Xiujuan Chai, Lei Zhao, Xilin Chen, British Machine Vision Conference (BMVC), 2019.

# 🎖 Honors and Awards
- ICCV 2025 **Multimodal Sign Language Recognition** Challenge – 1st Place
  - Achieved top performance in signer-independent and unseen sentence sub-tasks.
- WWW 2025 **Cross-View Isolated Sign Language Recognition** Challenge – 1st Place
  - Achieved top performance in RGB and RGB-D tracks.
- **Excellence Prize of the Chinese Academy of Sciences (CAS) President Award**, 2023.
- **China National Scholarship for Ph.D.**, 2022

# 📖 Educations
- 2017.09 - 2024.1, I was a Ph.D. student at Institute of Computing Technology, CAS, under the supervision of Prof. [Xilin Chen](https://scholar.google.com/citations?user=vVx2v20AAAAJ&hl=en&oi=ao).
- 2013.09 - 2017.07, I was a college student in Shandong University, Weihai.

# ✒️ Academic Services
- Invited journal reviewer for
IEEE TPAMI / IEEE TMM / IEEE TIP / PR ...
- Invited conference reviewer for
CVPR'22 /ACM MM'22 / ECCV'22 / CVPR'23 ...

# ⚙️ Misc
- A summary of papers on gesture and sign language recognition. [![](https://img.shields.io/github/stars/ycmin95/awesome-Gesture-Sign-Language-Recognition?style=social&label=Awesome-Gesture-Sign-Language-Recognition Stars)](https://github.com/ycmin95/awesome-Gesture-Sign-Language-Recognition)
- A simple tool to visualize the main keywords of accepted papers for the recent Computer Vision conferences [![](https://img.shields.io/github/stars/ycmin95/CVPaperStatistics?style=social&label=CVPaperStatistics Stars)](https://github.com/ycmin95/CVPaperStatistics)


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->