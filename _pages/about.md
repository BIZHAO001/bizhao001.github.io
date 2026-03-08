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

I received my Ph.D. in Aerospace Engineering from **Nanyang Technological University** (NTU), Singapore. I am currently a Research Fellow at the Air Traffic Management Research Institute (ATMRI), NTU, where I previously worked as a Research Associate. Before that, I received my Master of Engineering in Air Traffic Management and Operations Research and my Bachelor of Engineering in Air Transportation from the Civil Aviation University of China (CAUC). Together, these background built a strong foundation in airport, airline, and air traffic control operations, mathematical modeling and optimization, which I now combine with AI for **next-generation ATM** and emerging **Advanced Air Mobility** (AAM) systems.

My research centers on AI and optimization for safety-critical air transportation systems. The objective is to develop **human-centered AI** and **intelligent decision-support** methods for safer, more efficient, and more resilient AAM and ATM operations. My research interests include optimization under uncertainty, multi-agent systems, safe reinforcement learning, human–AI teaming, and large language models for safety-critical and autonomous trasportation systems. 

**Research Summary**
- **Systems and stakeholders:** Contributed to deployable prototypes for low-altitude UAM traffic management, resilient ATM decision support under thunderstorms, and an ongoing AI-Assisted Regional ATFM system.
- **Peer-reviewed publications:** 30+ top journal and conference papers (**15 first authored**), including *Transportation Research Part C/E*, *Reliability Engineering & System Safety*, *Advanced Engineering Informatics*, IEEE T-ITS/TVT; AAMAS 2026 (oral). **800+ citations** on Google Scholar.
- **Leadership and teamwork:** Technical lead (7-person team) for AI-assisted regional ATFM (Aug 2025 – now); team lead (3-person team) for Singapore–Italy AI4ATM project (Apr 2024 – now).
- **Funding and grants:** Experience in national/agency programs (CAAS, NRF, A*STAR, Singapore, NSF China) and grant proposal writing (lead writer / technical coordinator roles listed below).
- **Teaching and mentoring:** Teaching assistant experience; mentored 2 Ph.D. students, 3 M.Sc. students, and 5 undergraduate final-year projects; co-authored 10+ peer-reviewed publications with students.


<span class='anchor' id='-news'></span>
# 🔥 News

- *2026.01*: &nbsp;🎉 AAMAS 2026 full paper accepted for Oral presentation on constrained multi-agent reinforcement learning for safe trajectory planning.
- *2025.05*: &nbsp;🎉 Extended abstract accepted at AAMAS 2025 on decentralized deep reinforcement learning for cooperative multi-agent flight trajectory planning in adverse weather.
- *2023.12*: &nbsp;🎉 Joined ATMRI as Research Fellow. Leading AI-assisted Regional ATFM and AI4ATM projects.
- *2023.10*: &nbsp;🎉 Successfully defended Ph.D. thesis on risk-based route planning and decision-making for UAS in urban environments.

<span class='anchor' id='-publications'></span>
# 📝 Publications

