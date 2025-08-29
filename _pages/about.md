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

# 👨🏽‍🎓 About me

I am currently a Master’s student supervised by [Zhiyong Zhang](https://zzmri.sjtu.edu.cn/group/) at the School of Biomedical Engineering, Shanghai Jiao Tong University, with an expected graduation in March 2026. 

My research interests include magnetic resonance imaging (MRI), signal processing, deep learning and RF sensing, with a primary focus on motion detection and correction in MRI. **I am actively seeking PhD positions that align with these areas of study.**

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2025</div><img src='images/paper1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Learning-Driven ECG Synthesis from Beat Pilot Tone Signals for Physiological Monitoring and Image Reconstruction](https://submissions.mirasmart.com/ISMRM2025/Itinerary/PresentationDetail.aspx?evdid=2857)

**Haoyu Sun**, Sijie Zhong, Qichen Ding, Philip Kenneth Lee, Zhiyong Zhang

In Proc. Intl. Soc. Mag. Reson. Med, 10-15 May, Honolulu, Hawaii, 2025 (Power Pitch)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Trans. Instrum. Meas. 2025</div><img src='images/paper2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards contact-free motion sensing technique in low-field MRI using beat pilot tone](https://ieeexplore.ieee.org/abstract/document/10839477)

Suen Chen, **Haoyu Sun**, Suma Anand, Michael Lustig, Yueqi Qiu, Sijie Zhong, Hao Chen, Zhiyong Zhang

IEEE Transactions on Instrumentation and Measurement, 2025.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2024</div><img src='images/paper3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Experimental Investigation of Interfering Factors in Cardiac Sensing of Beat Pilot Tone](https://submissions.mirasmart.com/ISMRM2024/Itinerary/PresentationDetail.aspx?evdid=1691)

**Haoyu Sun**, Sijie Zhong, Suen Chen, Wei Hou, Qichen Ding, Hao Chen, Zhiyong Zhang

In Proc. Intl. Soc. Mag. Reson. Med, 04-09 May, Singapore, 2024 (Digital Poster)

</div>
</div>
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2023</div><img src='images/paper4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards contact-free motion sensing technique at low-field MRI using beat pilot tone](https://submissions.mirasmart.com/ISMRM2023/Itinerary/PresentationDetail.aspx?evdid=930) 
  
Suen Chen, **Haoyu Sun**, Hao Chen, Suma Anand, Michael Lustig, Zhiyong Zhang

In Proc. Intl. Soc. Mag. Reson. Med, 03-08 June, Toronto, Canada, 2023 (Oral)

</div>
</div>

Deep learning-driven contactless ECG in MRI via beat pilot tone for motion-resolved image reconstruction and heart rate monitoring 

**Haoyu Sun**, Qichen Ding, Sijie Zhong, Zhiyong Zhang. Physics in Medicine & Biology, 2025 (Under Revision)

# 🔬 Research Experience

## **Development of a small quadruped robot with VSLAM capabilities** <span style="float: right">2021.04 - 2022.04</span>
- **Visual navigation**: Deployed Stereo Vision-based SLAM algorithm on Nvidia embedded device based on [ROS](https://www.ros.org/) to navigate for quadruped robot.

## **A novel contact-free motion sensing method in Low-Field MRI** <span style="float: right">2022.08 - 2024.09</span>
- **Funding application**: Prepared grant proposal materials that successfully secured funding from the National Natural Science Foundation of China (NSFC).
- **Integration of a 0.25T permanent C-shaped MRI system**: Assembled a low-field MRI system from scratch (magnet, shielding room, gradient and RF amplifiers, power supply, etc.).
- **Quality assurance for the low field MRI system**: Implemented a magnetic field auto-measurement control system on raspberry pi based on the open-source project [cosi-measure](https://github.com/opensourceimaging/cosi-measure).
- **RF-based contact-free motion sensing hardware**: Integrated [Beat Pilot Tone (BPT)](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.30150) (a contact-free motion sensing modality during MR scans) hardware link modules to transmit 2.4 GHz RF signals for motion sensing during MRI scans.
- **Physiological signal processing**: Extracted motion features from high-dimensional BPT-derived physiological data and mapped it to quantitative representations using a motion model.

## **Contactless ECG measurement based on deep learning and Beat Pilot Tone under MRI** <span style="float: right">2024.09 - 2025.06</span>
- **MRI sequence programing**: Modified the MRI sequence (e.g. gradient, RF) and investigated its effect on the BPT sensing signal to guide the optimal experimental setup.
- **Dataset Collection**: Recruited participants to complete cardiac MRI scans and collect paired data of MRI, BPT, and ECG.
- **AI algorithm development**: Developed a deep learning model based on Pytorch to achieve ECG waveform reconstruction using BPT cardiac signal.
- **MRI reconstruction**: Motion-robust retrospective binning MRI reconstruction using radial sampling trajectories.


# 📖 Education
- *2023.09 - present*, Master, Biomedical Engineering, <a href="https://www.sjtu.edu.cn/"><img class="svg" src="/images/SJTU_logo.svg" width="23pt"></a> Shanghai Jiao Tong University 
- *2019.09 - 2023.06*, Bachelor, cum laude, Electrical Engineering, <a href="https://www.njupt.edu.cn/"><img class="svg" src="/images/NJUPT_logo.svg" width="20pt"></a> Nanjing University of Posts and Telecommunications 

# 🎖 Honors and Awards
- *2024.10* Shanghai Jiao Tong University First-Class Academic Scholarship 
- *2022.10* National Scholarship (Top 1%)
- *2021.12* First Prize in TI Cup China’s Undergraduate Electronics Design Contest \| [\[Intelligent medication delivery robot\]](https://www.bilibili.com/video/BV1zp8Je9Esr/?spm_id_from=333.1387.favlist.content.click&vd_source=fb44d4bd04beda1502bf99705ce0494f)
- *2021.10* National Scholarship (Top 1%)
- *2021.09* Second Prize in China’s Undergraduate Smart Car Contest \| [\[Omnidirectional Smart Car Racing\]](https://www.bilibili.com/video/BV1LP4y1P77p/?spm_id_from=333.1387.top_right_bar_window_default_collection.content.click&vd_source=fb44d4bd04beda1502bf99705ce0494f)

# 💻 Internships
## **Prospective physiological triggering for motion-resolved MRI based on Beat Pilot Tone** <span style="float: right">2025.08 - present</span>
Wandong Medical Technology <span style="float: right">Beijing</span>
- **Real-time signal processing**: Acquired BPT-encoded real-time MRI k-space data stream based on Gadgetron and extracted modulated physiological signals with minimal latency.
- **Physiological triggering pipeline**: Calibrated a stable physiological trigger by deriving an initial threshold from the prescan and applied dynamic threshold correction to refine it, converted the trigger signal to a TTL level via serial-port communication hardware, and outputted the TTL trigger to the MR spectrometer to synchronize the sequence acquisition.

# ​👻 Personal
Outdoors has been my constant since childhood. I used to think it was about the views or the adrenaline, but a pre-dawn 5 km climb when I was 15 taught me something simpler: being outdoors helps me quiet my mind and focus on myself. Out there I slow down, strip away the noise, and come back clearer — it’s my go-to way to reset.
<!-- <img src="images/2016Sichuan.png" alt="2016" style="max-width:640;height:auto;display:block;margin:0 auto;"> -->

<!-- <div style="text-align:center; padding-bottom:4rem;">
  <div style="margin-bottom:0.5rem; font-weight:600;"> 2016 </div>
  <img src="images/2016Sichuan.png"
       alt="2016"
       style="max-width:640; height:auto; display:block; margin:0 auto;">
</div> -->
<!-- 方案 A：flex 布局，图片等分宽度，小屏幕自动堆叠 -->
<div style="text-align:center; padding-bottom:4rem;">
  <!-- <div style="margin-bottom:0.5rem; font-weight:600;">
    2016
  </div> -->

  <div style="display:flex; gap:1rem; align-items:flex-start; justify-content:center; flex-wrap:wrap;">
    <img src="images/2016Sichuan.jpg"
         alt="2016"
         style="flex:1 1 280px; max-width:520px; width:100%; height:auto; display:block;">
    <img src="images/2025Jiangxi.jgp"
         alt="2025"
         style="flex:1 1 280px; max-width:520px; width:100%; height:auto; display:block;">
  </div>
</div>



