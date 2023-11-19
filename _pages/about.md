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

<br><br><br>
My research interest lies in the area of <b>Reinforcement Learning</b>, both practical applications and theoretical perspectives.
I focus on solving sequential decision-making problems for real-world autonomous learning systems!
These are the questions that I am digging these days.

<span style="font-size: 18px;">1️⃣ How can an agent acquire skills with minimal (or without) human-engineered intervention?</span>

<span style="font-size: 18px;">2️⃣ How can an agent acquire general-purpose skills to efficiently solve practical, long-horizon tasks?</span>

<span style="font-size: 18px;">3️⃣ What are the key differences that distinguish AI agents from humans in the process of learning new skills? What aspects of human learning can AI systems leverage?</span>

I am a research scientist at the Korea Institute of Science and Technology [(KIST)]( https://eng.kist.re.kr/eng/index.do) under the supervision of a senior researcher, [Yisoo Lee](https://sites.google.com/view/kist-arc/home/people?authuser=0). Before that, I received my M.S. from Korea University under the supervision of Professor [Myo-Taeg Lim](http://cml.korea.ac.kr/), where I studied reinforcement learning and path planning for autonomous driving. I received my B.S. from the University of Seoul. I finished internship at Hyundai Motor Group, working on developing autonomous driving decision-making and control.

<!-- <span class='anchor' id='educations'></span> -->
# 📖 Educations
- M.S. in Electrical and Computer Engineering, *Mar. 2021 - Aug. 2023*
  - Major : Control, Robotics and Systems. Korea University (GPA: 4.39/4.5)
  - Research Scholarship from Hyundai Motor Group, *Mar. 2021 - Dec. 2022*, 
- B.S. in Electrical and Computer Engineering, *Mar. 2017 - Feb. 2021*
  - University of Seoul. (GPA: 4.0/4.5)
  - Research Scholarship from Hyundai Motor Group, *Sep. 2019 - Dec. 2020*

<!-- <span class='anchor' id='news'></span> -->

# 🔥 News
- *Sep. 2023*: &nbsp;🎉🎉 Paper published at electronics journal
- *Aug. 2023*: &nbsp;🎉🎉 Completed my M.S degree!! 
- *Jan. 2022*: &nbsp;🎉🎉 Started working at KIST. 

<!-- <span class='anchor' id='projects'></span> -->

# 👩🏼‍💻 ̆̈Projects
<div class='paper-box'><div class='paper-box-image'><div><img src='images/valve.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Autonomous Robot Manipulator Operation for Intricate Object Handling
- ON GOING PROJECT! 
  - Challenge to long-horizon manipulator operation using reinforcement learning.
  - Develop skills for operating equipment (e.g., valve, switch, gear lever...) at industrial sites with a manipulator.
  - Learn skills while minimizing human-engineered features.
  - Learn skills without human intervention to enhance the autonomy of our robot manipulator.
  - Implemented TQC.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/cer_highway.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Classified Experience Replay
- Challenge to skewed sub-goal distribution for goal-conditioned RL controller. 
- Implemented TQC. 
- Paper under review
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/hybrid_highway.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Learning to drive in highway with guided RL controller.
- Addresses the challenge of reward shaping for continuous RL controllers by using MPC reference.
- Implemented DDPG.
- Paper published at ICEIC, 2022 (oral).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/f1tenth.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
F1tenth Virtual Race competition
- Compete to race with RL controller. 
- Participated in IROS, 2021 and ICRA, 2022
- Won 3rd prize
- Implemented PPO, DQN.
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
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMECS 2023</div><img src='images/lanechange.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Lane change decision making on crowded highway environment
- Establishing robust statistical criteria for lane change decisions in driving, grounded in human data.
- Poster session at EMECS, 2023
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/transformer.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transformer model from scratch! 
- Generate Korean-English translator. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SMP 2020</div><img src='images/smp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Smart Mobility Project - Fail safe system development
- Development of a fail-safe system for self-driving cars.
- Utilization of V2V sensor data for operation during sensor failure.
- [Presentation](https://youtu.be/zKZ-OdYeDTw?si=BmTPEP5J4DMhe5em)
</div>
</div>

<!-- <span class='anchor' id='publications'></span> -->
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/cer_highway.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Classified Experience Replay: The Off-Policy Reinforcement Learning Method and Dynamic Trajectory Planning for Autonomous Driving
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
</div>

<!-- <span class='anchor' id='awards'></span> -->

# 🎖 Honors and Awards
- *Spring 2018,*            Scholarship for Excellent Achievement, University Of Seoul. 
- *Sep. 2018 - Dec. 2022,*  Full Scholarship for Selected Research Student, Hyundai Motor Company.
- *May 2022,*               10th F1TENTH Autonomous Racing Grand Prix, 3rd Place, ICRA 2022.
- *Jul. 2018,*              2018 Intelligent Model Car Competition, 3rd Place, Hanyang University. 
- *Jul. 2017,*              14th Microrobot Competition, Special Award for Women Engineer, Dankook University.

<!-- <span class='anchor' id='works'></span> -->

# 💻 Work Experience
- *Jan. 2023 - now*, [Korea Institute of Science and Technology](https://eng.kist.re.kr/eng/index.do), Republic of Korea.
- *Jul. 2019*, [Hyundai Motor Group](https://www.hyundaimotorgroup.com/main/mainRecommend), Republic of Korea.