## Recent Highlights

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">AI for ATM</span>
    <img src="images/BIZHAO/AAMAS2026.png" alt="MAF-Net for safe trajectory planning">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;">Constrained Multi-Agent Reinforcement Learning with MAF-Net for Safe Trajectory Planning</h3>
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
    <span class="badge">TRC 2026</span>
    <img src="images/BIZHAO/TRC2026.png" alt="U-Aerodrome airspace reconfiguration for UAM at aerodrome">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;">U-Aerodrome: Data-driven and risk-bounded airspace reconfiguration for safe integration of urban air mobility at aerodrome</h3>
    <p style="margin: 0.5em 0;">Xinting Hu, <strong>Bizhao Pang</strong>, Sameer Alam, Mir Feroskhan</p>
    <p style="margin: 0.5em 0;"><em>Transportation Research Part C: Emerging Technologies</em></p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.trc.2025.105506">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>U-Aerodrome, a data-driven and risk-bounded airspace reconfiguration framework designed to support the safe and flexible integration of UAM operations near controlled aerodromes.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">RESS 2026</span>
    <img src="images/BIZHAO/RESS2026.png" alt="U-SAFE trajectory planning for UAM at aerodrome">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;">U-SAFE: UAM Safe Integration into Aerodrome via Bio-Inspired and Reinforcement Learning-Based Trajectory Planning</h3>
    <p style="margin: 0.5em 0;">Xinting Hu, <strong>Bizhao Pang</strong>, Sameer Alam, Mir Feroskhan</p>
    <p style="margin: 0.5em 0;"><em>Reliability Engineering &amp; System Safety</em> (RESS), 2026.</p>
    <ul style="margin: 0.5em 0;">
      <li>An integrated trajectory planning framework that combines proactive risk-based planning with reactive inflight conflict resolution near aerodromes.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">AEI 2025</span>
    <img src="images/BIZHAO/AEI2025.png" alt="Multi-aircraft trajectory planning under thunderstorms">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;">A multi-aircraft co-operative trajectory planning model under dynamic thunderstorm cells using decentralized deep reinforcement learning</h3>
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
    <h3 style="margin-top: 0;">Stochastic route optimization under dynamic ground risk uncertainties for safe drone delivery operations</h3>
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
    <h3 style="margin-top: 0;">Chance-constrained UAM traffic flow optimization with fast disruption recovery under uncertain waypoint occupancy time</h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Kin Huat Low, Vu N. Duong</p>
    <p style="margin: 0.5em 0;"><em>Transportation Research Part C: Emerging Technologies</em>, 161 (2024): 104547.</p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.trc.2024.104547">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>A chance-constrained UTFM model is developed to optimize UAM traffic flow.</li>
      <li>A hierarchical stochastic search algorithm is designed to solve the UTFM model.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <span class="badge">RESS 2022</span>
    <img src="images/BIZHAO/RESS2022.PNG" alt="UAV path optimization with third-party risk assessment">
  </div>
  <div class="paper-box-text">
    <h3 style="margin-top: 0;">UAV path optimization with an integrated cost assessment model considering third-party risks in metropolitan environments</h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Xinting Hu, Wei Dai, Kin Huat Low</p>
    <p style="margin: 0.5em 0;"><em>Reliability Engineering &amp; System Safety</em>, 2022: 108399.</p>
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
    <h3 style="margin-top: 0;">Adaptive conflict resolution for multi-UAV 4D routes optimization using stochastic fractal search algorithm</h3>
    <p style="margin: 0.5em 0;"><strong>Bizhao Pang</strong>, Kin Huat Low, Chen Lv</p>
    <p style="margin: 0.5em 0;"><em>Transportation Research Part C: Emerging Technologies</em>, 2022: 103666.</p>
    <p style="margin: 0.5em 0;"><a href="https://doi.org/10.1016/j.trc.2022.103666">Paper</a></p>
    <ul style="margin: 0.5em 0;">
      <li>An adaptive UAV conflict resolution framework for 4D route optimization that integrates scheduling, speed adjustment, and rerouting strategies.</li>
    </ul>
  </div>
</div>

## Journal Papers

