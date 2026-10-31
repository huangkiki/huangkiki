# Project visuals

The profile links to actual project recordings and replays at fixed commits. Updating their presentation does not create a new experiment or benchmark.

| Profile visual | Source |
| --- | --- |
| MATRiX · Town10 navigation | [Original recording](https://github.com/zsibot/matrix/blob/55ad3fec77deaf1b589d27fa6cc4bfca4553754e/demo_gif/Town10.gif) |
| DexLab · execution and evaluation architecture | User-provided DexLab architecture artwork; task thumbnails are illustrative |
| DexLab · Wuji grasp and contact switching | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/64d9051beb12bda0cc47b9fea3d2e7226315ae16/docs/evidence/wuji-contact/comparison.gif) |
| DexLab · Tofu cutting | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/14ba2f1e5b75abd61353117a51fd2e37f59880b5/docs/evidence/cutting/tofu-cut-push/surface-rtx.gif) |
| DexLab · Banana cutting | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/14ba2f1e5b75abd61353117a51fd2e37f59880b5/docs/evidence/cutting/banana-cut-push/surface-rtx.gif) |
| DexLab · Stain wiping | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/rss.gif) |
| DexLab · Apple grasping | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/apple.gif) |
| DexLab · LIBERO replay | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/libero.gif) |


The profile highlights six experiments: Wuji grasp and contact switching, tofu
cutting, banana cutting, stain wiping, apple grasping, and LIBERO replay. The
apple and LIBERO previews come from a rigid-scene RTX batch of 13 complete
recordings and 1,142 frames. Their original states are replayed with MuJoCo's
USD exporter and OVRTX; no physics is integrated during rendering.
Every exported object and camera transform is checked at each rendered frame.
[Frame maps, source hashes and render settings](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/manifest.json)
accompany the [individual receipts and videos](https://github.com/huangkiki/Dexlab/tree/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio).

The apple preview compares MuJoCo 3.16.0 and SuperDex 1.0, with scripted control
and independently verified 14-second recordings. The older
[PhysX / Isaac Sim 5.1 recording](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/demos/physx-contact/media/physx-sdf.mp4)
remains linked separately. Different contact models and controllers prevent
interpreting these clips as an engine ranking.

Stain wiping uses a separately verified matched-camera RTX replay of the RSS
experiment; its profile GIF covers
10–19.9 seconds. The local `stain-wiping.gif` centers the original 640 × 363
frames on a transparent 640 × 528 canvas to match the LIBERO preview. All
100 frames retain their exact original pixels and playback durations.

Cutting shows connected-volume reconstruction from recorded
synthetic-material states, without real-food calibration. The banana and tofu
cut-push previews use repaired display surfaces and OVRTX path tracing;
their 161 and 121 frames retain the original motion and measurements. The original particle
views and force measurements remain in the
[cutting report](https://huangkiki.github.io/Dexlab/en/latest/cutting-surface.html).

`gawm-architecture.png` is an unmodified copy of **Figure 1** from
[Toward Physically Grounded JEPA World Models for Goal-Conditioned Robotic Planning, arXiv:2609.03565v2](https://arxiv.org/html/2609.03565v2#S0.F1).
[Original image](https://arxiv.org/html/2609.03565v2/method_overview.png).
It shows the visual encoder, action-conditioned predictor, state-alignment head,
inverse-dynamics head, and training losses.

`dexlab-architecture.jpg` describes DexLab's execution and evaluation flow. Its
task images identify supported categories and are not additional experiment
results; the recordings below remain the evidence shown on the profile.
