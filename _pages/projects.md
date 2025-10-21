---
title: "🛠️ Projects Portfolio"
layout: single
permalink: /projects/
classes: wide
author_profile: true
---

<!-- # 🛠️ Projects Portfolio -->

Here’s a showcase of selected research projects across robotics, AI, and healthcare — blending real-world application with academic rigor.

---

## 🧭 Autonomous Navigation with Deep Reinforcement Learning  
**UdG Girona, Spain** | *Feb 2024 – Jun 2024*

<img src="/images/thesis1.png" alt="DRL Navigation" width="100%" style="border-radius: 12px; margin-top: 10px;" />

An end-to-end learning pipeline for autonomous navigation using **Soft Actor-Critic (SAC)** and **PPO**, built with a custom Gymnasium environment and LIDAR-based input.

🎥 [Watch Project Video](https://drive.google.com/file/d/1_lDjbW6k9gace_Ca7jNYK760WsogKfSQ/view?usp=sharing)  
📄 [Read Thesis PDF](/files/Thesis_by_Preeti_Verma.pdf)

---

## 🤖 Autonomous Robotic Explorer & Manipulator  
**UdG Girona, Spain** | *Feb 2023 – Jul 2023*

An integrated robotic system combining **exploration**, **manipulation**, **SLAM**, and **perception**, developed in **ROS**, tested in simulators and real environments.

### 📸 Project Snapshots

<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 10px;">
  <img src="/images/sim_mapping.png" width="48%" style="border-radius: 10px;" />
  <img src="/images/sim_planning.png" width="48%" style="border-radius: 10px;" />
  <img src="/images/real_planning_localization.png" width="48%" style="border-radius: 10px;" />
  <img src="/images/manipulationreal.png" width="48%" style="border-radius: 10px;" />
</div>

### 🔹 Planning
- **Frontier-based exploration** combining RRT and DWA
- ✅ Tested in Gazebo and Stonefish  
📄 [Read PDF](/files/Hands_on_Planning_report.pdf)

### 🔹 Localization
- **Pose-based EKF SLAM** with ICP scan matching  
- 🔄 Sensor fusion using LiDAR and IMU  
📄 [Read PDF](/files/Hands_On_Localization_Presentation.pdf)

### 🔹 Perception
- **Event-based tracking** for DAVIS sensor  
- ✅ Integrated RealSense + ArUco detection  
🎥 [Watch Video](https://drive.google.com/file/d/1x_3L2jBV-lypZHbmb2kTQ8vprtLnZTqt/view?usp=drive_link)  
📄 [Read PDF](/files/Hands_On_Perception_Report.pdf)

### 🔹 Manipulation
- **Task-priority control** for 4-DOF robotic arm  
- 🤖 Autonomous pick-and-place  
📄 [Read PDF](/files/Hands_On_Intervention_Report.pdf)

### 🔹 Autonomy
- **Behavior Trees** using `py_trees`  
- 🧠 Seamless decision-making  
🎥 [Real Robot](https://drive.google.com/file/d/1fpwyqLnYkeVfgQACtkmG4f_qg_WIAAzI/view?usp=drive_link)  
🎥 [Simulation](https://drive.google.com/file/d/1RycwcICvbDNGwVo2LzIz3QIRni1FGWvE/view?usp=drive_link)

---

## 🧬 Medical Imaging Quality Assessment using Radiomics  
**University of Barcelona** | *Jul 2023 – Aug 2023*

<img src="/images/radiomic_noise.png" alt="Medical Image Quality" width="100%" style="border-radius: 12px;" />

Evaluated **synthetic imaging realism** using Radiomics FID. Analyzed robustness to noise, correlation with clinical features, and limitations of classical image realism metrics.

📄 [Read Paper](https://arxiv.org/pdf/2403.13890)

---

## 🌐 Pomona 3D Graph SLAM  
**Budapest, Hungary** | *Sep 2023 – Dec 2023*

<img src="/images/lidaroutdoor2.png" alt="Pomona Graph SLAM" width="100%" style="border-radius: 12px;" />

Developed a 3D mapping solution in ROS using **LiDAR, IMU, and GPS**, fusing data into optimized pose graphs using `hdl_graph_slam`. Focused on accuracy, real-time loop closure, and outdoor readiness.

---

## 💬 Multi-Span Medical QA (QueSemKnow)  
**IIT Patna, India** | *Jun 2022 – Aug 2022*

<img src="/images/lrcolling.png" alt="Medical QA" width="100%" style="border-radius: 12px;" />

Developed **QueSemKnow**, a query semantic and knowledge-guided transformer model for multi-span question answering in medical settings. Published at LREC-COLING 2024.

📄 [Read Publication](https://aclanthology.org/2024.lrec-main.1264.pdf)

---















<!-- ---
title: "Projects"
layout: single
permalink: /projects/
classes: wide
author_profile: true
---

# 🛠️ Projects Portfolio

Here’s a showcase of my selected projects across robotics, AI, and healthcare — combining research, engineering, and real-world applications.

---

## 🧭 Autonomous Navigation with Deep Reinforcement Learning  
**UdG Girona, Spain** | *Feb 2024 – Jun 2024*

<img src="/images/thesis1.png" alt="DRL Navigation" width="100%" style="border-radius: 12px; margin-top: 10px;" />

An end-to-end learning pipeline for autonomous navigation using **Soft Actor-Critic (SAC)** and **PPO** with custom-built Gymnasium environments and LIDAR inputs.

🎥 [Watch Project Video](https://drive.google.com/file/d/1_lDjbW6k9gace_Ca7jNYK760WsogKfSQ/view?usp=sharing)  
📄 [Read Thesis PDF](/files/Thesis_by_Preeti_Verma.pdf)

---

## 🤖 Autonomous Robotic Explorer & Manipulator  
**UdG Girona, Spain** | *Feb 2023 – Jul 2023*

An integrated robotic system combining **exploration**, **manipulation**, **SLAM**, and **perception**, developed using **ROS** and tested in both simulation and real-world environments.

---

### 🔹 Planning

**Implemented:** Frontier-based exploration combining **RRT** and **DWA**  
**Platform:** Gazebo & Stonefish Simulators

📄 [Read PDF](/files/Hands_on_Planning_report.pdf)

---

### 🔹 Localization

**Implemented:** Pose-based **EKF SLAM** with **ICP scan matching**  
**Sensors:** LiDAR odometry + IMU fusion

📄 [Read PDF](/files/Hands_On_Localization_Presentation.pdf)

---

### 🔹 Perception

**Implemented:** Event-based feature tracking for **DAVIS sensor**  
**Tools:** RealSense camera + ArUco marker detection pipeline

🎥 [Watch Video](https://drive.google.com/file/d/1x_3L2jBV-lypZHbmb2kTQ8vprtLnZTqt/view?usp=drive_link)  
📄 [Read PDF](/files/Hands_On_Perception_Report.pdf)

---

### 🔹 Manipulation

**Implemented:** Task-priority redundancy resolution for 4-DOF arm  
**Tasks:** Object pick, transport, and placement
 
📄 [Read PDF](/files/Hands_On_Intervention_Report.pdf)

---

### 🔹 Autonomy

**Implemented:** Behavior trees using `py_trees` for intelligent decision-making  
**Outcome:** Seamless integration of modules for autonomous robot behavior

🎥 [Real Robot Video](https://drive.google.com/file/d/1fpwyqLnYkeVfgQACtkmG4f_qg_WIAAzI/view?usp=drive_link)  
🎥 [Simulation Video](https://drive.google.com/file/d/1RycwcICvbDNGwVo2LzIz3QIRni1FGWvE/view?usp=drive_link)

---

### 🧠 Skills & Tools Used

- 🧠 **ROS**, **Gazebo**, **Python**, **RRT**, **ICP**, **SLAM**, **py_trees**
- 📡 **LiDAR**, **IMU**, **DAVIS**, **RealSense**, **ArUco**
- 🛠️ Behavior Trees, Feature Tracking, Motion Planning, EKF

---

### 📌 Outcome

This project demonstrated a full-stack robotics pipeline integrating planning, perception, localization, and manipulation in a cohesive system — simulating autonomous exploration and real-time decision-making in unknown environments.

---

## 🧬 Medical Imaging Quality Assessment using Radiomics  
**University of Barcelona** | *Jul 2023 – Aug 2023*

<img src="/images/radiomic_noise.png" alt="Medical Image Quality" width="100%" style="border-radius: 12px; margin-top: 10px;" />

Evaluated **synthetic imaging realism** using **Radiomics FID** — a metric focused on robustness to noise, clinical relevance, and image fidelity.

📄 [View Full Paper](https://arxiv.org/pdf/2403.13890?)

---

## 🌐 Pomona 3D Graph SLAM for Online Mapping  
**Budapest, Hungary** | *Sep 2023 – Dec 2023*

<img src="/images/lidaroutdoor2.png" alt="Pomona Graph SLAM" width="100%" style="border-radius: 12px; margin-top: 10px;" />

Built a full pipeline in ROS for real-time **3D environment mapping** using **LiDAR + GPS + IMU**. Integrated with hdl_graph_slam and optimized for pose graph accuracy.

---

## 🧠 Multi-Span Medical QA using Query Semantics & Knowledge Graphs  
**IIT Patna, India** | *Jun 2022 – Aug 2022*

<img src="/images/lrcolling.png" alt="Medical QA" width="100%" style="border-radius: 12px; margin-top: 10px;" />

Developed **QueSemKnow**, a two-phase semantic-aware model for answering complex medical questions using transformer-based extraction and graph-based reasoning.

📄 [Read Publication](https://aclanthology.org/2024.lrec-main.1264.pdf)

--- -->





























<!-- _pages/projects.md
---
permalink: /projects/
title: "Projects"
author_profile: true
layout: archive
classes: wide
---

# 🚀 Projects Overview

Each project demonstrates my interest in **AI, robotics, control systems**, and **real-world deployment**.

---

## 🤖 Autonomous Robotic Explorer and Manipulator  
**UdG Girona, Spain** | *Feb 2023 – Jul 2023*  

An integrated robotic system combining **exploration**, **manipulation**, **SLAM**, and **perception**, developed using **ROS** and tested in simulation and real-world environments.

### 🔹 Planning
- Implemented a **frontier-based exploration algorithm** combining RRT and DWA.
- Tested in Gazebo and Stonefish simulators.

### 🔹 Localization
- Developed **Pose-based EKF SLAM** with **ICP scan matching**.
- Fused **LiDAR odometry and IMU data** for accurate mapping.

### 🔹 Perception
- Designed an **event-based feature tracker** for DAVIS data.
- Integrated **RealSense camera** with **ArUco marker** detection pipeline.

### 🔹 Manipulation
- Created **task-priority redundancy resolution** for 4-DOF robotic arm.
- Enabled autonomous object picking, transport, and placement.

### 🔹 Autonomy
- Developed **behavior trees** using `py_trees` for intelligent decision making.

### 📸 Media
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="/images/robot_explore.jpg" alt="Robot exploring" width="300" />
  <img src="/images/manipulation_arm.png" alt="Robot arm" width="300" />
</div>

### 🎥 Demo Videos
- 🔗 [Exploration & Mapping Demo](https://drive.google.com/file/d/1fpwyqLnYkeVfgQACtkmG4f_qg_WIAAzI/view?usp=drive_link)
- 🔗 [Object Manipulation Demo](https://drive.google.com/file/d/1RycwcICvbDNGwVo2LzIz3QIRni1FGWvE/view?usp=drive_link)

---

## 🧠 DRL for Autonomous Navigation  
**UdG Girona, Spain** | *Feb 2024 – Jun 2024*  
- Developed a **custom Gymnasium environment** for autonomous navigation.
- Compared **SAC vs PPO** using **LIDAR downsampling** for real-time control.

---

## 🧬 Medical Imaging Quality Assessment  
**University of Barcelona, Spain** | *Jul 2023 – Aug 2023*  
- Investigated **Radiomics FID** metrics for image quality benchmarking.
- Evaluated noise robustness and downstream task impact.

---

## 🧾 Multi-Span Medical QA  
**IIT Patna, India** | *Jun 2022 – Aug 2022*  
- Designed **QueSemKnow**, a transformer-based QA system for MedQA.
- Integrated **query semantics** and **knowledge graph reasoning**.

---

## 🌍 Pomona 3D Graph SLAM  
**Budapest, Hungary** | *Sep 2023 – Dec 2023*  
- Built online 3D SLAM using **LiDAR + IMU + GPS fusion** in ROS.
- Adapted HDL Graph SLAM to real-time ROS mapping pipelines.

---

## ☀️ Metaheuristic MPPT Optimization  
**AMU, India** | *Aug 2020 – May 2021*  
- Simulated **PSO, Cuckoo Search, Jaya Algorithm** in MATLAB/Simulink.
- Evaluated under **partial shading** conditions for PV systems.

---
 -->
