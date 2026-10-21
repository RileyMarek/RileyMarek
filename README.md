<div align="center">

# Hi, I'm Riley Marek 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=1100&color=56C5C5&center=true&vCenter=true&width=720&lines=Spacecraft+GNC+%26+Autonomous+Orbital+Vision;High-Performance+%26+Low-Latency+Networking;AI%2FML+Infrastructure+%26+Enterprise+GPU+Clusters;Embodied+Robotics+(Isaac+Sim+%2B+ROS+2);Deterministic%2C+Allocation-Free+Rust+(no_std))](https://git.io/typing-svg)

<p align="center">
  <b>Building high-assurance autonomous systems at the intersection of AI/ML infrastructure, low-latency distributed networking, and physical robotics.</b>
</p>

<p align="center">
  <a href="https://github.com/RileyMarek"><img src="https://img.shields.io/badge/GitHub-RileyMarek-181717?style=flat-square&logo=github" alt="GitHub" /></a>
  <a href="mailto:riley.marek@wsu.edu"><img src="https://img.shields.io/badge/Email-riley.marek%40wsu.edu-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Focus-AI%2FML%20Infra%2C%20Networking%20%26%20Aerospace-FF8A46?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Location-Washington%2C%20USA-2ea44f?style=flat-square" alt="Location" />
</p>

---

</div>

