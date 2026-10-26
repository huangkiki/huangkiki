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

I’m a **Robotics Simulation Engineer at GENISOM AI in Beijing**, building platforms that bring together physics simulation, rendering, sensor models, and robot control. Previously, I worked on **production autonomous driving simulation for Baidu Apollo**.

My background is in **numerical modeling of physical systems**. I hold a master’s degree in Petroleum Engineering from China University of Petroleum, where I developed **physics-guided surrogate models for reservoir simulation**, using neural networks and mass-balance principles to predict how fluid distributions evolve over time.

I’m currently exploring **world models**, with a particular interest in how agents learn from physical interaction in tasks such as **dexterous manipulation**.

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

I develop **simulation workflows for dexterous manipulation**, covering robot and object modeling, task construction, controller integration, and behavior evaluation. DexLab brings these workflows together with reproducible experiments in **grasping, cutting, wiping, and deformable-material interaction**.

I use these tasks to examine how **contact, friction, and numerical solvers** affect simulated behavior, compare results across physics engines, and investigate tradeoffs between **numerical stability, accuracy, and computational cost**.

<table width="100%">
  <tr>
    <td width="50%" align="center" valign="top">
      <p><strong><a href="https://huangkiki.github.io/Dexlab/en/latest/cut-push.html">Tofu cutting</a></strong></p>
      <a href="https://huangkiki.github.io/Dexlab/en/latest/cut-push.html"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/14ba2f1e5b75abd61353117a51fd2e37f59880b5/docs/evidence/cutting/tofu-cut-push/surface-rtx.gif" width="100%" alt="Tofu cutting and pushing in RTX" loading="lazy"></a>
    </td>
    <td width="50%" align="center" valign="top">
      <p><strong><a href="https://huangkiki.github.io/Dexlab/en/latest/cut-push.html">Banana cutting</a></strong></p>
      <a href="https://huangkiki.github.io/Dexlab/en/latest/cut-push.html"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/14ba2f1e5b75abd61353117a51fd2e37f59880b5/docs/evidence/cutting/banana-cut-push/surface-rtx.gif" width="100%" alt="Banana cutting and pushing in RTX" loading="lazy"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <p><strong><a href="https://huangkiki.github.io/Dexlab/en/latest/rss-wiping.html">Stain wiping</a></strong></p>
      <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/rss-wiping/rtx/rtx.mp4"><img src="assets/projects/stain-wiping.gif" width="100%" alt="Stain wiping: recorded trajectory in RTX, 10–19.9 s" loading="lazy"></a>
    </td>
    <td width="50%" align="center" valign="top">
      <p><strong><a href="https://huangkiki.github.io/Dexlab/en/latest/libero-workflow.html">LIBERO replay</a></strong></p>
      <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/libero.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/libero.gif" width="100%" alt="LIBERO demo 0: native baseline state replay" loading="lazy"></a>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <p><strong><a href="https://huangkiki.github.io/Dexlab/en/latest/experiments.html#apple-replays">Apple grasping</a></strong></p>
      <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/apple.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/apple.gif" width="100%" alt="Apple grasping: MuJoCo 3.16 / SuperDex 1.0 RTX replay" loading="lazy"></a>
    </td>
  </tr>
</table>

[More experiments](https://huangkiki.github.io/Dexlab/en/latest/experiments.html) · [Task and solver coverage](https://huangkiki.github.io/Dexlab/en/latest/coverage.html)

<sub>Recorded simulation replays · <a href="assets/projects/README.md">Sources and rendering details</a>.</sub>

### 3. World Model

<h3><a href="https://github.com/zsibot/gawm">GAWM: Geometry-Aware World Model</a> <a href="https://github.com/zsibot/gawm/stargazers"><img src="https://img.shields.io/github/stars/zsibot/gawm?style=flat&amp;logo=github&amp;label=Stars" alt="GitHub Stars"></a></h3>
<p>Our action-conditioned JEPA world model combines latent prediction with <strong>state alignment (SA) and inverse dynamics (IDM) losses</strong>. <strong>SA trains a head to predict measured physical states from consecutive latent representations</strong>, encouraging the encoder to retain physical configuration and motion. IDM provides complementary supervision by predicting executed actions from latent pairs. Physical states are used only for training supervision. At deployment, GAWM plans toward visual goals with CEM in latent space, without reconstructing future images.</p>
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
