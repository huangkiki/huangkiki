<div align="center">
  <h1>
    <img src="assets/emoji/robot.gif" width="32" height="32" alt="Robot">
    Hi, I’m Kiki Huang
    <img src="assets/emoji/wave.gif" width="32" height="32" alt="Waving hand">
  </h1>
  <h3>Robotics Simulation Engineer</h3>
  <p>
    Simulation Platforms · Dexterous Manipulation Simulation<br>
    Physics Solvers · World Models
  </p>
  <p>
    <a href="mailto:huangyue0719@outlook.com" title="Email: huangyue0719@outlook.com"><img src="assets/icons/email.svg" width="28" height="28" alt="Email"></a>&nbsp;&nbsp;&nbsp;
    <a href="https://github.com/huangkiki" title="GitHub"><img src="assets/icons/github.svg" width="28" height="28" alt="GitHub"></a>&nbsp;&nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/huangkiki" title="LinkedIn"><img src="assets/icons/linkedin.svg" width="28" height="28" alt="LinkedIn"></a>&nbsp;&nbsp;&nbsp;
    <a href="https://www.xiaohongshu.com/user/profile/62f72244000000001f0176ea" title="REDNOTE · 12K+ followers"><img src="assets/icons/rednote.svg" width="28" height="28" alt="REDNOTE"></a>
  </p>
  <p>
    <a href="https://www.xiaohongshu.com/user/profile/62f72244000000001f0176ea">REDNOTE · 12K+ followers</a>
  </p>
</div>

---

I build **simulation systems for robots**, with a broader interest in how agents **learn to understand and act in the physical world**. I currently develop robotics simulation platforms at a leading quadruped robotics company. Previously, I worked on **production autonomous driving simulation for Baidu Apollo**.

My engineering work connects **physics simulation and solvers, visual rendering, sensor models, and robot control** into closed-loop systems. I want to make these environments useful as **interactive sandboxes** where agents can explore, learn how the world responds, and test their understanding through action.

I’m exploring **predictive representation learning, including JEPA-based approaches**, with a focus on what an agent needs to represent to anticipate the consequences of its actions and plan effectively. **Dexterous manipulation** gives me a concrete way to study this: small differences in geometry, friction, or timing can change an outcome, even when two situations look similar.

My aim is to use **simulation as an experimental environment**: generate controlled interactions, test learned predictions through robot behavior, and use failures to refine both the world model and the environment. This lets me study how the design of a simulated world affects what an agent can learn within it.

My background is in **numerical modeling of physical systems**. I hold a master’s degree in Petroleum Engineering from China University of Petroleum, where I studied flow through porous media, numerical reservoir simulation, and physics-informed neural networks. Across subsurface flow, autonomous driving, and robotics, I keep coming back to how much of the physical world a model needs to capture, and how to tell when it is reliable enough to guide action.

## Research Tools

<h3><a href="https://github.com/huangkiki/dailypaper-skills">DailyPaper Skills</a> <a href="https://github.com/huangkiki/dailypaper-skills/stargazers"><img src="https://img.shields.io/github/stars/huangkiki/dailypaper-skills?style=flat&amp;logo=github&amp;label=Stars" alt="GitHub Stars"></a></h3>
<p>Agent skills for <strong>paper discovery, critical reviews, and connected research notes</strong>, with support for English and Chinese.</p>

## Research & Engineering

### 1. Robot Simulation Platforms

<a href="https://raw.githubusercontent.com/zsibot/matrix/55ad3fec77deaf1b589d27fa6cc4bfca4553754e/demo_gif/Town10.gif"><img align="right" src="https://raw.githubusercontent.com/zsibot/matrix/55ad3fec77deaf1b589d27fa6cc4bfca4553754e/demo_gif/Town10.gif" width="360" alt="MATRiX quadruped navigation in the Town10 simulation"></a>

<h3><a href="https://github.com/zsibot/matrix">MATRiX</a> <a href="https://github.com/zsibot/matrix/stargazers"><img src="https://img.shields.io/github/stars/zsibot/matrix?style=flat&amp;logo=github&amp;label=Stars" alt="GitHub Stars"></a></h3>
<p>An integrated robotics simulation platform combining <strong>Unreal Engine 5 rendering and MuJoCo dynamics</strong>, configurable robot models, calibrated sensor simulation, motion control, and ROS 2-compatible communication for robot development and evaluation.</p>
<p><sub>MATRiX · Town10 navigation</sub></p>

