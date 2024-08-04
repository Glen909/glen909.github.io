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

# 🧐 About Me
Hi, I am a first-year M.Sc. student of the [Monash University](https://www.monash.edu/), advised by [Dr. Lim Chern Hong](https://www.monash.edu.my/it/staff/academic/dr-lim-chern-hong). Before that, I got my bachelor degree from [Hebei University of Science and Technology](https://english.hebust.edu.cn/), under the supervision of [Dr. Su Jingfang](https://xxxy.web.hebust.edu.cn/szdw/zhuanrenjs/wlaqx/sujingfang.htm).


[//]: # (From March 2023 to November 2023, I worked as a Research Assistant at the [ASTAPLE lab]&#40;https://www.astaple.com/&#41; of Hong Kong Polytechnic University, under the supervision of [Prof. Haibo Hu]&#40;https://haibohu.org/&#41; and [Dr. Qingqing Ye]&#40;https://www.qingqingye.net/&#41;. )

### 🤔 Research Interests:
* Multimodal Federated Learning.
* Differential Privacy.
* Affective Computing.
* Ubiquitous Computing.


# 🔥 News
<style>
  .scrollable {
    max-height: 200px; 
    overflow-y: scroll; 
  }
</style>

<div class="scrollable">
 <ul>
<li><strong>2024.07</strong>: &nbsp;🎉 One first author paper is accepted by IEEE SMC 2024. </li>
<li><strong>2024.06</strong>: &nbsp;🎉 I have joined the <a href="https://www.monash.edu/it/current-students/enrolment/honours-and-minor-thesis">Research Stream</a> at Monash University Malaysia, under the supervision of <a href="https://www.monash.edu.my/it/staff/academic/dr-lim-chern-hong">Dr. Lim Chern Hong</a>, focusing on privacy in the LLM. </li>
</ul>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE SMC 2024</div><img src='images/1_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FedBChain: A Blockchain-enabled Federated Learning Framework for Improving DeepConvLSTM with Comparative Strategy Insights](https://arxiv.org/abs/2407.21282)

**Gaoxuan Li**, Chern Hong Lim, Qiyao Ma, Xinyu Tang, Hwa Hui Tew
<div class="scrollable">
<ul>
  <li>Achievements:
    <ul>
      <li>Achieved significant improvements in Precision, Recall, and F1-score (4%+ on average) across three real-world datasets.</li>
      <li>Demonstrated enhancements using five federated learning strategies: FedAvg, FedProx, FedTrimmedAvg, Krum, and FedAvgM.</li>
    </ul>
  </li>
  <li>Responsibilities:
    <ul>
      <li>Conducted extensive research on reducing LSTM layers for enhanced prediction performance.</li>
      <li>Designed and implemented the FedBChain framework.</li>
      <li>Performed comparative tests with different hidden layer units (128, 256, 512) and federated learning strategies.</li>
      <li>Analyzed and validated results, ensuring improvements in performance metrics.</li>
      <li>Ensured data security and privacy during distributed training processes.</li>
    </ul>
  </li>
</ul>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Thesis Project</div><img src='images/2_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Intelligent Navigation System Based on ResNet50-LSTM Combined Model](https://www.youtube.com/watch?v=VaXgr8zIOWs)

**Gaoxuan Li**, Su Jingfang

<div class="scrollable">
<ul>
  <li>System Composition:
    <ul>
      <li>The system consists of four parts: visually impaired user terminal, supervisor terminal, data cloud storage, and image cloud processing.</li>
    </ul>
  </li>
  <li>Visually Impaired User Terminal:
    <ul>
      <li>Uses Raspberry Pi 3B+ as the central processor, running a Linux system, equipped with modules for image collection, GPS positioning, ultrasonic distance measurement, voice broadcasting, and remote voice assistance.</li>
    </ul>
  </li>
  <li>Supervisor Terminal:
    <ul>
      <li>A WeChat mini-program displaying data including images and corresponding text descriptions, along with distance data of obstacles, also offering remote voice assistance.</li>
    </ul>
  </li>
  <li>Data Cloud Storage:
    <ul>
      <li>Uses China Mobile OneNET platform for storing and forwarding system data.</li>
    </ul>
  </li>
  <li>Image Cloud Processing:
    <ul>
      <li>Utilizes Flask framework-based web server to generate text descriptions via neural network models, which are then sent back to the user terminal.</li>
    </ul>
  </li>
</ul>
</div>
</div>
</div>

# 📖 Educations
- *2024.02 - 2025.06*, Master of Data Science, Monash University, Bandar Sunway, Malaysia. 
- *2016.09 - 2020.06*, Bachelor of Network Engineering, Hebei University of Science and Technology, Shi Jiazhuang, China.

# 🎖 Honors and Awards
- Outstanding Undergraduate Thesis, 2020
- Four-Time Recipient of Provincial-Level Awards, 2016 - 2020
- Seven-Time Recipient of School-Level Awards, 2016 - 2020
- Two-time Outstanding Team Leader, 2016 - 2020

# 💻 Work Experience
<ul>
  <li><i>2022.07 - 2022.12</i>, <a href="https://en.wikipedia.org/wiki/Meituan">Youxuan Department, Meituan (Fortune Top 500)</a>, Test Development Engineer (Full-time), Beijing, China.
    <div style="margin-left: 20px;">
      <ul>
        <li>Responsible for testing and maintaining the vegetable market module.</li>
        <li>Developed and implemented automated testing frameworks to ensure the quality and functionality of the vegetable market module.</li>
        <li>Conducted regular performance evaluations and troubleshooting to identify and resolve issues promptly.</li>
        <li>Collaborated with cross-functional teams to enhance system efficiency and user experience.</li>
        <li>Provided documentation and training to team members on automation tools and processes.</li>
      </ul>
    </div>
  </li>
</ul>
<ul>
  <li><i>2021.06 - 2021.09</i>, <a href="https://en.wikipedia.org/wiki/Meituan">Youxuan Department, Meituan (Fortune Top 500)</a>, Test Development Engineer (Part-time), Beijing, China.
    <div style="margin-left: 20px;">
      <ul>
        <li>Managed testing and maintenance of the logistics module for Meituan Youxuan.</li>
        <li>Developed and maintained automated test cases for the logistics module.</li>
        <li>Participated in the research and development of algorithms for automatic generation of system-level test cases.</li>
        <li>Conducted performance evaluations and debugging to ensure optimal system operation.</li>
        <li>Collaborated with various teams to improve automation processes and system efficiency.</li>
        <li>Received an internship performance rating of A (S/A/B/C).</li>
      </ul>
    </div>
  </li>
</ul>

# 🎧 Monthly Song
<div>

<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/6QDGqo8VQ4vadIuHcTSXFK?utm_source=generator" width="50%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
</div>

<style>
  .scrollable2 {
    max-height: 80px; 
    overflow-y: scroll; 
  }
</style>

<div class="scrollable2">
 <ul>
<li><strong>2024.07</strong>:&nbsp;《Where Did U Go》- G.E.M </li>
<li><strong>2024.06</strong>:&nbsp;《日落大道》- 梁博 </li>
<li><strong>2024.05</strong>:&nbsp;《我记得》- 赵雷 </li>
<li><strong>2024.04</strong>:&nbsp;《Chalpter Seven》- Jay Chou </li>
<li><strong>2024.03</strong>:&nbsp;《In The Name of Father》- Jay Chou </li>
</ul>
</div>

<div>

<div>

-------------------------------------------------------------------------------------------

</div>
<div style="display: flex; justify-content: space-between; align-items: center;">
  <div>
    <script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
    <span id="busuanzi_container_site_pv">Visitor Counter: <span id="busuanzi_value_site_pv"></span></span>
    <span id="last-updated-time" style="margin-left: 20px;">
      Last updated on: 2024.8.4
    </span>
  </div>
</div>
