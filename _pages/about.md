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

I am currently a Ph.D. candidate in Visual Information Processing and Learning ([VIPL](https://vipl.ict.ac.cn/)) group from the Institute of Computing Technology, Chinese Academy of Sciences, under the supervision of Prof. [Xilin Chen](https://scholar.google.com/citations?user=vVx2v20AAAAJ&hl=en&oi=ao). I also had close collaboration with Prof. [Xiujuan Chai](https://scholar.google.com/citations?user=ZcL91HsAAAAJ&hl=en&oi=ao). My research interests mainly focus on human behavior analysis and understanding from sequential data, especially for gesture and sign language. I am also interested in exploring how to use data in deep learning more efficient. Before that, I obtained my bachelor degree from Shandong University.

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
- *2022.07*: &nbsp;🎉🎉 One paper is accepted by ECCV 2022!
- *2023.07*: &nbsp;🎉🎉 One paper on Co-occurrence signals in CSLR is accepted by ICCV 2023. Congratulations to Peiqi Jiao and the team!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/radialCTC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Radial Embedding for Visual Sequence Learning](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5670_ECCV_2022_paper.php)

**Yuecong Min**, Peiqi Jiao, Yanan Li, Xiaotao Wang, Lei Lei, Xiujuan Chai, Xilin Chen

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

- CoSign: Exploring Co-occurrence Signals in Skeleton-based Continuous Sign Language Recognition. Peiqi Jiao, **Yuecong Min**, Yanan Li, Xiaotao Wang, Lei Lei, Xilin Chen, International Conference on Computer Vision (ICCV), 2023 (accept).
- [Self-Mutual Distillation Learning for Continuous Sign Language Recognition.](https://openaccess.thecvf.com/content/ICCV2021/html/Hao_Self-Mutual_Distillation_Learning_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html) Aiming Hao, **Yuecong Min**, and Xilin Chen, International Conference on Computer Vision (ICCV), 2021.
- [Teaching Chinese Sign Language with A Smartphone.](https://www.sciencedirect.com/science/article/pii/S2096579621000309) Yanxiao Zhang, **Yuecong Min**, Xilin Chen, Virtual Reality &amp; Intelligent Hardware, 2021.
- [FlickerNet: Adaptive 3D Gesture Recognition from Sparse Point Clouds.](https://bmvc2019.org/wp-content/uploads/papers/0326-paper.pdf) **Yuecong Min**, Xiujuan Chai, Lei Zhao, Xilin Chen, British Machine Vision Conference (BMVC), 2019.


# 🎖 Honors and Awards
- **China National Scholarship for Ph.D.**, ICT, CAS, 2022


# 📖 Educations
- 2017.09 - now, I am a Ph.D. student at Institute of Computing Technology, CAS, under the supervision of Prof. [Xilin Chen](https://scholar.google.com/citations?user=vVx2v20AAAAJ&hl=en&oi=ao).
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