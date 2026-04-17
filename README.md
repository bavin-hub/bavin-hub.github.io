## About Me

I’m a Master’s student in Mechanical Engineering at Carnegie Mellon University and a researcher at AirLab, where I focus on building intelligent autonomous systems that operate reliably in real-world environments. My work lies at the intersection of control theory and learning-based approaches, particularly reinforcement learning and multi-agent coordination, with an emphasis on safety, robustness, and decision-making under uncertainty. I’m especially interested in bridging the gap between theory and deployment—developing methods that not only perform well in simulation but can be transferred effectively to physical systems. This includes tackling challenges in autonomous navigation, system reliability, and scalable coordination among multiple agents. I hold a Bachelor’s degree in Mechanical Engineering from SSN College of Engineering (Chennai, India), where I developed a strong foundation in robot dynamics, kinematics, and control. This background continues to shape my approach to designing systems that are both principled and practical. Overall, I’m driven by the goal of enabling autonomous systems to perceive, adapt, and collaborate seamlessly in complex, dynamic environments.

---

## Research & Professional Experience

### AI & Robotics Engineer — Skytex Unmanned Aerial Solutions
**Bengaluru, India · Jul 2023 – Jul 2025**

A two-year industry research role developing full-stack autonomy for unmanned aerial vehicles across three concurrent programs.

---

#### Cactus Swarm — Decentralized Multi-Agent VTOL UAV Swarm

Autonomous UAV swarms have applications in disaster response, environmental monitoring, and distributed logistics, where scalable coordination can significantly improve efficiency and safety. This project aimed to design and deploy a fully decentralized multi-agent VTOL UAV swarm capable of robust, real-time coordination without centralized control.

Designed and deployed a decentralized multi-agent VTOL UAV swarm demonstrating emergent behaviors including flocking, schooling, foraging, and coordinated payload delivery. Evaluated system performance through field tests, confirming stable flight autonomy at scale and reliable inter-agent coordination under communication constraints.

- Proposed a **vector field-based guidance algorithm** enabling scalable and collision-free coordinated swarm flight  
- Architected a real-time **MAVLink + ROS2 + XRCE-DDS** communication stack to support low-latency, fully autonomous operations  
- Achieved sustained autonomous flight at altitudes up to **2 km** with **12 km endurance**, validated through outdoor test missions  
- Developed a web-based Ground Control Station (GCS) for real-time mission planning, telemetry visualization, and system monitoring  
- Led the design and implementation of swarm coordination algorithms and integrated the communication stack across all agents  

![Swarm](/assets/img/swarm.jpg)

---

#### Ghost LM — Autonomous Loitering Munition

Autonomous loitering systems can enhance precision engagement while reducing operator workload in time-sensitive missions. This project aimed to design a loitering munition platform with robust guidance, adaptive mission management, and operator-in-the-loop control to ensure flexibility and accountability in dynamic environments.

Designed guidance and mission management algorithms for an autonomous loitering munition platform, emphasizing operator-in-the-loop control and dynamic retargeting. Evaluated system performance through simulated and controlled tests, demonstrating reliable target reacquisition, real-time mission updates, and improved decision latency.

- Developed pre-coordinated and dynamic strike algorithms with real-time mission update capability  
- Integrated computer vision pipelines for target detection, tracking, and strike decision verification  
- Built a mission-specific Ground Control Station (GCS) supporting dynamic replanning and operator-assisted strike authorization  
- Validated system responsiveness and targeting accuracy under varying mission scenarios  
- Led the development of guidance logic and contributed to vision-system integration and GCS design  

![Loitering Munition](/assets/img/lm.jpg)

---

#### Bumblebee — Miniature Autonomous Quadrotor for GPS-Denied Environments

Reliable navigation in GPS-denied environments is critical for applications such as search and rescue, infrastructure inspection, and exploration in complex terrain. This project aimed to develop a palm-sized quadrotor capable of fully autonomous, obstacle-aware navigation in cluttered environments without reliance on external positioning systems.

Built a compact quadrotor platform (Jetson Orin NX) capable of autonomous flight in GPS-denied environments such as forests and urban canyons. Evaluated system performance through indoor and outdoor tests, demonstrating robust localization, consistent obstacle avoidance, and effective area coverage under constrained sensing and compute resources.

- Integrated **Isaac-ROS SLAM** with **A\*** path planning for real-time, obstacle-aware navigation  
- Deployed onboard target verification using **Siamese Neural Networks** for lightweight visual matching  
- Implemented a **Lissajous trajectory** search strategy to enable systematic and efficient area coverage  
- Validated localization accuracy and navigation reliability in cluttered, GPS-denied scenarios  
- Led system integration across perception, planning, and control, and developed core autonomy pipelines  

---

## Personal

### AIRRO — AI-Powered Multimodal Search Engine  
_May 2025 – Present_

Multimodal search systems can improve information access by unifying text, image, and voice queries into a single semantic framework. This project aims to design a scalable, low-latency search engine that supports real-time retrieval across modalities while maintaining high relevance and efficiency.

Developing a research-oriented multimodal search system integrating web, image, and voice retrieval into a unified semantic pipeline. Ongoing evaluation focuses on retrieval relevance, latency, and scalability under increasing data and query loads.

- Implementing distributed indexing pipelines using **BM25** and **nomic-embed** for hybrid lexical-semantic retrieval  
- Designing low-latency semantic ranking strategies for real-time search applications  
- Building modular pipelines to support cross-modal query understanding and retrieval  
- Benchmarking system performance on latency and relevance metrics across modalities  
- Leading system architecture design and core retrieval pipeline development  

![AIRRO](/assets/img/airro_new.jpg)

---

## Teaching & Outreach

| Role | Institution | Period |
|---|---|---|
| **Teaching Assistant — Ai/Ml Project for Enginners** | Carnegie Mellon University | Spring 2026 |
| **Teaching Assistant — Trustworthy AI** | Carnegie Mellon University | Fall 2025 |
| **Organizer — Deep Learning & ROS2 Workshop** | Chennai, India | Nov 2024 |

---

## Publications

1. Santosh S., **Bavin S.**, Srivatsan T.S.  
   *Comparing surface characteristics of Cu–Al–Fe alloys using thermal-based machining processes.*  
   **Surface Engineering**, 2024. [DOI: 10.1177/02670844241276371](https://doi.org/10.1177/02670844241276371)

2. Santosh S., **Bavin S.**  
   *Experimental Studies on Wire Electric Discharge Machining of Cu–Al–Fe Shape Memory Alloy.*  
   **Physica Scripta**, IOP Publishing — _under review_.

---

## Links

- [GitHub](https://github.com/bavin-hub)
- [LinkedIn](https://www.linkedin.com/in/bavin-ab61671b6)
- [Skytex UAVs](https://theskytex.com/)
