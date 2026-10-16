# Project visuals

The profile links to existing project GIFs at fixed commits. They are unmodified recordings; the profile does not imply a new experiment, evaluation, or benchmark.

| Profile section | Original visual |
| --- | --- |
| Robot Simulation Platforms | [zsibot/matrix — demo_gif/Town10.gif](https://github.com/zsibot/matrix/blob/55ad3fec77deaf1b589d27fa6cc4bfca4553754e/demo_gif/Town10.gif) |
| DexLab — apple stem grasp (MuJoCo 3.11.0) | [huangkiki/Dexlab — demos/apple-stem-grasp/media/mujoco-sdf.gif](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/demos/apple-stem-grasp/media/mujoco-sdf.gif) |
| DexLab — apple stem grasp (SuperDex 1.0.0 FP64) | [huangkiki/Dexlab — demos/apple-stem-grasp/media/superdex-sdf.gif](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/demos/apple-stem-grasp/media/superdex-sdf.gif) |
| DexLab — apple stem grasp (PhysX / Isaac Sim 5.1) | [huangkiki/Dexlab — demos/physx-contact/media/physx-sdf.gif](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/demos/physx-contact/media/physx-sdf.gif) |
| DexLab — tofu cutting and blade push (surface) | [huangkiki/Dexlab — tofu-cut-push/surface.gif](https://github.com/huangkiki/Dexlab/blob/35c447d639c7fc2e49d66570c851d6d364181edc/docs/evidence/cutting/tofu-cut-push/surface.gif) |
| DexLab — tofu cutting and blade push (particles) | [huangkiki/Dexlab — tofu-cut-push/particles.gif](https://github.com/huangkiki/Dexlab/blob/35c447d639c7fc2e49d66570c851d6d364181edc/docs/evidence/cutting/tofu-cut-push/particles.gif) |
| DexLab — banana cutting and blade push (surface) | [huangkiki/Dexlab — banana-cut-push/surface.gif](https://github.com/huangkiki/Dexlab/blob/35c447d639c7fc2e49d66570c851d6d364181edc/docs/evidence/cutting/banana-cut-push/surface.gif) |
| DexLab — banana cutting and blade push (particles) | [huangkiki/Dexlab — banana-cut-push/particles.gif](https://github.com/huangkiki/Dexlab/blob/35c447d639c7fc2e49d66570c851d6d364181edc/docs/evidence/cutting/banana-cut-push/particles.gif) |

The four cutting GIFs share their corresponding task recording and preserve its frame-level measurements. [Cut-push evidence](https://github.com/huangkiki/Dexlab/tree/35c447d639c7fc2e49d66570c851d6d364181edc/demos/cut-push) records protocols, controls, viscosity, numerical checks and media hashes. They replace the older halving / banana clips.

The three apple-grasp GIFs show separate 14-second physics recordings from MuJoCo, SuperDex and PhysX, rendered with the same MuJoCo replay renderer. All use OpenArm and Wuji hands with scripted control. Their SDF discretization, contact parameters and controllers differ; the gallery does not establish an engine ranking. [MuJoCo / SuperDex settings and evidence](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/docs/sdf-backends.md) and [PhysX settings and evidence](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/demos/physx-contact/apple.md) document the configurations, checks and limitations. The GIFs are unmodified; clicking them opens the corresponding original MP4.

`gawm-architecture.png` is an unmodified copy of **Figure 1** from [Toward Physically Grounded JEPA World Models for Goal-Conditioned Robotic Planning, arXiv:2609.03565v2](https://arxiv.org/html/2609.03565v2#S0.F1). [Original image](https://arxiv.org/html/2609.03565v2/method_overview.png). It shows the visual encoder, action-conditioned predictor, state-alignment head, inverse-dynamics head, and training losses.
