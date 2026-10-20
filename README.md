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

The broader research matrix spans **MuJoCo, SuperDex, Genesis, Newton Physics, PhysX, and Drake**, with coverage varying by task. The previews below show recorded experiments; click an experiment for its report or an RTX preview for the full replay.

| Experiment | Animated preview | Result |
| --- | --- | --- |
| [RSS wiping](https://huangkiki.github.io/Dexlab/en/latest/rss-wiping.html) | <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/rss-wiping/rtx/rtx.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/rss.gif" width="300" alt="RSS original recorded trajectory in RTX, 10–19.9 s" loading="lazy"></a> | Retains the sponge with auxiliary constraints; slips without them. Wiping reproduction. |
| [Cutting and pushing](https://huangkiki.github.io/Dexlab/en/latest/cut-push.html) | <a href="https://huangkiki.github.io/Dexlab/en/latest/cut-push.html"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cutting/tofu-cut-push/surface.gif" width="145" alt="Tofu-like / banana-like material" loading="lazy"></a> <a href="https://huangkiki.github.io/Dexlab/en/latest/cut-push.html"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cutting/banana-cut-push/surface.gif" width="145" alt="Tofu-like / banana-like material" loading="lazy"></a> | Blade contact pushes synthetic material; [separate single-cut force results do not establish convergence](https://huangkiki.github.io/Dexlab/en/latest/banana-force.html). |
| [Cross scoring](https://huangkiki.github.io/Dexlab/en/latest/tofu-scoring.html) | <a href="https://huangkiki.github.io/Dexlab/en/latest/tofu-scoring.html"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cutting/tofu-scoring/surface.gif" width="300" alt="Surface reconstruction from recorded states" loading="lazy"></a> | Two shallow cuts leave a connected base; the elastic surface can rebound. Native particle views remain available. |
| [Apple-stem grasp](https://huangkiki.github.io/Dexlab/en/latest/experiments.html#apple-replays) | <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/apple.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/apple.gif" width="300" alt="MuJoCo 3.16 / SuperDex 1.0 RTX replay" loading="lazy"></a> | Both 14 s MuJoCo 3.16 / SuperDex 1.0 records pass the 3 s hold check; scripted control. |
| [Cloth engine comparison](https://huangkiki.github.io/Dexlab/en/latest/cloth-comparison.html) | <a href="https://huangkiki.github.io/Dexlab/en/latest/cloth-comparison.html"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cloth-studio/sag.gif" width="300" alt="Matched sag across four engines" loading="lazy"></a> | Historical cloth responses across four engines, retaining failures and coverage gaps. |
| [Robot cloth grasp](https://huangkiki.github.io/Dexlab/en/latest/experiments.html) | <a href="https://huangkiki.github.io/Dexlab/en/latest/experiments.html"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cloth-studio/grasp.gif" width="300" alt="Cloth grasp, lift and release" loading="lazy"></a> | One development scene lifts, holds and releases; active folding remains unverified. |
| [Force-limit comparison](https://huangkiki.github.io/Dexlab/en/latest/visual-comparisons.html#pinch) | <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/pinch.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/pinch.gif" width="300" alt="Actuator limit 0.4 N / 0.8 N" loading="lazy"></a> | In the same Genesis protocol, actuator limits of 0.4 N slip and 0.8 N hold. |
| [LIBERO replay](https://huangkiki.github.io/Dexlab/en/latest/libero-workflow.html) | <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/libero.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/libero.gif" width="300" alt="Demo 0 native baseline state replay" loading="lazy"></a> | 500 official demonstrations: 495 task successes; none pass every numerical diagnostic. |
| [Six-engine incline](https://huangkiki.github.io/Dexlab/en/latest/visual-comparisons.html#incline) | <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/incline.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/incline.gif" width="300" alt="Sliding records at 1 ms timestep" loading="lazy"></a> | Compare sliding responses across six engines; equal parameter values do not imply equivalent models. |
| [Normal contact calibration](https://huangkiki.github.io/Dexlab/en/latest/visual-comparisons.html#normal) | <a href="https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/normal.mp4"><img src="https://raw.githubusercontent.com/huangkiki/Dexlab/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/normal.gif" width="300" alt="Loading, hold and unloading against a synthetic target" loading="lazy"></a> | Loading fits a synthetic target better; unloading and transfer need separate validation. |

[Full task and solver matrix](https://huangkiki.github.io/Dexlab/en/latest/coverage.html) · [Experiment reports](https://huangkiki.github.io/Dexlab/en/latest/experiments.html) · [Historical PhysX apple recording](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/demos/physx-contact/media/physx-sdf.mp4)

<sub>Lighting, surface reconstruction and recorded-state replay improve presentation. Original trajectories, failures and task scores are retained; appearance does not establish physical accuracy or an engine ranking. <a href="assets/projects/README.md">Visual sources and rendering details</a>.</sub>

### 3. JEPA & World Models

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
