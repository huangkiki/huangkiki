# Project visuals

The profile links to actual project recordings and replays at fixed commits. Updating their presentation does not create a new experiment or benchmark.

| Profile visual | Source |
| --- | --- |
| MATRiX · Town10 navigation | [Original recording](https://github.com/zsibot/matrix/blob/55ad3fec77deaf1b589d27fa6cc4bfca4553754e/demo_gif/Town10.gif) |
| DexLab · studio/rss | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/rss.gif) |
| DexLab · cutting/tofu-cut-push/surface-rtx | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/14ba2f1e5b75abd61353117a51fd2e37f59880b5/docs/evidence/cutting/tofu-cut-push/surface-rtx.gif) |
| DexLab · cutting/banana-cut-push/surface-rtx | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/14ba2f1e5b75abd61353117a51fd2e37f59880b5/docs/evidence/cutting/banana-cut-push/surface-rtx.gif) |
| DexLab · cutting/tofu-scoring/surface | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cutting/tofu-scoring/surface.gif) |
| DexLab · studio/apple | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/apple.gif) |
| DexLab · cloth-studio/sag | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cloth-studio/sag.gif) |
| DexLab · cloth-studio/grasp | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/cloth-studio/grasp.gif) |
| DexLab · studio/pinch | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/pinch.gif) |
| DexLab · studio/libero | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/libero.gif) |
| DexLab · studio/incline | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/incline.gif) |
| DexLab · studio/normal | [Recorded replay](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/normal.gif) |


The DexLab gallery presents ten experiment groups. The rigid-scene RTX batch
contains 13 complete recordings and 1,142 frames: two apple-grasp records, both
Genesis force limits, LIBERO demo 0, six historical incline engines and the
initial/calibrated normal-contact pair. Their original states are replayed with
MuJoCo's USD exporter and OVRTX; no physics is integrated during rendering.
Every exported object and camera transform is checked at each rendered frame.
[Frame maps, source hashes and render settings](https://github.com/huangkiki/Dexlab/blob/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio/manifest.json)
accompany the [individual receipts and videos](https://github.com/huangkiki/Dexlab/tree/fe658e2d863fb1c393835ee9e515c6451bdf1b26/docs/evidence/studio).

The apple preview compares MuJoCo 3.16.0 and SuperDex 1.0, with scripted control
and independently verified 14-second recordings. The older
[PhysX / Isaac Sim 5.1 recording](https://github.com/huangkiki/Dexlab/blob/b955d8536e219e7ba3de1150cfc19aa65878cfb3/demos/physx-contact/media/physx-sdf.mp4)
remains linked separately. Different contact models and controllers prevent
interpreting these clips as an engine ranking.

RSS uses a separately verified matched-camera RTX replay; its profile GIF covers
10–19.9 seconds. Cutting shows connected-volume reconstruction from recorded
synthetic-material states, without real-food calibration. The banana and tofu
cut-push previews use repaired display surfaces and OVRTX path tracing;
their 161 and 121 frames retain the original motion and measurements. The original particle
views and force measurements remain in the
[cutting report](https://huangkiki.github.io/Dexlab/en/latest/cutting-surface.html).
Cloth uses recorded-mesh studio views, with failures and coverage gaps preserved
in the [cloth report](https://huangkiki.github.io/Dexlab/en/latest/cloth-comparison.html).

`gawm-architecture.png` is an unmodified copy of **Figure 1** from
[Toward Physically Grounded JEPA World Models for Goal-Conditioned Robotic Planning, arXiv:2609.03565v2](https://arxiv.org/html/2609.03565v2#S0.F1).
[Original image](https://arxiv.org/html/2609.03565v2/method_overview.png).
It shows the visual encoder, action-conditioned predictor, state-alignment head,
inverse-dynamics head, and training losses.