- **Bizhao Pang**, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli. In-flight multi-aircraft trajectory replanning under dynamic thunderstorm cells using decentralized deep reinforcement learning. *Advanced Engineering Informatics*, 65 (2025): 103157. 
- **Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low. Stochastic route optimization under dynamic ground risk uncertainties for safe drone delivery operations. *Transportation Research Part E*, 192 (2024): 103717. 
- **Bizhao Pang**, Kin Huat Low, Vu N. Duong. Chance-constrained UAM traffic flow optimization with fast disruption recovery under uncertain waypoint occupancy time. *Transportation Research Part C*, 161 (2024): 104547.
- **Bizhao Pang**, Kin Huat Low, Chen Lv. Adaptive conflict resolution for multi-UAV 4D routes optimization using stochastic fractal search algorithm. *Transportation Research Part C*, 2022.
- **Bizhao Pang**, Xinting Hu, Wei Dai, Kin Huat Low. UAV path optimization with an integrated cost assessment model considering third-party risks in metropolitan environments. *Reliability Engineering & System Safety*, 2022: 108399.
- **Bizhao Pang**, Wei Dai, Xinting Hu, Fuqing Dai, Kin Huat Low. Multiple air route crossing waypoints optimization via artificial potential field method. *Chinese Journal of Aeronautics*, 34(4), 2021.
- Xinting Hu, **Bizhao Pang**, Sameer Alam, Mir Feroskhan. U-Aerodrome: Data-driven and risk-bounded airspace reconfiguration for safe integration of Urban Air Mobility at aerodrome. *Transportation Research Part C* (2026), Accepted. (SCI, IF: 7.9)
- Mingcheng Zhang, **Bizhao Pang**, Chao Yan, Mir Feroskhan, Chen Lv. Real-time avoidance of building and dynamic geo-fencing for urban air mobility using deep reinforcement learning. *IEEE Transactions on Intelligent Transportation Systems*, (2025). (SCI, IF: 8.4)
- Wei Dai, **Bizhao Pang**, Kin Huat Low. Conflict-free four-dimensional path planning for urban air mobility considering airspace occupancy. *Aerospace Science and Technology*, 119 (2021): 107154. (SCI, IF: 5.8)
- Xinting Hu, **Bizhao Pang**, Fuqing Dai, Kin Huat Low. Risk assessment model for UAV cost-effective path planning in urban environments. *IEEE Access*, 8 (2020): 150162–150173. (SCI, IF: 3.6)
- Yu Wu, Kin Huat Low, **Bizhao Pang**, Qingyu Tan. Swarm-based 4D path planning for drone operations in urban environments. *IEEE Transactions on Vehicular Technology*, 70(8), 7464–7479, 2021. (SCI, IF: 7.1)
- Sen Du, Gang Zhong, Fei Wang, **Bizhao Pang**, Honghai Zhang, Qingyu Jiao. Safety risk modelling and assessment of civil unmanned aircraft system operations: A comprehensive review. *Drones*, 8(8), 354. (SCI, IF: 4.8)
- Fuqing Dai, **Bizhao Pang**, Yuandi Zhao. Optimization model of air route crossing angles with varying preferences. *Journal of Southwest Jiaotong University*, 54(6), 2019. (EI, in Chinese)
- Fuqing Dai, **Bizhao Pang**, Zhi Ren, Yuandi Zhao. Congestion risk on airway crossing point for tube-type operation. *Journal of Wuhan University of Technology*, 40(2), 2018. (In Chinese)
- Fuqing Dai, **Bizhao Pang**, Jie Yuan, Yuandi Zhao. Air-rail traffic flow distribution model based on super-road network. *Journal of Wuhan University of Technology (Transportation Science and Engineering)*, 41(5), 2017. (In Chinese)

## Conference Papers

