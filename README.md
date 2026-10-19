<div align="center">

# Hi, I'm Riley Marek 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1200&color=56C5C5&center=true&vCenter=true&width=650&lines=Spacecraft+GNC+%26+Relative+Navigation;Embodied+Robotics+(Isaac+Sim+%2B+ROS+2);Deterministic%2C+Allocation-Free+Rust+(no_std);Multi-Agent+Autonomous+Systems)](https://git.io/typing-svg)

<p align="center">
  <b>Building high-assurance autonomy at the intersection of embedded systems, orbital physics, and embodied AI.</b>
</p>

<p align="center">
  <a href="https://github.com/RileyMarek"><img src="https://img.shields.io/badge/GitHub-RileyMarek-181717?style=flat-square&logo=github" alt="GitHub" /></a>
  <a href="mailto:riley.marek@wsu.edu"><img src="https://img.shields.io/badge/Email-riley.marek%40wsu.edu-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Focus-Aerospace%20%26%20Robotics-FF8A46?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Location-Washington%2C%20USA-2ea44f?style=flat-square" alt="Location" />
</p>

---

</div>

### 🛰️ Flagship Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/RileyMarek/ApsisVision">🛰️ Apsis Vision</a></h3>
      <p align="center"><b>Relative Spacecraft Navigation in Rust</b></p>
      <p>Autonomous relative optical navigation core for spacecraft rendezvous and proximity operations:</p>
      <ul>
        <li><b>Zero-Allocation Flight Core:</b> Strict <code>no_std</code>, allocation-free EKF cross-compiled for ARM Cortex-M / Linux.</li>
        <li><b>High-Integrity Perception:</b> Geometry-dependent 6x6 pose covariance, dual-stage visual admission, and latched ambiguity holds.</li>
        <li><b>Orbital Dynamics:</b> Hill-Clohessy-Wiltshire (HCW) relative dynamics with approach corridors, virtual capture, and automated aborts.</li>
      </ul>
      <p align="center">
        <code>Rust</code> · <code>no_std</code> · <code>EKF</code> · <code>GNC</code> · <code>Computer Vision</code> · <code>ARM</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🤖 Moonbase</h3>
      <p align="center"><b>Embodied Robotics Command Center</b></p>
      <p>Robotic autonomy stack bridging high-level Vision-Language-Action (VLA) models with low-level execution:</p>
      <ul>
        <li><b>Simulation & Physics:</b> High-fidelity Isaac Sim (NVIDIA Omniverse) with native RTX physics.</li>
        <li><b>Distributed Architecture:</b> ROS 2, FastDDS, and Foxglove WebSocket bridging across edge hardware.</li>
        <li><b>VLA Foundation Models:</b> Remote VLA (Molmo-7B) integration with a real-time Three.js / React digital twin.</li>
      </ul>
      <p align="center">
        <code>Python</code> · <code>ROS 2</code> · <code>Isaac Sim</code> · <code>Three.js</code> · <code>FastDDS</code> · <code>VLAs</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🧠 Hermes Brain</h3>
      <p align="center"><b>Autonomous Agent & Memory Server</b></p>
      <p>Persistent context, scheduling, and autonomous tool orchestration infrastructure:</p>
      <ul>
        <li><b>Context Persistence:</b> Structured episodic and procedural memory store via Supabase MCP.</li>
        <li><b>Task Orchestration:</b> Proactive background workflows, tool execution, and daily synthesis engines.</li>
      </ul>
      <p align="center">
        <code>Python</code> · <code>FastAPI</code> · <code>MCP</code> · <code>Docker</code> · <code>AsyncIO</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📐 Research & Engineering Rigor</h3>
      <p align="center"><b>Methodology & Standards</b></p>
      <p>Committed to rigorous engineering with reproducible, zero-theater empirical evidence:</p>
      <ul>
        <li><b>Rigorous Benchmarking:</b> Characterized on official Stanford SLAB SPEED+ and SHIRT datasets.</li>
        <li><b>Aerospace-Grade Verification:</b> Full-state NEES consistency, formal covariance bounds, and strict CI gates.</li>
      </ul>
      <p align="center">
        <code>Formal Verification</code> · <code>Covariance Consistency</code> · <code>CI/CD</code>
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
| **Robotics & Space** | ![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white) ![Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![Foxglove](https://img.shields.io/badge/Foxglove-4B32C3?style=for-the-badge) ![GNC / EKF](https://img.shields.io/badge/GNC_%2F_EKF-56C5C5?style=for-the-badge) |
| **Perception & Math** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white) ![PnP / RANSAC](https://img.shields.io/badge/PnP_%2F_RANSAC-FF8A46?style=for-the-badge) |
| **Embedded & Infra** | ![no_std](https://img.shields.io/badge/no__std_ARM-black?style=for-the-badge&logo=arm&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) |

</div>

---

### 📈 Activity & Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RileyMarek&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=56C5C5&icon_color=FF8A46&text_color=C9D1D9" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RileyMarek&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=56C5C5&text_color=C9D1D9" height="165" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=RileyMarek&theme=tokyonight&hide_border=true&background=0D1117&ring=56C5C5&fire=FF8A46&currStreakLabel=56C5C5" alt="GitHub Streak" />

</div>

---

<div align="center">
  <sub>Designed with precision. Committed to verifiable results.</sub>
</div>