### 🛰️ Featured Systems & Research

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/RileyMarek/ApsisVision">🛰️ Apsis Vision</a></h3>
      <p align="center"><b>Relative Spacecraft Navigation in Rust</b></p>
      <p>Autonomous relative optical navigation core for spacecraft rendezvous and proximity operations:</p>
      <ul>
        <li><b>Zero-Allocation Core:</b> Strict <code>no_std</code>, allocation-free EKF cross-compiled for ARM Cortex-M and Linux.</li>
        <li><b>High-Integrity Perception:</b> Geometry-dependent 6x6 pose covariance, dual-stage visual admission, and latched ambiguity holds.</li>
        <li><b>Orbital Dynamics:</b> Hill-Clohessy-Wiltshire (HCW) relative dynamics with approach corridors, virtual capture, and automated aborts.</li>
      </ul>
      <p align="center">
        <code>Rust</code> · <code>no_std</code> · <code>EKF</code> · <code>GNC</code> · <code>Computer Vision</code> · <code>ARM</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⚡ AI/ML Infrastructure & Low-Latency Networking</h3>
      <p align="center"><b>High-Throughput Distributed Compute & Telemetry</b></p>
      <p>High-reliability infrastructure for enterprise GPU clusters and real-time distributed robotics:</p>
      <ul>
        <li><b>GPU Cluster Orchestration:</b> Multi-node distributed compute pipelines, remote GPU offloading (FastAPI/tunnel bridging to remote VLA models), and CUDA profiling.</li>
        <li><b>Low-Latency IPC:</b> Zero-copy message passing with FastDDS, eRPC, and WebSocket streaming bridges optimized for sub-millisecond control loops.</li>
        <li><b>Resilient Cloud Middleware:</b> Bounded-queue replay buffers, automated QoS throttling, network fault injection, and containerized microservices.</li>
      </ul>
      <p align="center">
        <code>GPU Clusters</code> · <code>FastDDS</code> · <code>WebSockets</code> · <code>gRPC</code> · <code>FastAPI</code> · <code>CUDA</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🤖 Moonbase</h3>
      <p align="center"><b>Embodied Robotics Command Center</b></p>
      <p>Robotic autonomy stack bridging high-level Vision-Language-Action (VLA) models with low-level execution:</p>
      <ul>
        <li><b>Physics & Simulation:</b> High-fidelity Isaac Sim (NVIDIA Omniverse) with native RTX physics.</li>
        <li><b>Distributed Middleware:</b> ROS 2, FastDDS, and Foxglove WebSocket bridging across distributed edge compute.</li>
        <li><b>VLA Foundation Models:</b> Remote VLA (Molmo-7B) integration with a real-time Three.js / React digital twin.</li>
      </ul>
      <p align="center">
        <code>Python</code> · <code>ROS 2</code> · <code>Isaac Sim</code> · <code>FastDDS</code> · <code>WebSockets</code> · <code>VLAs</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🪐 NASA Rover Autonomy</h3>
      <p align="center"><b>Planetary Surface Robotics & Navigation</b></p>
      <p>Autonomous navigation, localization, and control infrastructure for planetary exploration rovers:</p>
      <ul>
        <li><b>Sensor Fusion:</b> Multi-sensor state estimation fusing IMU, GNSS, wheel odometry, and stereo vision.</li>
        <li><b>Perception & Planning:</b> Real-time terrain traversability hazard mapping and dynamic local path planning.</li>
        <li><b>Telemetry Networking:</b> Robust, low-latency CAN bus and UDP/Ethernet communication architecture for harsh telemetry links.</li>
      </ul>
      <p align="center">
        <code>C++</code> · <code>ROS 2</code> · <code>Sensor Fusion</code> · <code>Path Planning</code> · <code>CAN Bus</code> · <code>Embedded</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🧠 ADAPT-AI <small><i>(Proprietary)</i></small></h3>
      <p align="center"><b>Multi-Agent LLM Orchestration Platform</b></p>
      <p>Assessment-design application developed for the CAIRE Research Lab at Washington State University <i>(Proprietary)</i>:</p>
      <ul>
        <li><b>Multi-Stage LLM Pipelines:</b> Deterministic P1–P6 sequential and conditional prompt orchestration pipelines.</li>
        <li><b>High-Throughput Backend:</b> Distributed FastAPI backend with async task scheduling, session state, and telemetry.</li>
        <li><b>Reliable Data Architecture:</b> PostgreSQL persistence with strict audit logging, migrations, and schema validation.</li>
      </ul>
      <p align="center">
        <code>FastAPI</code> · <code>LLM Pipelines</code> · <code>PostgreSQL</code> · <code>Next.js</code> · <code>Docker</code> · <code>Telemetry</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🔬 AI/ML Research & Geometric Perception</h3>
      <p align="center"><b>Robust Computer Vision Under Domain Gaps</b></p>
      <p>Bridging deep neural representations with classical geometric state estimation:</p>
      <ul>
        <li><b>Monocular 6-DoF Pose:</b> Heatmap regression for 3D landmarks paired with EPNP RANSAC and Levenberg-Marquardt.</li>
        <li><b>Domain Adaptation:</b> Training networks to cross the space radiometry gap (harsh solar glare, specular MLI, Earth albedo).</li>
        <li><b>Uncertainty & Gating:</b> Analytic covariance propagation, Mahalanobis NIS gating, and spatial entropy confidence screening.</li>
      </ul>
      <p align="center">
        <code>PyTorch</code> · <code>Computer Vision</code> · <code>PnP / RANSAC</code> · <code>ONNX</code> · <code>Optimization</code>
      </p>
    </td>
  </tr>
</table>

---

### 🛠️ Tech Stack & Systems

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) |
| **Networking & Infra** | ![FastDDS](https://img.shields.io/badge/FastDDS-008080?style=for-the-badge) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) |
| **AI/ML & Compute** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![CUDA](https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![VLA / LLMs](https://img.shields.io/badge/VLAs_%2F_LLMs-FF8A46?style=for-the-badge) |
| **Robotics & Aerospace** | ![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white) ![Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![Foxglove](https://img.shields.io/badge/Foxglove-4B32C3?style=for-the-badge) ![GNC / EKF](https://img.shields.io/badge/GNC_%2F_EKF-56C5C5?style=for-the-badge) |

</div>

---

### 📈 Activity & Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RileyMarek&show_icons=true&hide_rank=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=56C5C5&icon_color=FF8A46&text_color=C9D1D9" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RileyMarek&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=56C5C5&text_color=C9D1D9" height="165" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=RileyMarek&theme=tokyonight&hide_border=true&background=0D1117&ring=56C5C5&fire=FF8A46&currStreakLabel=56C5C5" alt="GitHub Streak" />

</div>

---

<div align="center">
  <sub>Designed with precision. Committed to verifiable results.</sub>
</div>
