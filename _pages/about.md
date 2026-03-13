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

I received my Ph.D. in Aerospace Engineering from **Nanyang Technological University** (NTU), Singapore. I am currently a Research Fellow at the Air Traffic Management Research Institute (ATMRI), NTU. My research centers on AI and optimization for safety-critical air transportation systems with a focus on: **(i) Safe and scalable low-altitude UAM and AAM planning and operations**, **(ii) Human-centered AI for resilient ATM and regional ATFM**, **(iii) AI-driven decision support for intelligent transportation systems**.

**Research Summary**
- **Systems and stakeholders:** Contributed to deployable prototypes for low-altitude UAM traffic management, resilient ATM decision support under thunderstorms, and an ongoing AI-Assisted Regional ATFM system.
- **Publications:** 30+ top journal and conference papers (**15 first authored**), including *Transportation Research Part C/E*, *Reliability Engineering & System Safety*, *Advanced Engineering Informatics*, IEEE T-ITS/TVT; AAMAS 2026 (oral). **850+ citations** on Google Scholar.
- **Leadership and teamwork:** Technical lead (7-person team) for AI-assisted regional ATFM (Aug 2025 – now); team lead (3-person team) for Singapore–Italy AI4ATM project (Apr 2024 – now).
- **Funding and grants:** Experience in national/agency programs (CAAS, NRF, A*STAR, Singapore, NSF China) and grant proposal writing (lead writer / technical coordinator roles listed below).
- **Teaching and mentoring:** Teaching assistant experience; mentored 2 Ph.D. students, 3 M.Sc. students, and 5 undergraduate final-year projects; co-authored 10+ peer-reviewed publications with students.


<span class='anchor' id='-news'></span>
# 🔥 News

