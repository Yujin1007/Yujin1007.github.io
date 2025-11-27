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

<br><br>
I study methods at the interface of machine learning and control, including reinforcement learning, imitation learning, model predictive control and dynamic mode decomposition. My main interest is in approaches that build on mathematical structure and optimization principles, enabling both interpretability and efficiency in decision-making and control. My research aims to develop interpretable and theoretically grounded methods for decision-making in partially observable, real-world systems.

I am a Ph.D. student in Computer Science at Cornell University, working with [Sarah Dean](https://sdean.website/). Before joining Cornell, I was a research scientist at the Korea Institute of Science and Technology (KIST). I received my M.S. from Korea University and my B.S. from the University of Seoul.

<!-- <span class='anchor' id='educations'></span> -->
# 📖 Educations
- Ph.D. Student in Computer Science, *Aug. 2024 - Present*
  - Cornell University
  - Advisor: [Sarah Dean](https://sdean.website/)
- M.S. in Electrical and Computer Engineering, *Mar. 2021 - Aug. 2023*
  - Major : Control, Robotics and Systems. Korea University (GPA: 4.39/4.5)
  - Research Scholarship from Hyundai Motor Group, *Mar. 2021 - Dec. 2022*, 
- B.S. in Electrical and Computer Engineering, *Mar. 2017 - Feb. 2021*
  - University of Seoul. (GPA: 4.0/4.5)
  - Research Scholarship from Hyundai Motor Group, *Sep. 2019 - Dec. 2020*

<!-- <span class='anchor' id='news'></span> -->

<!-- # 🔥 News
- *Sep. 2023*: &nbsp;🎉🎉 Paper published at electronics journal
- *Aug. 2023*: &nbsp;🎉🎉 Completed my M.S degree!! 
- *Jan. 2022*: &nbsp;🎉🎉 Started working at KIST.  -->

<!-- <span class='anchor' id='projects'></span> -->

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><img src='images/recon_every.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Sparse-to-Field Reconstruction via Stochastic Neural Dynamic Mode Decomposition](http://arxiv.org/abs/2511.20612)
- Proposes a probabilistic DMD–Neural ODE model that reconstructs continuous spatiotemporal fields from only 10% sparse observations with uncertainty quantification. 
- Recovers interpretable Koopman modes and continuous-time eigenvalues, learns distributions over dynamics across realizations.
- Submitted to L4DC 2026, [project website](https://sdean-group.github.io/Stochastic-NODE-DMD/)
<!-- - Learn skills without human intervention to enhance the autonomy of our robot manipulator. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/mppi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Single-Instance Sampling for Computationally Efficient and Accurate Real-Time Task Space MPPI Control](https://ieeexplore.ieee.org/document/11219213)
<!-- [Autonomous Robot Manipulator Operation for Intricate Object Handling] (https://arxiv.org/abs/2412.08522) -->
<!-- - Challenge to long-horizon manipulator operation using reinforcement learning. -->
- Real-time MPPI controller that achieves high-frequency task-space manipulation by redesigning sampling and horizon structures. 
- Establish that constant-perturbation rollouts remain theoretically compatible with MPPI weighting.
- Published in the Proceedings of IEEE Transactions on Robotics, [supplementary video](https://www.youtube.com/watch?v=lqLPyxnlV5k)
<!-- - Learn skills without human intervention to enhance the autonomy of our robot manipulator. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/alltasks.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Distilling Realizable Students from Unrealizable Teachers](https://arxiv.org/abs/2505.09546)
<!-- [Autonomous Robot Manipulator Operation for Intricate Object Handling] (https://arxiv.org/abs/2412.08522) -->
<!-- - Challenge to long-horizon manipulator operation using reinforcement learning. -->
- Policy distillation under asymmetric imitation learning setting. 
- Propose two new IL/RL algorithms robust to state aliasing.
- Published in the Proceedings of IROS 2025, [project website](https://portal-cornell.github.io/CritiQ_ReTRy/)
<!-- - Learn skills without human intervention to enhance the autonomy of our robot manipulator. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/valve.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Subspace-wise Hybrid RL for Articulated Object Manipulation](https://arxiv.org/abs/2412.08522)
<!-- - Challenge to long-horizon manipulator operation using reinforcement learning. -->
- Develop skills for operating equipment (e.g., valve, switch, gear lever...) at industrial sites with a manipulator.
- Learn skills while minimizing human-engineered features using reinforcement learning.
- Submitted to ICRA 2026
<!-- - Learn skills without human intervention to enhance the autonomy of our robot manipulator. -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/door.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Whole-body motion planning of dual-arm mobile manipulator for compensating for door reaction force](https://openreview.net/forum?id=A8MTF3nTO5)
  - Address challenges of door traversal motion planning
  - Unified framework for door traversal, from approaching, opening, passing through, and closing the door with dual-armed mobile manipulator  
  - Decision making for optimal contact point planning with RL.
  - Presented in ICRA 2025 workshop
  <!-- - [Paper](https://openreview.net/forum?id=A8MTF3nTO5) publishsed at ICRA 2024: 2nd Workshop on Mobile Manipulation and Embodied Intelligence (MOMA.v2) -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/cer_highway.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A reinforcement learning approach to dynamic trajectory optimization with consideration of imbalanced sub-goals in self-driving vehicles](https://www.mdpi.com/2076-3417/14/12/5213)
- Challenge to skewed sub-goal distribution for goal-conditioned RL controller. 
- Enable adaptive sub-goal planning and efficient reward learning via MPC-synchronized rewards.
- Published in the Proceedings of Applied Sciences
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/hybrid_highway.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Reinforcement Learning for Autonomous Vehicle using MPC in Highway Situation](https://ieeexplore.ieee.org/abstract/document/9748810).
- Addresses the challenge of reward shaping for continuous RL controllers by using MPC reference.
- Published in the Proceedings of ICEIC 2022
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><img src='images/f1.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
F1tenth Virtual Race competition
- Compete to race with RL controller. 
- Participated in IROS, 2021 and ICRA, 2022
- Won 3rd prize
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/pallet_loading.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Pallet loading problem with robot manipulator
- Employed decision-making techniques using Reinforcement Learning (RL) to optimize box layout on pallets for varying box sizes.
- Implemented PPO.
- Executed pallet loading operations based on the optimized layout using the Doosan Robotics M1013 robot manipulator.
- Successfully applied this solution in a real-world scenario.
</div>
</div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMECS 2023</div><img src='images/lanechange.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Lane change decision making on crowded highway environment
- Establishing robust statistical criteria for lane change decisions in driving, grounded in human data.
- Poster session at EMECS, 2023
</div>
</div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><img src='images/transformer.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transformer model from scratch! 
- Generate Korean-English translator. 
</div>
</div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">SMP 2020</div><img src='images/smp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Smart Mobility Project - Fail safe system development
- Development of a fail-safe system for self-driving cars.
- Utilization of V2V sensor data for operation during sensor failure.
- [Presentation](https://youtu.be/zKZ-OdYeDTw?si=BmTPEP5J4DMhe5em)
</div>
</div> -->

<!-- <span class='anchor' id='publications'></span> -->
<!-- # 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/cer_highway.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
A Reinforcement Learning Approach to Dynamic Trajectory Optimization with Consideration of Imbalanced Sub-Goals in Self-Driving Vehicles
- Under Review

**Yujin Kim**, Sun-Ho Jang, Woo-Jin Ahn, Myo-Taeg Lim, Dong-Sung Pae

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICEIC 2022</div><img src='images/hybrid_highway.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reinforcement Learning for Autonomous Vehicle using MPC in Highway Situation](https://ieeexplore.ieee.org/abstract/document/9748810)

**Yujin Kim**, Dong-Sung Pae, Sun-Ho Jang, Seong-Woo Kang, Myo-Taeg Lim

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMECS 2023</div><img src='images/lanechange1.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="../images/hyundai.pdf">Prediction of estimated lane change distance on highway: based on traffic information</a>

**Yujin Kim**, Seok Youl Yang, Myo-Taeg Lim

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronics 2023</div><img src='images/stable.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stable and Efficient Reinforcement Learning Method for Avoidance Driving of Unmanned Vehicles](https://www.mdpi.com/2079-9292/12/18/3773)

Sun-Ho Jang, Woo-Jin Ahn, **Yu-Jin Kim**, Hyung-Gil Hong, Dong-Sung Pae, Myo-Taeg Lim

</div>
</div> -->

<!-- <span class='anchor' id='awards'></span> -->

# 🎖 Honors and Awards
- *2025*                    IROS-SDC Travel Award.
- *2024*                    Student Travel Grant, ICRA 2024 (MOMA.v2 Workshop).
- *Sep. 2018 - Dec. 2022,*  Full Scholarship for Selected Research Student, Hyundai Motor Company.
- *May 2022,*               10th F1TENTH Autonomous Racing Grand Prix, 3rd Place, ICRA 2022.
- *Spring 2018,*            Scholarship for Excellent Achievement, University Of Seoul. 
- *Jul. 2018,*              2018 Intelligent Model Car Competition, 3rd Place, Hanyang University. 
- *Jul. 2017,*              14th Microrobot Competition, Special Award for Women Engineer, Dankook University.

<!-- <span class='anchor' id='works'></span> -->

# 💻 Work Experience
- *Jan. 2023 - 2024*, [Korea Institute of Science and Technology](https://eng.kist.re.kr/eng/index.do), Republic of Korea.
- *Jul. 2019*, [Hyundai Motor Group](https://www.hyundaimotorgroup.com/main/mainRecommend), Republic of Korea.