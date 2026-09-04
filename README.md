# Hi, I'm Ethan 👋

A Computer Engineering student passionate about **embedded systems**, **robotics**, and **low-level software development**. My goal is to build efficient, robust, and reliable systems from the ground up.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ethan_Ieong-0A66C2?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/ethan-ieong) 
[![Email](https://img.shields.io/badge/Gmail-ethanieong99@gmail.com-EA4335?logo=gmail&logoColor=white&style=flat-square)](mailto:ethanieong99@gmail.com)

---

## 🔭 What I'm Focused On

I'm currently diving deep into C/C++ and hardware-level programming. Here's what I'm building right now:

* 🤖 **Unitree G1 humanoid (ISRMM Lab)** — a C++ control stack with an FSM and polymorphic behavior interface over Unitree SDK2, running a 500 Hz control loop with thread-safe command queuing and joint-limit enforcement. Vision side: depth + color streaming mapped into robot-frame coordinates via camera intrinsics/extrinsics, with MoveIt2 planning collision-aware dual-arm motion from live obstacle geometry.
* 🚀 **Rocket avionics (MetRocketry)** — leading control systems for roll-stabilizing canards on an STM32/FreeRTOS target at 10 ms actuator latency, with a Linear and Extended Kalman Filter on Cortex-M4 for state estimation and hand-written SPI/I2C sensor drivers paced by interrupts and binary semaphores.
* 🛰️ **Synthetic data pipelines** — domain randomization in Isaac Sim with Omniverse Replicator to generate labelled training sets for YOLOv8.

💼 Incoming Firmware Developer Intern at **The Home Depot Canada** (Sept–Dec 2026).

🌱 Outside of engineering, I love reading, currently working my way through *The School for Good and Evil*.

---

## 🛠️ My Toolkit

I have experience with a wide range of technologies, but my core focus is on systems programming.

| Category | Technologies |
| :--- | :--- |
| **Embedded & Low-Level** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" alt="Arduino" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cmake/cmake-original.svg" alt="CMake" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" width="40" height="40"/><br/>STM32 · ARM Cortex-M4 · FreeRTOS · I2C · SPI · CAN · UART · Make |
| **Languages** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" width="40" height="40"/> |
| **Robotics** | ROS2 · DDS · SLAM · RViz2 · MoveIt2 · Isaac Sim · Isaac Lab · Jetson Orin |
| **AI / CV** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" alt="OpenCV" width="40" height="40"/><br/>YOLOv8 |
| **Tools & DevOps** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" alt="Visual Studio" width="40" height="40"/><br/>KiCad · GDB · GitHub Actions · Oscilloscope & Multimeter |

---

## 🔩 Projects

**Flight Computer PCB** — [repo](https://github.com/etthann)
* 4-layer board in KiCad with dedicated power and ground planes, 50 Ω impedance-matched RF traces to minimize EMI
* IMU, GPS and barometer integrated over SPI, UART and I2C; LoRa downlink telemetry validated to 45k ft
* 4-bit SDIO bus length-matched within 2.5 mm across all six traces to keep clock and data aligned and prevent corruption

**6-DoF Robotic Arm**
* C++ inverse kinematics solver driving a six-axis arm

---

## 📊 My GitHub Stats

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=etthann&show_icons=true&theme=dark"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=etthann&show_icons=true"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api?username=etthann&show_icons=true" />
</picture>

<br/>

<a href="https://github.com/etthann"> 
   <img width="50%" src="https://streak-stats.demolab.com/?user=etthann&locale=en&theme=onedark&hide_border=true" /> 
</a>