- **Bizhao Pang**, Mingcheng Zhang, Xinting Hu, Thinh Pham, Sameer Alam, Guglielmo Lulli. Constrained Multi-Agent Reinforcement Learning with MAF-Net for Safe Trajectory Planning. *25th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2026)*, Paphos, Cyprus, May 25–29, 2026. **Full paper, Oral presentation.**
- **Bizhao Pang**, Xinting Hu, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli. Decentralized Deep Reinforcement Learning for Cooperative Multi-Agent Flight Trajectory Planning in Adverse Weather. *24th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2025)*, Detroit, Michigan, USA, May 19–23, 2025.
- **Bizhao Pang**, Xinting Hu, Yi Yang Poh, Kin Huat Low. Population density estimation for dynamic ground risk assessment of drone operations. *IEEE/AIAA DASC 2023*, Barcelona.
- **Bizhao Pang**, Mingcheng Zhang, Chao Deng, Kin Huat Low. Investigation of flight technical error for UAV separation requirement. *AIAA AVIATION 2022*.
- **Bizhao Pang**, C.H. John Wang, Kin Huat Low. Framework of level-of-autonomy-based concept of operations: UAS capabilities. *IEEE/AIAA DASC 2021*.
- **Bizhao Pang**, Wei Dai, Thu Ra, Kin Huat Low. A concept of airspace configuration and operational rules for UAS. *IEEE/AIAA DASC 2020*.
- **Bizhao Pang**, Ng Ee Meng, Kin Huat Low. UAV trajectory estimation and deviation analysis for contingency management. *AIAA AVIATION 2020*, Nevada.
- **Bizhao Pang**, Qingyu Tan, Kin Huat Low. A risk model based traffic network for adaptive urban airspace management. *AIAA AVIATION 2020*, Nevada.
- **Bizhao Pang**, Ng Ee Meng, Kin Huat Low. Contingency management of urban UTM based on airspace contexts. *ICAO UAS Industry Symposium*, Montreal, 2019.
- Xinting Hu, **Bizhao Pang**, Mingcheng Zhang, Sameer Alam, Guglielmo Lulli. An independent DDPG method with shared neural networks for cooperative multi-aircraft rerouting. *37th International Conference on Tools with Artificial Intelligence (ICTAI)*, Athens, Greece, November 2025.
- Xinting Hu, **Bizhao Pang**, Mir Feroskhan. Airspace reconfiguration for UAM: A spatial-temporal analysis within aerodromes. *IEEE 27th International Conference on Intelligent Transportation Systems (ITSC)*, Edmonton, Canada, 2024.
- Xinting Hu, Yu Wu, **Bizhao Pang**. Path planning for drone delivery in dense building environments. *IEEE 26th International Conference on Intelligent Transportation Systems (ITSC)*, Bilbao, Spain, 2023.
- Lewis Lee, **Bizhao Pang**, Kin Huat Low. Environmental data analytics for safe drone operations in urban environments. *AIAA AVIATION 2022*.
- Xinting Hu, **Bizhao Pang**, Kin Huat Low. Wind patterns analysis for safe UAV operations using statistical approaches. *IEEE/AIAA DASC 2022*.
- Wei Dai, **Bizhao Pang**, Kin Huat Low. Accessibility analysis of UAVs near airports with a 4D airspace management concept. *IEEE/AIAA DASC 2020*, San Antonio.

## Forthcoming Publications

- **Bizhao Pang**, Mingcheng Zhang, Xinting Hu, Sameer Alam, Guglielmo Lulli. Constrained Multi-Agent Reinforcement Learning with Multi-Head Action Filtering for Safe Aircraft Trajectory Planning (2026), Under 1st revision.
- **Bizhao Pang**, Mingcheng Zhang, Sameer Alam. LLM-Guided Multi-Agent Reinforcement Learning with Safety Constraints (2026), Working paper.
- Xinting Hu, **Bizhao Pang**, Sameer Alam, Mir Feroskhan. U-SAFE: UAM Safe Integration into Aerodrome via Bio-Inspired and Reinforcement Learning-Based Trajectory Planning (2026), Under 1st revision.

<span class='anchor' id='-honors-and-awards'></span>
# 🎖 Honors and Awards

- *2020* NTU Research Student Scholarship, Nanyang Technological University
- *2019* Best Master Thesis Award (Top 1%), Tianjin, China
- *2019* Excellent Master Graduate Award, CAUC
- *2018* Boeing Scholarship (Top 1%)
- *2018* Excellent Postgraduate Student Certificate, CAUC
- *2015–2018* A-Level Graduate Scholarship (3 consecutive years), CAUC
- *2017* National Winner Award, Internet Innovation and Entrepreneurship Competition
- *2014–2015* University Single Subject Scholarship of Innovation (2 consecutive years), CAUC
- *2013* Excellent University Student Leader Honor Certificate, CAUC

<span class='anchor' id='-education'></span>
# 📖 Education

- *2020.08 – 2023.10*, Doctor of Philosophy in Aerospace Engineering (AI and Intelligent Transportation), Nanyang Technological University, Singapore  
  - Thesis: Risk-based route planning and decision-making for UAS in urban environments  
  - Supervisors: Prof. Kin Huat Low, Prof. Vu N. Duong; Co-supervisor: Prof. Chen Lv
