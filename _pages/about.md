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

## Hi, welcome!

I am a tenure-track **Assistant Professor** at **The Hong Kong University of Science and Technology (Guangzhou) [HKUST(GZ)]**, where I am establishing the research group **Human–AI Collaborative Intelligence for Aviation Systems**. My research combines AI, data science, optimization, statistics, and human factors to develop trustworthy decision-support and autonomous systems for safety-critical aviation applications. I received my Ph.D. in Mechanical and Aerospace Engineering from **Nanyang Technological University (NTU)**, Singapore, and subsequently worked there as a postdoctoral Research Fellow before joining HKUST(GZ).

<div class="notice--info" markdown="1">

#### ✈️ Human–AI Collaborative Intelligence for Aviation Systems

The group focuses on three connected research themes:

- 🧠 **AI-driven prediction and decision-making under uncertainty:** We develop AI, data-driven, and optimization methods for risk prediction, multimodal trajectory forecasting, anomaly detection, intention recognition, and intelligent decision-making in complex and uncertain environments.
- 🤝 **Human–AI collaboration and multi-agent systems:** We study how humans, AI agents, and autonomous systems can safely and efficiently perceive, decide, and collaborate, including aircraft coordination, distributed traffic optimization, human–AI decision-making, LLM/VLM agents, and aerial embodied intelligence.
- 🛡️ **Trustworthy AI for safety-critical systems:** We develop robust, explainable, and safety-aware AI methods and validate them in high-consequence, real-world operational settings.

Aviation is our primary application domain, including **low-altitude mobility, ATM/UTM integration, intelligent aviation, logistics, and related autonomous systems**. We emphasize interdisciplinary, impact-driven research that combines AI, data science, optimization, statistics, human factors, and real-world system validation. Our long-term vision is to help aviation and air mobility become more accessible, safer, and smarter.

#### 🎓 Ph.D./MPhil/RA Openings

I am recruiting **Ph.D. students for Spring 2027 and Fall 2027**, as well as **MPhil students and Research Assistants**. Students from AI, computer science, statistics, mathematics, operations research, automation, transportation, aviation, and related backgrounds are welcome to apply; prior aviation experience is not required.

🌏 I also warmly welcome research collaborations with students and colleagues worldwide, as well as partnerships with industry and government agencies.

📩 To apply, email [pangbizhao@gmail.com](mailto:pangbizhao@gmail.com?subject=PhD%2FMPhil%2FRA%20Application%20%E2%80%93%20Name%20%E2%80%93%20Research%20Interest) with the subject **“PhD/MPhil/RA Application – Name – Research Interest.”** Please include:

- Your CV
- A brief description of your future research interests
- One or two representative works, if available (paper links, GitHub repositories, project demos, etc.)

I look forward to learning, building, and growing together with future students and collaborators. ✨

</div>

<span class='anchor' id='-news'></span>
# 🔥 News

