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
Hi, I am a first-year M.Sc. student of the [Monash University](https://www.monash.edu/), advised by [Dr. Lim Chern Hong](https://www.monash.edu.my/it/staff/academic/dr-lim-chern-hong). I will graduate in Septe. 2025. Before that, I got my bachelor degree from [Hebei University of Science and Technology](https://english.hebust.edu.cn/), under the supervision of [Dr. Su Jingfang](https://xxxy.web.hebust.edu.cn/szdw/zhuanrenjs/wlaqx/sujingfang.htm).


[//]: # (From March 2023 to November 2023, I worked as a Research Assistant at the [ASTAPLE lab]&#40;https://www.astaple.com/&#41; of Hong Kong Polytechnic University, under the supervision of [Prof. Haibo Hu]&#40;https://haibohu.org/&#41; and [Dr. Qingqing Ye]&#40;https://www.qingqingye.net/&#41;. )

### 🤔 Research Interests:
* Multimodal Federated Learning.
* Differential Privacy.
* Human Activity Recognization.
* Decentralized Finance & GNN.


# 🔥 News
<style>
  .scrollable {
    max-height: 200px; 
    overflow-y: scroll; 
  }
</style>

<div class="scrollable">
 <ul>
 <li><strong>2024.11</strong>: &nbsp;🎉 One first author paper is accepted by ICIT 2024. </li>
<li><strong>2024.07</strong>: &nbsp;🎉 One first author paper is accepted by IEEE SMC 2024. </li>
<li><strong>2024.06</strong>: &nbsp;🎉 I have joined the <a href="https://www.monash.edu/it/current-students/enrolment/honours-and-minor-thesis">Research Stream</a> at Monash University Malaysia, under the supervision of <a href="https://www.monash.edu.my/it/staff/academic/dr-lim-chern-hong">Dr. Lim Chern Hong</a>, focusing on privacy in the Federated Learning. </li>
</ul>
</div>

# 📝 Main Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICIT 2024</div><img src='images/defi.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring GCN, GAT, and GIN Fusion for Illicit Transaction Classification in Cryptocurrency Networks](https://www.icit.org/index.html)

**Gaoxuan Li**, Xinyu Tang
<div class="scrollable">
<ul>
  <li>First Author (Accepted by <b>ICIT 2024</b>)</li>
  <li>Achievements:
    <ul>
      <li>Achieved classification accuracy improvements of up to 2.9% over standalone GCN, GAT, and GIN models on the Elliptic Bitcoin dataset, reaching an accuracy of 97.17%.</li>
      <li>Demonstrated the effectiveness of four novel fusion architectures—Triple Parallel Layer, Hierarchical Staging, Attention-Weighted Residual Fusion, and Multi-View Feature Aggregation—in enhancing illicit transaction classification.</li>
    </ul>
  </li>
  <li>Responsibilities:
    <ul>
      <li>Developed and implemented four fusion models integrating GCN, GAT, and GIN to address limitations of single architectures in cryptocurrency networks.</li>
      <li>Conducted quantitative and qualitative analyses, showing that the fusion models improve precision, recall, and F1-score for illegal transaction detection.</li>
      <li>Analyzed and validated performance across diverse graph patterns, focusing on capturing multi-dimensional transaction features.</li>
    </ul>
  </li>
</ul>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ICASSP 2025</div><img src='images/pic_arc.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive MIC-Based Noise Injection in Federated Learning for Privacy-Preserving Surgical Activity Analysis](https://2025.ieeeicassp.org/)

**Gaoxuan Li**, Hwa Hui Tew, Jingwen Hu, Litong Liu, Chern Hong Lim
<div class="scrollable">
<ul>
  <li>First Author (Received and Under Review by <b>IEEE ICASSP 2025</b>)</li>
  <li>Achievements:
    <ul>
      <li>Developed the FedMIC framework, enhancing model parameter security in federated learning through adaptive noise injection.</li>
      <li>Introduced dynamic noise adjustment based on Maximal Information Coefficient, maintaining high accuracy while protecting privacy.</li>
    </ul>
  </li>
  <li>Responsibilities:
    <ul>
      <li>Researched and optimized the relationship between noise and model parameters.</li>
      <li>Designed and implemented the FedMIC framework.</li>
      <li>Conducted comparative tests, showing improved security and accuracy.</li>
      <li>Ensured data security during federated training using adaptive noise mechanisms.</li>
    </ul>
  </li>
</ul>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE SMC 2024</div><img src='images/1_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FedBChain: A Blockchain-enabled Federated Learning Framework for Improving DeepConvLSTM with Comparative Strategy Insights](https://arxiv.org/abs/2407.21282)

**Gaoxuan Li**, Chern Hong Lim, Qiyao Ma, Xinyu Tang, Hwa Hui Tew, Fan Ding, and Xuewen Luo
<div class="scrollable">
<ul>
  <li>First Author (Accepted by <b>IEEE SMC 2024</b>)</li>
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
- *2024.02 - 2025.09*, Master of Data Science, Monash University, Bandar Sunway, Malaysia. 
- *2016.09 - 2020.06*, Bachelor of Network Engineering, Hebei University of Science and Technology, Shi Jiazhuang, China.

# 🎖 Honors and Awards
- Student Travel Grant by IEEE SMC Conference, 2024
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
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/0KWnRv3wxjltYVB3MqjNd2?utm_source=generator" width="50%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

<style>
  .scrollable2 {
    max-height: 150px; 
    overflow-y: scroll; 
  }
</style>

<div class="scrollable2">
<ul>
<li><strong>2024.10</strong>:&nbsp;《Where Did U Go》- G.E.M </li>
<li><strong>2024.09</strong>:&nbsp;《Rashomon》- Pear freezes tightly & Wiz_H张子豪 </li>
<li><strong>2024.08</strong>:&nbsp;《Natural》- Imagine Dragons </li>
<li><strong>2024.07</strong>:&nbsp;《Bad Guy》- Billie Eilish</li>
<li><strong>2024.06</strong>:&nbsp;《日落大道》- 梁博 </li>
<li><strong>2024.05</strong>:&nbsp;《我记得》- 赵雷 </li>
<li><strong>2024.04</strong>:&nbsp;《Chalpter Seven》- Jay Chou </li>
<li><strong>2024.03</strong>:&nbsp;《In The Name of Father》- Jay Chou </li>
</ul>
</div>
</div>

# 🏃 Running

<style>
    /* Container for the progress bar */
    .progress-container {
        display: flex;
        align-items: center;
        flex-direction: column;
        width: 100%;
        max-width: 800px;
        margin: 20px auto;
        font-family: Arial, sans-serif;
    }

    /* Distance and target info displayed above the progress bar */
    .distance-info {
        font-size: 14px;
        margin-bottom: 5px;
        color: black;
    }

    /* Horizontal bar container */
    .horizontal-bar {
        display: flex;
        align-items: center;
        width: 100%;
    }

    /* Start age on the left side */
    .start-age {
        font-size: 16px;
        margin-right: 10px;
    }

    /* Progress bar background */
    .progress-bar {
        flex: 1;
        height: 20px;
        background-color: #e0e0e0;
        border-radius: 10px;
        overflow: hidden;
        position: relative;
    }

    /* Actual progress fill */
    .progress {
        height: 100%;
        width: 26%; /* Set this to the progress percentage based on age */
        background-color: #08830f;
        position: relative;
    }

    /* Running icon positioned at the end of the progress fill */
    .runner-icon {
        position: absolute;
        top: 50%;
        right: -10px; /* Adjusts the position to slightly outside the progress bar */
        transform: translateY(-50%) scaleX(-1); /* Center align vertically and flip the icon */
        font-size: 20px;
    }

    /* End label */
    .end-age {
        font-size: 16px;
        margin-left: 10px;
    }
</style>

<div class="progress-container">
    <!-- Distance info displayed above the progress bar -->
    <div class="distance-info">445 km / 41,600 km (Running Target)</div>

    <div class="horizontal-bar">
        <!-- Start age -->
        <div class="start-age">Start: 22 Nov. 2023</div>
        
        <!-- Progress bar container -->
        <div class="progress-bar">
            <!-- Progress fill inside the bar -->
            <div class="progress">
                <!-- Runner icon at the end of the progress fill -->
                <div class="runner-icon">🏃</div>
            </div>
        </div>
        
        <!-- End label -->
        <div class="end-age">Until Unable to Run 💪💪💪</div>
    </div>

    <!-- New line for age label -->
    <div style="margin-left: -33%;font-size: 14px;margin-top: 5px;">26 yrs</div>
</div>

<style>
    /* 容器样式，确保水平滚动 */
    .gallery-container {
        display: flex;
        overflow-x: auto; /* 横向滚动 */
        white-space: nowrap; /* 防止图片换行 */
        padding: 20px;
        scroll-behavior: smooth; /* 滚动平滑 */
    }

    /* 每个图片的样式 */
    .gallery-container img {
        width: 300px; /* 图片宽度，可根据需要调整 */
        height: auto; /* 自动调整高度 */
        margin-right: 10px; /* 图片间隔 */
        border-radius: 10px; /* 圆角 */
        transition: transform 0.3s; /* 放大效果过渡 */
    }

    /* 图片悬停时放大效果 */
    .gallery-container img:hover {
        transform: scale(1.05);
    }

    /* 隐藏滚动条 */
    .gallery-container::-webkit-scrollbar {
        display: none;
    }

    /* 进度条容器 */
    .progress-container-img {
        width: 100%;
        height: 8px;
        background-color: #e0e0e0;
        border-radius: 5px;
        margin-top: 10px;
        overflow: hidden;
    }

    /* 进度条 */
    .progress-bar-img {
        height: 100%;
        width: 0; /* 初始宽度 */
        background-color: #4caf50;
        transition: width 0.1s; /* 平滑过渡 */
    }
</style>
<h2>Running Image Gallery 
    <a href="https://drive.google.com/drive/folders/1PXAIcNtqblzK79AkCed8d7CQRk8c6Rhg?usp=sharing" 
       title="Explore High-Quality Images" 
       style="font-size: 10px; margin-left: 10px; text-decoration: none; color: #007bff;">
       (View High-Quality Images / Monthly Update)
    </a>
</h2>


<div class="gallery-container" id="gallery"></div>

<div class="progress-container-img">
    <div class="progress-bar-img" id="progressBar"></div>
</div>

<script>
    const gallery = document.getElementById('gallery');
    const progressBar = document.getElementById('progressBar');
    
    // 循环生成 136 张图片
    for (let i = 1; i <= 134; i++) {
        const img = document.createElement('img');
        img.src = `running/${i}.jpg`;  // 设置图片路径为 1.jpg, 2.jpg, ..., 136.jpg
        img.alt = `Image ${i}`;
        gallery.appendChild(img);
    }

    // 更新进度条
    gallery.addEventListener('scroll', () => {
        const scrollLeft = gallery.scrollLeft; // 当前滚动的距离
        const maxScrollLeft = gallery.scrollWidth - gallery.clientWidth; // 最大滚动距离
        const scrollPercentage = (scrollLeft / maxScrollLeft) * 100; // 计算滚动百分比
        progressBar.style.width = `${scrollPercentage}%`; // 设置进度条宽度
    });
</script>
-------------------------------------------------------------------------------------------


<div style="display: flex; justify-content: space-between; align-items: center;">
  <div>
    <script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
    <span id="busuanzi_container_site_pv">Visitor Counter: <span id="busuanzi_value_site_pv"></span></span>
    <span id="last-updated-time" style="margin-left: 20px;">
      Last updated on: 2024.11.11
    </span>
  </div>
</div>