- *2026.02*: &nbsp; **Singapore Airshow 2026** — Invited as an exhibitor to showcase the AI-assisted Regional ATFM prototype for aviation stakeholders. Grateful for engaging discussions with colleagues from AIR Lab, MITRE Asia, A*STAR, and SUTD.
- *2026.01*: &nbsp; **AAMAS 2026** — Full paper accepted for oral presentation on constrained multi-agent reinforcement learning for safe planning. Thanks to all co-authors for the collaboration.
- *2025.11*: &nbsp; Visited **ETH Zurich** for discussions on multi-agent systems and privacy-preserving decision making with Dr Fan. Looking forward to future collaborations.
- *2025.10*: &nbsp; Presented our research on automated AI tools for next-generation air transportation at **ICTAI 2025** in Greece.
- *2025.08*: &nbsp; Appointed as Technical Lead for the **AI-assisted Regional ATFM** project. Honoured to work with PI Prof. Luu Anh Tuan.
- *2025.08*: &nbsp; Hosted Prof. Eri Itoh (The University of Tokyo) for a workshop on Regional ATFM and collaborative decision making. Thanks for the inspiring exchange.
- *2025.05*: &nbsp; Met with the Founder and CEO of [ToBlue Aviation Digital](https://www.toblue.aero/) (Fintech start-up) in New York City, USA and had an insightful discussion on how aviation assets can be valued and managed through AI-driven digitalization.
- *2025.05*: &nbsp; Delivered a research talk at **University of Michigan, Ann Arbor**. Many thanks to Prof. Max Li for the kind invitation and hospitality.
- *2024.04*: &nbsp; Appointed as Team Lead for the **Singapore–Italy AI4ATM** collaborative project on resilient aircraft operations under convective weather. Grateful to work with Prof. Guglielmo Lulli and his team from Lancaster University, UK.
- *2023.12*: &nbsp; Joined **ATMRI, NTU** as Research Fellow to work on human–AI teaming for Advanced Air Mobility.
- *2023.10*: &nbsp; Successfully defended my **Ph.D. thesis**. Heartfelt thanks to my supervisors Prof. Kin Huat Low, Prof. Chen Lv, and Prof. Vu N. Duong for their guidance and support throughout the journey.

<span class='anchor' id='-publications'></span>
# 📝 Publications

## Recent Highlights

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">AAMAS 2026 (Oral)</span>
    <img src="images/BIZHAO/AAMAS2026.png" alt="MAF-Net for safe trajectory planning">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[AI for ATM]</strong> <span style="font-weight: normal;">Constrained Multi-Agent Reinforcement Learning with MAF-Net for Safe Trajectory Planning</span></h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Mingcheng Zhang, Xinting Hu, Duc-Thinh Pham, Sameer Alam, Guglielmo Lulli</p>
    <p style="margin: 0.5em 0;"><em>Proc. of the 25th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2026)</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.65109/MQDV9851">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>MAF-Net: A multi-head action filter network integrated with decentralized MARL to enable safe and scalable multi-agent planning under uncertainty.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">AEI 2025</span>
    <img src="images/BIZHAO/AEI2025.png" alt="Multi-aircraft trajectory planning under thunderstorms">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[AI for ATM]</strong> <span style="font-weight: normal;">A multi-aircraft co-operative trajectory planning model under dynamic thunderstorm cells using decentralized deep reinforcement learning</span></h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli</p>
    <p style="margin: 0.5em 0;"><em>Advanced Engineering Informatics</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.aei.2025.103157">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>A framework for multi-aircraft trajectory planning under dynamic thunderstorms.</li>
      <li>A Decentralized MDP for cooperative planning to handle secondary conflicts.</li>
      <li>An improved Independent Deep Deterministic Policy Gradient solution algorithm.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">TRE 2024</span>
    <img src="images/BIZHAO/TRE_2024.png" alt="Stochastic route optimization for safe drone delivery">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[Safe AAM]</strong> <span style="font-weight: normal;">Stochastic route optimization under dynamic ground risk uncertainties for safe drone delivery operations</span></h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Xinting Hu, Wei Dai, Kin Huat Low</p>
    <p style="margin: 0.5em 0;"><em>Transportation Research Part E: Logistics and Transportation Review</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.tre.2024.103717">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>A two-stage stochastic optimization method for AAM risk management.</li>
      <li>Flight approval and execution decisions are made jointly to mitigate dynamic ground risk.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">TRC 2024</span>
    <img src="images/BIZHAO/TRC2024.png" alt="Chance-constrained UAM traffic flow optimization">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[Safe AAM]</strong> <span style="font-weight: normal;">Chance-constrained UAM traffic flow optimization with fast disruption recovery under uncertain waypoint occupancy time</span></h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Kin Huat Low, Vu N. Duong</p>
    <p style="margin: 0.5em 0;"><em>Transportation Research Part C: Emerging Technologies</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.trc.2024.104547">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>A chance-constrained UTFM model is developed to optimize UAM traffic flow under trajectory uncertainty.</li>
      <li>A concept of Waypoint Occupancy Time is proposed to manage dynamic separation.</li>
      <li>A hierarchical stochastic search algorithm is designed to solve the non-convex UTFM optimization problem.</li>
    </ul>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">RESS 2022</span>
    <img src="images/BIZHAO/RESS2022.PNG" alt="UAV path optimization with third-party risk assessment">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[Safe AAM]</strong> <span style="font-weight: normal;">UAV path optimization with an integrated cost assessment model considering third-party risks in metropolitan environments</span></h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Xinting Hu, Wei Dai, Kin Huat Low</p>
    <p style="margin: 0.5em 0;"><em>Reliability Engineering &amp; System Safety</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.ress.2022.108399">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>A third-party risk assessment framework incorporating fatality risk, property damage risk, and noise impact for safe and societally acceptable UAM operations in low-altitude urban airspace.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">TRC 2022</span>
    <img src="images/BIZHAO/TRC2022.PNG" alt="Adaptive conflict resolution for multi-UAV 4D routes">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[Safe AAM]</strong> <span style="font-weight: normal;">Adaptive conflict resolution for multi-UAV 4D routes optimization using stochastic fractal search algorithm</span></h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Kin Huat Low, Chen Lv</p>
    <p style="margin: 0.5em 0;"><em>Transportation Research Part C: Emerging Technologies</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.trc.2022.103666">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>An adaptive UAV conflict resolution framework for 4D route optimization that integrates scheduling, speed adjustment, and rerouting strategies.</li>
    </ul>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">TRC 2026</span>
    <img src="images/BIZHAO/TRC2026.png" alt="U-Aerodrome airspace reconfiguration for UAM at aerodrome">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[UAM-ATM Integration]</strong> <span style="font-weight: normal;">U-Aerodrome: Data-driven and risk-bounded airspace reconfiguration for safe integration of urban air mobility at aerodrome</span></h3>
    <p style="margin: 0.5em 0;">Xinting Hu, <strong>Bizhao Pang* </strong>, Sameer Alam, Mir Feroskhan (*PhD mentor)</p>
    <p style="margin: 0.5em 0;"><em>Transportation Research Part C: Emerging Technologies</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.trc.2025.105506">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>U-Aerodrome, a data-driven and risk-bounded airspace reconfiguration framework designed to support the safe and flexible integration of UAM operations near controlled aerodromes.</li>
      <li>Probabilistic and risk-bounded framework to optimize spatiotemporal boundaries.</li>
      <li>Handling Gaussian and non-Gaussian data distributions for robust safety assurance.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">Work in 2026</span>
    <img src="images/BIZHAO/RESS2026.png" alt="U-SAFE trajectory planning for UAM at aerodrome">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;"><strong>[UAM-ATM Integration]</strong> <span style="font-weight: normal;">U-SAFE: UAM Safe Integration into Aerodrome via Bio-Inspired and Reinforcement Learning-Based Trajectory Planning</span></h3>
    <p style="margin: 0.5em 0;">Xinting Hu, <strong>Bizhao Pang*</strong>, Sameer Alam, Mir Feroskhan (*PhD mentor)</p>
    <p style="margin: 0.5em 0;">Under 2nd review, 2026.</p>
    <ul style="margin: 0.5em 0;">
      <li>An integrated trajectory planning framework that combines proactive risk-based planning with reactive inflight conflict resolution near aerodromes.</li>
    </ul>
  </div>