<br clear="right">

### 2. Dexterous Manipulation Simulation & Physics Solvers

<h3><a href="https://github.com/huangkiki/Dexlab">DexLab</a> <a href="https://github.com/huangkiki/Dexlab/stargazers"><img src="https://img.shields.io/github/stars/huangkiki/Dexlab?style=flat&amp;logo=github&amp;label=Stars" alt="GitHub Stars"></a></h3>

Developing simulation workflows spanning **robot and object modeling, task construction, controller integration, and behavior evaluation**, alongside reproducible experiments on **contact, friction, deformable materials, and numerical solvers**. I explore grasping, in-hand manipulation, and cutting, with attention to numerical stability and tradeoffs between accuracy and efficiency.

Public examples include [Apple Stem Grasp](https://github.com/huangkiki/Dexlab/tree/main/demos/apple-stem-grasp) with OpenArm and Wuji hands, [Tofu Halving](https://github.com/huangkiki/Dexlab/tree/main/demos/tofu-cut), and [Banana Slicing](https://github.com/huangkiki/Dexlab/tree/main/demos/banana-cut).

<p>
<a href="https://github.com/huangkiki/Dexlab/tree/main/demos/apple-stem-grasp"><img align="top" src="https://raw.githubusercontent.com/huangkiki/Dexlab/4d988229fc7bc7bd6331947c8cd64b23da048cd8/demos/apple-stem-grasp/media/superdex-sdf.gif" width="260" alt="Apple Stem Grasp: recorded OpenArm and Wuji hand simulation in SuperDex"></a>
<a href="https://github.com/huangkiki/Dexlab/tree/main/demos/tofu-cut"><img align="top" src="https://raw.githubusercontent.com/huangkiki/Dexlab/4d988229fc7bc7bd6331947c8cd64b23da048cd8/docs/evidence/cutting/tofu/surface.gif" width="260" alt="Tofu Halving: recorded synthetic material cutting simulation"></a>
<a href="https://github.com/huangkiki/Dexlab/tree/main/demos/banana-cut"><img align="top" src="https://raw.githubusercontent.com/huangkiki/Dexlab/4d988229fc7bc7bd6331947c8cd64b23da048cd8/docs/evidence/cutting/banana/surface.gif" width="260" alt="Banana Slicing: recorded synthetic material simulation with three sequential cuts"></a>
</p>
<sub>Recorded simulation replays: apple stem grasp · tofu halving · banana slicing.</sub>

### 3. JEPA & World Models

<h3><a href="https://github.com/zsibot/gawm">GAWM: Geometry-Aware World Model</a> <a href="https://github.com/zsibot/gawm/stargazers"><img src="https://img.shields.io/github/stars/zsibot/gawm?style=flat&amp;logo=github&amp;label=Stars" alt="GitHub Stars"></a></h3>
<p>Our work on a lightweight, action-conditioned JEPA world model combining <strong>inverse dynamics and physical-state alignment</strong>. GAWM plans toward visual goals in latent space using CEM, without reconstructing future images.</p>
<p><strong>Toward Physically Grounded JEPA World Models for Goal-Conditioned Robotic Planning</strong><br>
<em>Accepted to the IROS 2026 Workshop on Physical World Models for Scaling Embodied AI.</em><br>
<a href="https://arxiv.org/abs/2609.03565">Paper</a> · <a href="https://github.com/zsibot/gawm">Code</a> · <a href="https://huggingface.co/kikihuang/GA-WM">Model Checkpoints</a></p>
<p align="center">
<a href="assets/projects/gawm-architecture.png"><img src="assets/projects/gawm-architecture.png" width="800" alt="GAWM model architecture from Figure 1: visual encoder E, action-conditioned predictor F, state-alignment head G (SA), inverse-dynamics head H (IDM), and their training losses"></a><br>
<sub>GAWM model architecture · <a href="https://arxiv.org/html/2609.03565v2#S0.F1">Figure 1 from the paper</a></sub>
</p>

---

I welcome discussions and collaboration on robotics simulation platforms, dexterous manipulation simulation, physics solvers, and world models.

<sub>[Project visuals](assets/projects/README.md)</sub>