- *2026.08*: &nbsp; I joined **The Hong Kong University of Science and Technology (Guangzhou)** as a tenure-track **Assistant Professor** and began establishing the research group **Human–AI Collaborative Intelligence for Aviation Systems**.
- *2026.08*: &nbsp; Two papers on safe **AAM–ATM integration**  ([**U-Aerodrome**](https://doi.org/10.1016/j.trc.2025.105506) and [**U-SAFE**](https://doi.org/10.1016/j.ress.2026.113153)) have been accepted for publication in *TR Part-C* and *Reliability Engineering & System Safety*, respectively. Congrats to the team!
- *2026.06*: &nbsp; Call for Papers is open for the first edition of [**Aviation Innovation Conference for the Asia-Pacific (AICAP) 2027**](https://event.ntu.edu.sg/AICAP-2027). Paper submissions, industry exhibitions, and technology demonstrations are very welcome.
- *2026.05*: &nbsp; Two papers accepted by **IEEE ITSC 2026** on scalable MARL and prediction-then-optimization. Congrats to the first authors, Dr Mingcheng and Dr Yixi.
- *2026.04*: &nbsp; I was appointed as *Team Lead* for the FlexMAN project, aiming to foster **human–AI hybrid automation** for NextGen Air Traffic Management systems.
- *2026.02*: &nbsp; **Singapore Airshow 2026** — Invited as an exhibitor to showcase the AI-assisted Regional ATFM prototype for aviation stakeholders. Grateful for engaging discussions with colleagues from AIR Lab, MITRE Asia, A*STAR, and SUTD.
- *2026.01*: &nbsp; **AAMAS 2026** — Full paper accepted for oral presentation on constrained multi-agent reinforcement learning for safe planning. Thanks to all co-authors for the collaboration.
- *2025.11*: &nbsp; Visited **ETH Zurich** for discussions on multi-agent systems and privacy-preserving decision making with Dr Fan. Looking forward to future collaborations.
- *2025.10*: &nbsp; Presented our research on automated AI tools for next-generation air transportation at **ICTAI 2025** in Greece.
- *2025.08*: &nbsp; Appointed as Technical Lead for the **AI-assisted Regional ATFM** project. Honoured to work with PI Prof. Luu Anh Tuan.
- *2025.08*: &nbsp; Hosted Prof. Eri Itoh (The University of Tokyo) for a workshop on Regional ATFM and collaborative decision making. Thanks for the inspiring exchange.
- *2025.05*: &nbsp; Had an insightful talk session with Mr. Yu, Founder and CEO of ToBlue Aviation Digital (Fintech start-up) in New York City, USA, on potential collaboration in AI-driven digitalization for aviation asset valuation and management.
- *2025.05*: &nbsp; Delivered a research talk at **University of Michigan, Ann Arbor**. Many thanks to Prof. Max Li for the kind invitation and hospitality.
- *2024.04*: &nbsp; Appointed as Team Lead for the **Singapore–Italy AI4ATM** collaborative project on resilient aircraft operations under convective weather. Grateful to work with Prof. Guglielmo Lulli and his team from Lancaster University, UK.
- *2023.12*: &nbsp; Joined **ATMRI, NTU** as Research Fellow to work on human–AI teaming for Advanced Air Mobility.
- *2023.09*: &nbsp; Successfully defended my **Ph.D. thesis** on AI for safe and efficient Urban Air Mobility. Heartfelt thanks to my supervisors Prof. Kin Huat Low, Prof. Chen Lv, and Prof. Vu N. Duong for their guidance and support throughout the journey.

<span class='anchor' id='-publications'></span>
# 📝 Publications



## Recent Highlights

AAMAS 2026 (Oral) ![MAF-Net for safe trajectory planning](images/BIZHAO/AAMAS2026.png)

### **[AI for ATM]** Constrained Multi-Agent Reinforcement Learning with MAF-Net for Safe Trajectory Planning

**Bizhao Pang**, Mingcheng Zhang, Xinting Hu, Duc-Thinh Pham, Sameer Alam, Guglielmo Lulli

*Proc. of the 25th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2026)*

[Paper](https://doi.org/10.65109/MQDV9851) | [Video](https://www.youtube.com/watch?v=l5eEwZ6mpqc&t=12s)

- MAF-Net: A multi-head action filter network integrated with decentralized MARL to enable safe and scalable multi-agent planning under uncertainty.

AEI 2025 ![Multi-aircraft trajectory planning under thunderstorms](images/BIZHAO/AEI2025.png)

### **[AI for ATM]** A multi-aircraft co-operative trajectory planning model under dynamic thunderstorm cells using decentralized deep reinforcement learning

**Bizhao Pang**, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli

*Advanced Engineering Informatics*

[Paper](https://doi.org/10.1016/j.aei.2025.103157)

- A framework for multi-aircraft trajectory planning under dynamic thunderstorms.
- A Decentralized MDP for cooperative planning to handle secondary conflicts.
- An improved Independent Deep Deterministic Policy Gradient solution algorithm.

TRE 2024 ![Stochastic route optimization for safe drone delivery](images/BIZHAO/TRE_2024.png)

### **[Safe AAM]** Stochastic route optimization under dynamic ground risk uncertainties for safe drone delivery operations

**Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low

*Transportation Research Part E: Logistics and Transportation Review*

[Paper](https://doi.org/10.1016/j.tre.2024.103717)

- A two-stage stochastic optimization method for AAM risk management.
- Flight approval and execution decisions are made jointly to mitigate dynamic ground risk.

TRC 2024 ![Chance-constrained UAM traffic flow optimization](images/BIZHAO/TRC2024.png)

### **[Safe AAM]** Chance-constrained UAM traffic flow optimization with fast disruption recovery under uncertain waypoint occupancy time

**Bizhao Pang**, Kin Huat Low, Vu N. Duong

*Transportation Research Part C: Emerging Technologies*

[Paper](https://doi.org/10.1016/j.trc.2024.104547)

- A chance-constrained UTFM model is developed to optimize UAM traffic flow under trajectory uncertainty.
- A concept of Waypoint Occupancy Time is proposed to manage dynamic separation.
- A hierarchical stochastic search algorithm is designed to solve the non-convex UTFM optimization problem.

RESS 2022 ![UAV path optimization with third-party risk assessment](images/BIZHAO/RESS2022.PNG)

### **[Safe AAM]** UAV path optimization with an integrated cost assessment model considering third-party risks in metropolitan environments

**Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low

*Reliability Engineering & System Safety*

[Paper](https://doi.org/10.1016/j.ress.2022.108399)

- A third-party risk assessment framework incorporating fatality risk, property damage risk, and noise impact for safe and societally acceptable UAM operations in low-altitude urban airspace.

TRC 2022 ![Adaptive conflict resolution for multi-UAV 4D routes](images/BIZHAO/TRC2022.PNG)

### **[Safe AAM]** Adaptive conflict resolution for multi-UAV 4D routes optimization using stochastic fractal search algorithm

**Bizhao Pang**, Kin Huat Low, Chen Lv

*Transportation Research Part C: Emerging Technologies*

[Paper](https://doi.org/10.1016/j.trc.2022.103666)

- An adaptive UAV conflict resolution framework for 4D route optimization that integrates scheduling, speed adjustment, and rerouting strategies.

TRC 2026 ![U-Aerodrome airspace reconfiguration for UAM at aerodrome](images/BIZHAO/TRC2026.png)

### **[UAM-ATM Integration]** U-Aerodrome: Data-driven and risk-bounded airspace reconfiguration for safe integration of urban air mobility at aerodrome

Xinting Hu, **Bizhao Pang*** , Sameer Alam, Mir Feroskhan (*PhD mentor)

*Transportation Research Part C: Emerging Technologies*

[Paper](https://doi.org/10.1016/j.trc.2025.105506)

- U-Aerodrome, a data-driven and risk-bounded airspace reconfiguration framework designed to support the safe and flexible integration of UAM operations near controlled aerodromes.
- Probabilistic and risk-bounded framework to optimize spatiotemporal boundaries.
- Handling Gaussian and non-Gaussian data distributions for robust safety assurance.

RESS 2026 ![U-SAFE trajectory planning for UAM at aerodrome](images/BIZHAO/RESS2026.png)

### **[UAM-ATM Integration]** U-Safe: Urban air mobility safe integration into aerodrome via bio-inspired and reinforcement learning-based trajectory management

Xinting Hu, **Bizhao Pang*** , Sameer Alam, Mir Feroskhan (*PhD mentor)

*Reliability Engineering & System Safety*

[Paper](https://doi.org/10.1016/j.ress.2026.113153)

- An integrated trajectory management framework that combines proactive risk-based planning with reactive in-flight conflict resolution for safe UAM integration near aerodromes.
- Bio-inspired and reinforcement learning-based methods for scalable, safety-aware UAM–ATM integration at aerodromes.



## Selected Journal Papers

<sup>* Corresponding author</sup>

- **Bizhao Pang**, Mingcheng Zhang, Xinting Hu, Sameer Alam, Guglielmo Lulli. MAF-DAC: Constrained Multi-Agent Reinforcement Learning with Multi-Head Action Filtering for Safe Aircraft Trajectory Planning. *IEEE Transactions on Intelligent Transportation Systems*, (2026), Accepted.
- **Bizhao Pang**, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli. In-flight multi-aircraft trajectory replanning under dynamic thunderstorm cells using decentralized deep reinforcement learning. *Advanced Engineering Informatics*, 65 (2025): 103157. [DOI](https://doi.org/10.1016/j.aei.2025.103157).
- **Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low. Stochastic route optimization under dynamic ground risk uncertainties for safe drone delivery operations. *Transportation Research Part E*, 192 (2024): 103717. [DOI](https://doi.org/10.1016/j.tre.2024.103717).
- **Bizhao Pang**, Kin Huat Low, Vu N. Duong. Chance-constrained UAM traffic flow optimization with fast disruption recovery under uncertain waypoint occupancy time. *Transportation Research Part C*, 161 (2024): 104547. [DOI](https://doi.org/10.1016/j.trc.2024.104547).
- **Bizhao Pang**, Kin Huat Low, Chen Lv. Adaptive conflict resolution for multi-UAV 4D routes optimization using stochastic fractal search algorithm. *Transportation Research Part C*, 139 (2022): 103666. [DOI](https://doi.org/10.1016/j.trc.2022.103666).
- **Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low. UAV path optimization with an integrated cost assessment model considering third-party risks in metropolitan environments. *Reliability Engineering & System Safety*, 2022: 108399. [DOI](https://doi.org/10.1016/j.ress.2022.108399).
- **Bizhao Pang**, Wei Dai, Xinting Hu, Fuqing Dai, Kin Huat Low. Multiple air route crossing waypoints optimization via artificial potential field method. *Chinese Journal of Aeronautics*, 34(4), 2021. [DOI](https://doi.org/10.1016/j.cja.2020.10.008).
- Xinting Hu, **Bizhao Pang**, Sameer Alam, Mir Feroskhan. U-Aerodrome: Data-driven and risk-bounded airspace reconfiguration for safe integration of Urban Air Mobility at aerodrome. *Transportation Research Part C*, 184 (2026): 105506. [DOI](https://doi.org/10.1016/j.trc.2025.105506)
- Xinting Hu, **Bizhao Pang**, Sameer Alam, Mir Feroskhan. U-Safe: Urban air mobility safe integration into aerodrome via bio-inspired and reinforcement learning-based trajectory management. *Reliability Engineering & System Safety*, (2026): 113153. [DOI](https://doi.org/10.1016/j.ress.2026.113153).
- Mingcheng Zhang, **Bizhao Pang**, Chao Yan, Mir Feroskhan, Chen Lv. Real-time avoidance of building and dynamic geo-fencing for urban air mobility using deep reinforcement learning. *IEEE Transactions on Intelligent Transportation Systems* (2025). [DOI](https://doi.org/10.1109/TITS.2025.3589322).



## Selected Conference Papers

<sup>* Corresponding author</sup>

- **Bizhao Pang**, Mingcheng Zhang, Xinting Hu, Thinh Pham, Sameer Alam, Guglielmo Lulli. Constrained Multi-Agent Reinforcement Learning with MAF-Net for Safe Trajectory Planning. *25th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2026)*, Paphos, Cyprus, May 25–29, 2026. **(Oral)**
- **Bizhao Pang**, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli. Decentralized Deep Reinforcement Learning for Cooperative Multi-Agent Flight Trajectory Planning in Adverse Weather. *24th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2025)*, Detroit, Michigan, USA, May 19–23, 2025.
- **Bizhao Pang**, Xinting Hu, Yi Yang Poh, Kin Huat Low. Population density estimation for dynamic ground risk assessment of drone operations. *IEEE/AIAA Digital Avionics Systems Conference (DASC) 2023*, Barcelona, Spain.
- **Bizhao Pang**, Mingcheng Zhang, Chao Deng, Kin Huat Low. Investigation of flight technical error for UAV separation requirement. *AIAA Aviation Forum (AVIATION) 2022*.
- **Bizhao Pang**, C.H. John Wang, Kin Huat Low. Framework of level-of-autonomy-based concept of operations: UAS capabilities. *IEEE/AIAA Digital Avionics Systems Conference (DASC) 2021*.
- **Bizhao Pang**, Wei Dai, Thu Ra, Kin Huat Low. A concept of airspace configuration and operational rules for UAS. *IEEE/AIAA Digital Avionics Systems Conference (DASC) 2020*, San Antonio, TX, USA.
- **Bizhao Pang**, Ng Ee Meng, Kin Huat Low. UAV trajectory estimation and deviation analysis for contingency management. *AIAA Aviation Forum (AVIATION) 2020*, Reno, Nevada, USA.
- **Bizhao Pang**, Qingyu Tan, Kin Huat Low. A risk model based traffic network for adaptive urban airspace management. *AIAA Aviation Forum (AVIATION) 2020*, Reno, Nevada, USA.
- **Bizhao Pang**, Ng Ee Meng, Kin Huat Low. Contingency management of urban UTM based on airspace contexts. *ICAO UAS Industry Symposium 2019*, Montreal, Canada.
- Hu, Xinting, Yu Wu, and **Bizhao Pang\***. Path planning for drone delivery in dense building environments. *IEEE International Conference on Intelligent Transportation Systems (ITSC) 2023*, Bilbao, Spain, 24-28 September, 2023.
- Mingcheng Zhang, **Bizhao Pang\***, Duc-Thinh Pham, Vu N. Duong, Sameer Alam, Anh Tuan Luu. Scalable Multi-Agent Reinforcement Learning for Decentralized UAM Deconfliction Considering Downstream Impact. *IEEE 29th International Conference on Intelligent Transportation Systems (ITSC)*, Naples, Italy, 15–18 September, 2026. Accepted.





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

- *2020.08 – 2023.09*, Doctor of Philosophy (AI and Intelligent Transportation), Nanyang Technological University, Singapore  
- *2016.09 – 2019.06*, Master of Engineering (ATM and Operations Research), Civil Aviation University of China, Tianjin, China  
- *2012.09 – 2016.06*, Bachelor of Engineering (Air Transportation), Civil Aviation University of China, Tianjin, China



<span class='anchor' id='-work-experience'></span>
# 💼 Work Experience

- *2026.08 – Present*, **Tenure-track Assistant Professor**, The Hong Kong University of Science and Technology (Guangzhou), Guangzhou, China
  - Establishing the research group **Human–AI Collaborative Intelligence for Aviation Systems**.
- *2023.12 – 2026.08*, **Research Fellow**, Air Traffic Management Research Institute (ATMRI), NTU, Singapore
  - *Flexible Extended Arrival Management (FlexMAN) (Apr 2026 – Aug 2026)* — Team Lead: Led the development of human–AI hybrid automation for NextGen Air Traffic Management systems.
  - *AI-assisted Regional ATFM (Aug 2025 – Mar 2026)* — Tech Lead: Conceptualized and developed a distributed AI-assisted cross-border ATFM system for ASEAN.
  - *AI4ATM (Apr 2024 – Mar 2026)* — Team Lead: Led a cross-national team developing advanced AI models for resilient ATM under thunderstorms.
  - *UAM System Development (Dec 2023 – Apr 2024)* — Algorithm Scientist: Developed a safe and scalable AI-based UAM system for Singapore's highly urbanized airspace.
- *2019.08 – 2020.08*, **Research Associate**, Air Traffic Management Research Institute (ATMRI), NTU, Singapore  
  - *UTM System with AirMatrix Concept* — Developed a digital low-altitude urban airspace management system for UAM.  
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

- **May 2026**    **Constrained Multi-Agent Reinforcement Learning with MAF-Net for Safe Trajectory Planning**
  AAMAS 2026, Paphos, Cyprus
- **Feb 2026**    **Introduction and Demonstration of an AI-Assisted Regional ATFM Prototype**
  Singapore Airshow 2026, Singapore
- **May 2025**    **Multi-Agent Aircraft Trajectory Planning Using Decentralized MARL**
  University of Michigan, Ann Arbor, MI, USA
- **May 2025**    **Decentralized DRL for Cooperative Multi-Aircraft Trajectory Planning**
  AAMAS 2025, Detroit, MI, USA
- **Sep 2023**    **Population Density Estimation for Dynamic Ground-Risk Assessment of Drone Operations**
  IEEE/AIAA Digital Avionics Systems Conference (DASC) 2023, Barcelona, Spain
- **Dec 2022**    **Scientific Paper Writing and Response to Reviewers' Comments**
  Civil Aviation University of China (CAUC), Tianjin, China
- **Nov 2021**    **Risk Modelling and Assessment for UAM Operations in Urban Environments**
  Cranfield University, Online
- **Sep 2019**    **UAS Operations and Industry Perspectives**
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

#### UAM Traffic Management System

Safe and scalable AI-based UAM system for Singapore's urban airspace. Add your video or figure here.

*To add more showcase items: paste the HTML/Markdown blocks above and replace with your video IDs or image paths. Save your videos in* `images/` *or link to YouTube/Vimeo.*



<span class='anchor' id='-gallery'></span>
# 📷 Gallery

Photos from research, teaching, and daily life.

### 🔬 Research

![Research photo](images/gallery/research1.jpg)

Add caption for your photo

![Research photo](images/gallery/research2.jpg)

Add caption for your photo

### 📚 Teaching

![Teaching photo](images/gallery/teaching1.jpg)

Add caption for your photo

### 🌸 Daily Life

![Daily life photo](images/gallery/life1.jpg)

Add caption for your photo

*To add your photos: save images in* `images/gallery/` *and update the* `src` *paths and* `figcaption` *text above. Supported formats: jpg, png, webp.*

</div>