- *2016.08 – 2019.03*, Master of Engineering (ATM and Mathematical Optimization), Civil Aviation University of China, Tianjin, China  
  - Thesis: Large-scale air route network modelling and optimization  
  - Supervisor: Prof. Fuqing Dai
- *2012.08 – 2016.06*, Bachelor of Engineering in Transportation (Air Transportation Fundamentals), Civil Aviation University of China, Tianjin, China  
  - Thesis: Unmanned aerial vehicle path planning using dynamic programming method

<span class='anchor' id='-work-experience'></span>
# 💼 Work Experience

- *2023.12 – Present*, **Research Fellow**, Air Traffic Management Research Institute (ATMRI), NTU, Singapore  
  - *AI-assisted Regional ATFM (Aug 2025 – Now)* — Tech Lead: Conceptualizing and developing a distributed AI-assisted cross-border ATFM system for ASEAN.  
  - *AI4ATM (Apr 2024 – Now)* — Team Lead: Leading a cross-national team developing advanced AI models for resilient ATM under thunderstorms.  
  - *UAM System Development (Dec 2023 – Apr 2025)* — Algorithm Scientist: Developed a safe and scalable AI-based UAM system for Singapore's highly urbanized airspace.
- *2019.04 – 2020.08*, **Research Associate**, Air Traffic Management Research Institute (ATMRI), NTU, Singapore  
  - *UTM System with AirMatrix Concept* — Team Lead: Developed a digital low-altitude urban airspace management system for UAM.  
  - *Risk-based UAM Concept and Algorithm* — Algorithm Engineer: Developed risk-based concepts and planning algorithms for safe UAM operations.

<span class='anchor' id='-research-projects'></span>
# 🔬 Research Projects

**AI for Resilient ATM and Cross-Border ATFM Systems**
- *AI-Assisted Cross-Border Air Traffic Flow Management* (NRF, Singapore) Aug 2025 – Present — Technical Lead, AI Scientist (7 team members). Leading multidisciplinary research, coordinating with aviation authority and industry stakeholders.
- *Singapore–Italy Collaborative Project: AI for Air Traffic Management (AI4ATM)* Apr 2024 – Present — Team Lead, AI Scientist (3 team members). Developing AI algorithms for multi-aircraft separation assurance, thunderstorm avoidance, and sequencing.
- *Airspace and Air Traffic Flow Modeling and Optimization* (NSF, China) Sep 2016 – Mar 2019 — Data and Algorithm Engineer. Chinese Air Route Network Optimization; Terminal Airspace Optimization for Sustainable Aviation.

**Low-Altitude UAM and AAM: Concepts, Research, and Development** (NRF, Singapore)
- *Scalable and Robust UAM Scheduling and Disruption Recovery* Apr 2021 – Mar 2024 — Team Lead, AI Algorithm Researcher.
- *Risk-based UAM Path Optimization Using Machine Learning* Jan 2022 – Mar 2024 — Team Lead, AI Algorithm Researcher.
- *UTM Platform Development with AirMatrix Concept* Apr 2019 – Mar 2023 — Algorithm Engineer.
- *UTM and ATM Integration in Low-Altitude Urban Airspace* Apr 2019 – Mar 2021 — Data Engineer.

<span class='anchor' id='-showcase'></span>
# 🎬 Showcase

*This section is ready for you to add videos and figures to showcase your work. See instructions below.*

To add a **video** (e.g., from YouTube or a local file):

```html
<div class="showcase-item">
  <h4>Project Title</h4>
  <p>Brief description of the work.</p>
  <!-- YouTube embed -->
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
  <!-- Uncomment and add your YouTube embed:
  <div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
  </div>
  -->
</div>

*To add more showcase items: paste the HTML/Markdown blocks above and replace with your video IDs or image paths. Save your videos in `images/` or link to YouTube/Vimeo.*