</div>

## Selected Journal Papers

- **Bizhao Pang**, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli. In-flight multi-aircraft trajectory replanning under dynamic thunderstorm cells using decentralized deep reinforcement learning. *Advanced Engineering Informatics*, 65 (2025): 103157. [DOI](https://doi.org/10.1016/j.aei.2025.103157).
- **Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low. Stochastic route optimization under dynamic ground risk uncertainties for safe drone delivery operations. *Transportation Research Part E*, 192 (2024): 103717. [DOI](https://doi.org/10.1016/j.tre.2024.103717).
- **Bizhao Pang**, Kin Huat Low, Vu N. Duong. Chance-constrained UAM traffic flow optimization with fast disruption recovery under uncertain waypoint occupancy time. *Transportation Research Part C*, 161 (2024): 104547. [DOI](https://doi.org/10.1016/j.trc.2024.104547).
- **Bizhao Pang**, Kin Huat Low, Chen Lv. Adaptive conflict resolution for multi-UAV 4D routes optimization using stochastic fractal search algorithm. *Transportation Research Part C*, 139 (2022): 103666. [DOI](https://doi.org/10.1016/j.trc.2022.103666).
- **Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low. UAV path optimization with an integrated cost assessment model considering third-party risks in metropolitan environments. *Reliability Engineering & System Safety*, 2022: 108399. [DOI](https://doi.org/10.1016/j.ress.2022.108399).
- **Bizhao Pang**, Wei Dai, Xinting Hu, Fuqing Dai, Kin Huat Low. Multiple air route crossing waypoints optimization via artificial potential field method. *Chinese Journal of Aeronautics*, 34(4), 2021. [DOI](https://doi.org/10.1016/j.cja.2020.10.008).
- Xinting Hu, **Bizhao Pang**, Sameer Alam, Mir Feroskhan. U-Aerodrome: Data-driven and risk-bounded airspace reconfiguration for safe integration of Urban Air Mobility at aerodrome. *Transportation Research Part C*, 184 (2026): 105506. [DOI](https://doi.org/10.1016/j.trc.2025.105506)
- Mingcheng Zhang, **Bizhao Pang**, Chao Yan, Mir Feroskhan, Chen Lv. Real-time avoidance of building and dynamic geo-fencing for urban air mobility using deep reinforcement learning. *IEEE Transactions on Intelligent Transportation Systems* (2025). [DOI](https://doi.org/10.1109/TITS.2025.3589322).
- Wei Dai, **Bizhao Pang**, Kin Huat Low. Conflict-free four-dimensional path planning for urban air mobility considering airspace occupancy. *Aerospace Science and Technology*, 119 (2021): 107154. [DOI](https://doi.org/10.1016/j.ast.2021.107154).
- Yu Wu, Kin Huat Low, **Bizhao Pang**, Qingyu Tan. Swarm-based 4D path planning for drone operations in urban environments. *IEEE Transactions on Vehicular Technology*, 70(8), 7464–7479, 2021. [DOI](https://doi.org/10.1109/TVT.2021.3093318).

## Selected Conference Papers

- **Bizhao Pang**, Mingcheng Zhang, Xinting Hu, Thinh Pham, Sameer Alam, Guglielmo Lulli. Constrained Multi-Agent Reinforcement Learning with MAF-Net for Safe Trajectory Planning. *25th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2026)*, Paphos, Cyprus, May 25–29, 2026. **(Oral)**
- **Bizhao Pang**, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli. Decentralized Deep Reinforcement Learning for Cooperative Multi-Agent Flight Trajectory Planning in Adverse Weather. *24th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2025)*, Detroit, Michigan, USA, May 19–23, 2025.
- **Bizhao Pang**, Xinting Hu, Yi Yang Poh, Kin Huat Low. Population density estimation for dynamic ground risk assessment of drone operations. *IEEE/AIAA Digital Avionics Systems Conference (DASC) 2023*, Barcelona, Spain.
- **Bizhao Pang**, Mingcheng Zhang, Chao Deng, Kin Huat Low. Investigation of flight technical error for UAV separation requirement. *AIAA Aviation Forum (AVIATION) 2022*.
- **Bizhao Pang**, C.H. John Wang, Kin Huat Low. Framework of level-of-autonomy-based concept of operations: UAS capabilities. *IEEE/AIAA Digital Avionics Systems Conference (DASC) 2021*.
- **Bizhao Pang**, Wei Dai, Thu Ra, Kin Huat Low. A concept of airspace configuration and operational rules for UAS. *IEEE/AIAA Digital Avionics Systems Conference (DASC) 2020*, San Antonio, TX, USA.
- **Bizhao Pang**, Ng Ee Meng, Kin Huat Low. UAV trajectory estimation and deviation analysis for contingency management. *AIAA Aviation Forum (AVIATION) 2020*, Reno, Nevada, USA.
- **Bizhao Pang**, Qingyu Tan, Kin Huat Low. A risk model based traffic network for adaptive urban airspace management. *AIAA Aviation Forum (AVIATION) 2020*, Reno, Nevada, USA.
- **Bizhao Pang**, Ng Ee Meng, Kin Huat Low. Contingency management of urban UTM based on airspace contexts. *ICAO UAS Industry Symposium 2019*, Montreal, Canada.

## Forthcoming Publications

- **Bizhao Pang**, Mingcheng Zhang, Xinting Hu, Sameer Alam, Guglielmo Lulli. Constrained Multi-Agent Reinforcement Learning with Multi-Head Action Filtering for Safe Aircraft Trajectory Planning (2026), Under 2nd review.
- **Bizhao Pang**, Mingcheng Zhang, Sameer Alam. LLM-Guided Multi-Agent Reinforcement Learning with Safety Constraints (2026), Working paper.
- Xinting Hu, **Bizhao Pang**, Sameer Alam, Mir Feroskhan. U-SAFE: UAM Safe Integration into Aerodrome via Bio-Inspired and Reinforcement Learning-Based Trajectory Planning (2026), Under 2nd review.


<!-- <span class='anchor' id='-honors-and-awards'></span>
# 🎖 Honors and Awards

- *2020* NTU Research Student Scholarship, Nanyang Technological University
- *2019* Best Master Thesis Award (Top 1%), Tianjin, China
- *2019* Excellent Master Graduate Award, CAUC
- *2018* Boeing Scholarship (Top 0.1%)
- *2018* Excellent Postgraduate Student Certificate, CAUC
- *2015–2018* A-Level Graduate Scholarship (3 consecutive years), CAUC
- *2017* National Winner Award, Internet Innovation and Entrepreneurship Competition
- *2014–2015* University Single Subject Scholarship of Innovation (2 consecutive years), CAUC
- *2013* Excellent University Student Leader Honor Certificate, CAUC -->

<span class='anchor' id='-education'></span>
# 📖 Education

- *2020.08 – 2023.10*, Doctor of Philosophy (AI and Intelligent Transportation), Nanyang Technological University, Singapore  
- *2016.08 – 2019.03*, Master of Engineering (ATM and Operations Research), Civil Aviation University of China, Tianjin, China  
- *2012.08 – 2016.06*, Bachelor of Engineering (Air Transportation), Civil Aviation University of China, Tianjin, China  

<span class='anchor' id='-work-experience'></span>
# 💼 Work Experience

- *2023.12 – Present*, **Research Fellow**, Air Traffic Management Research Institute (ATMRI), NTU, Singapore  
  - *AI-assisted Regional ATFM (Aug 2025 – Now)* — Tech Lead: Conceptualizing and developing a distributed AI-assisted ATFM system.  
  - *AI4ATM (Apr 2024 – Now)* — Team Lead: Leading a cross-national team on advanced AI models for resilient ATM under thunderstorms.  
  - *UAM System Development (Dec 2023 – Apr 2025)* — Algorithm Scientist: Developed a safe and scalable AI-based UAM system for Singapore's highly urbanized airspace.
- *2019.04 – 2020.08*, **Research Associate**, Air Traffic Management Research Institute (ATMRI), NTU, Singapore  
  - *UTM System with AirMatrix Concept* — Team Lead: Developed a digital low-altitude urban airspace management system for UAM.  
  - *Risk-based UAM Concept and Algorithm* — Developed risk-based concepts and planning algorithms for safe UAM operations.

<span class='anchor' id='-research-projects'></span>
# 🔬 Research Projects

**AI for Resilient ATM and Cross-Border ATFM Systems**
- *AI-assisted Regional Air Traffic Flow Management* (NRF, Singapore). Aug 2025 – Present — Technical Lead, AI Scientist (7 team members). Leading multidisciplinary research, coordinating with aviation authority and industry stakeholders.
- *Singapore–Italy Collaborative Project: AI for Air Traffic Management (AI4ATM)*. Apr 2024 – Present — Team Lead, AI Scientist (3 team members). Developing AI algorithms for multi-aircraft separation assurance, thunderstorm avoidance, and sequencing.
- *Airspace and Air Traffic Flow Modeling and Optimization* (NSF, China). Sep 2016 – Mar 2019 — Data and Algorithm Engineer. Chinese Air Route Network Optimization; Terminal Airspace Optimization for Sustainable Aviation.

**Low-Altitude UAM and AAM: Concepts, Research, and Development** (NRF, Singapore)
- *Scalable and Robust UAM Scheduling and Disruption Recovery*. Apr 2021 – Mar 2024 — Team Lead, AI Algorithm Researcher.
- *Risk-based UAM Path Optimization Using Machine Learning*. Jan 2022 – Mar 2024 — Team Lead, AI Algorithm Researcher.
- *UTM Platform Development with AirMatrix Concept*. Apr 2019 – Mar 2023 — Algorithm Engineer.
- *UTM and ATM Integration in Low-Altitude Urban Airspace*. Apr 2019 – Mar 2021 — Data Engineer.

<span class='anchor' id='-presentations-and-talks'></span>
# 🎤 Selected Presentations and Talks

- **Feb 2026** &nbsp;&nbsp; **Introduction and Demonstration of an AI-Assisted Regional ATFM Prototype**  
  Singapore Airshow 2026, Singapore
- **May 2025** &nbsp;&nbsp; **Multi-Agent Aircraft Trajectory Planning Using Decentralized MARL**  
  University of Michigan, Ann Arbor, MI, USA
- **May 2025** &nbsp;&nbsp; **Decentralized DRL for Cooperative Multi-Aircraft Trajectory Planning**  
  AAMAS 2025, Detroit, MI, USA
- **Sep 2023** &nbsp;&nbsp; **Population Density Estimation for Dynamic Ground-Risk Assessment of Drone Operations**  
  IEEE/AIAA Digital Avionics Systems Conference (DASC) 2023, Barcelona, Spain
- **Dec 2022** &nbsp;&nbsp; **Scientific Paper Writing and Response to Reviewers' Comments**  
  Civil Aviation University of China (CAUC), Tianjin, China
- **Nov 2021** &nbsp;&nbsp; **Risk Modelling and Assessment for UAS Operations in Urban Environments**  
  Cranfield University, Online
- **Sep 2019** &nbsp;&nbsp; **UAS Operations and Industry Perspectives**  
  ICAO UAS Industry Symposium 2019, Montreal, Canada

<div style="display: none;">
<!-- HIDDEN: Showcase and Gallery sections - remove the wrapper div to show again -->

<span class='anchor' id='-showcase'></span>
# 🎬 Showcase

*This section is ready for you to add videos and figures to showcase your work. See instructions below.*

To add a **video** (e.g., from YouTube or a local file):

```html
<div class="showcase-item">
  <h4>Project Title</h4>
  <p>Brief description of the work.</p>
  <div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
  </div>
</div>
```

To add a **figure/image**:

```markdown
![Project Figure](images/your-figure.png)
*Caption: Description of your figure.*
```

**Example placeholder** — Replace with your own content:

<div class="showcase-item" style="margin: 2em 0; padding: 1em; border: 1px solid #eee; border-radius: 8px;">
  <h4>UAM Traffic Management System</h4>
  <p>Safe and scalable AI-based UAM system for Singapore's urban airspace. Add your video or figure here.</p>
</div>

*To add more showcase items: paste the HTML/Markdown blocks above and replace with your video IDs or image paths. Save your videos in `images/` or link to YouTube/Vimeo.*

<span class='anchor' id='-gallery'></span>
# 📷 Gallery

Photos from research, teaching, and daily life.

<div class="gallery-section">
  <h3>🔬 Research</h3>
  <div class="gallery-grid">
    <figure class="gallery-item">
      <img src="images/gallery/research1.jpg" alt="Research photo">
      <figcaption>Add caption for your photo</figcaption>
    </figure>
    <figure class="gallery-item">
      <img src="images/gallery/research2.jpg" alt="Research photo">
      <figcaption>Add caption for your photo</figcaption>
    </figure>
  </div>
</div>

<div class="gallery-section">
  <h3>📚 Teaching</h3>
  <div class="gallery-grid">
    <figure class="gallery-item">
      <img src="images/gallery/teaching1.jpg" alt="Teaching photo">
      <figcaption>Add caption for your photo</figcaption>
    </figure>
  </div>
</div>

<div class="gallery-section">
  <h3>🌸 Daily Life</h3>
  <div class="gallery-grid">
    <figure class="gallery-item">
      <img src="images/gallery/life1.jpg" alt="Daily life photo">
      <figcaption>Add caption for your photo</figcaption>
    </figure>
  </div>
</div>

*To add your photos: save images in `images/gallery/` and update the `src` paths and `figcaption` text above. Supported formats: jpg, png, webp.*

</div>
