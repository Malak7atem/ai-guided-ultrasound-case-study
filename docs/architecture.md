# System Architecture — Team Context

This page explains the **overall team project** so readers can see where my work fits. It does not imply that I personally built all stages.

```text
CT volume (3D) + organ segmentation
                  |
            Probe position
                  |
       Extract oriented 2D view
                  |
  Synthesis experiments / simulation
       (Field II, rays, Pix2Pix)
                  |
    Image analysis & localization
                  |
  Organ presence / view assessment
                  |
         PPO guidance policy
                  |
      Feedback in training UI
```

**My key research areas:** CT-to-ultrasound synthesis experiments and PPO navigation.

**Broader project software described in team materials:** React, TypeScript, Vite, Three.js/VTK.js frontend; Python/FastAPI/WebSocket backend; medical image processing; deep-learning experiments.

## Add a verified architecture visual

Upload an approved exported diagram as `assets/diagrams/system-architecture.png` and refer to it from this page. Before publishing, cross-check each arrow against the actual integrated prototype; a methodology diagram must not be mistaken for a fully deployed end-to-end model.

## System integration questions to verify

- Which backend module produced the probe image displayed in the final demo?
- Which of the different synthesis approaches were experimental versus used in the running interface?
- How did the UI send probe position/orientation to the backend?
- Where were PPO action suggestions rendered and how were they evaluated?

## Source

[Original graduation project](https://github.com/mariamelprince14/ai_guided_ultrasound).
