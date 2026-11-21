# AI-Guided Ultrasound Training System
### My Research & Engineering Contributions | Graduation Project, Nile University (2026)

**Medical Imaging · CT-to-Ultrasound Synthesis · Reinforcement Learning · PPO**

> **Personal technical case study.** This repository documents my individual work on a **five-person team graduation project**. It is not a copy of, or replacement for, the original team repository. The project is a research prototype, **not a clinically validated medical device**.

**Original team project:** [mariamelprince14/ai_guided_ultrasound](https://github.com/mariamelprince14/ai_guided_ultrasound)  
**My GitHub:** [@Malak7atem](https://github.com/Malak7atem)  
**My role:** AI Research & Software Development (Medical Imaging and Reinforcement Learning)

<!-- After permissions and de-identification checks, add a real project screenshot here:
![Virtual ultrasound training platform](assets/demo/platform-overview.png)
-->

## At a glance

Ultrasound image acquisition depends on the operator's probe position and orientation. Our team explored a virtual training workflow connecting patient-specific 3D CT imaging, ultrasound-like view synthesis, image assessment, and AI-assisted probe navigation.

My main work focused on **investigating and developing approaches to produce ultrasound-like images from CT-derived data**, and **developing and training a Proximal Policy Optimization (PPO) model for virtual probe guidance**.

## What I personally contributed

| Area | My work | Supporting detail |
|---|---|---|
| **CT-to-ultrasound synthesis** | Investigated and developed two image-generation approaches, focusing on anatomical fidelity and image realism. | [Methods and experiments](docs/ultrasound-simulation.md) |
| **Reinforcement learning** | Developed and trained a PPO model for guiding a simulated probe toward target anatomical views. | [PPO technical notes](docs/rl-probe-guidance.md) |
| **Research and evaluation** | Studied relevant literature, compared technical approaches, and interpreted experimental limitations. | [Individual contributions](CONTRIBUTIONS.md) |

*The exact scripts, experiments, and ownership boundaries will be linked once checked against the original team project. Other system modules are credited as team work.*

## How the system fits together

```text
3D CT anatomy + segmentation masks
                |
         Virtual probe pose
                |
         2D reslicing/view
                |
    Ultrasound-like image synthesis  <-- My research/experiments
                |
   Segmentation, localization &
        view-quality analysis        <-- Wider team pipeline
                |
       PPO probe guidance           <-- My development/training
                |
       Suggested probe action
                |
       Interactive training UI
```

This is a conceptual research architecture; not every experiment may be packaged in a single runnable application.

For a fuller explanation, see [System architecture](docs/architecture.md).

## Research methods

The project investigated **Field II**, **ray-based approaches**, and **2.5D Pix2Pix** as different ways to study ultrasound-like image generation from CT-derived information. These are team-level methods. My individual contribution was the development and investigation of two image-generation approaches; I will link the specific implementations once confirmed.

For navigation, my work included a **PPO-based reinforcement learning model** in a virtual probe environment. The wider project explored guidance toward liver, kidney, and gallbladder targets.

## Evaluation and evidence

The [results page](docs/results.md) distinguishes **team-reported prototype metrics** from results supported by code, scripts, or plots. I will add verified original figures and evaluation definitions rather than presenting simulation performance as clinical effectiveness.

**Evidence to attach:** a platform screenshot, a short probe-guidance demo, comparative synthesis outputs, and a PPO training/evaluation plot. See [asset instructions](assets/README.md).

## Technologies used across the project

`Python` · `PyTorch` · `Stable-Baselines3 / PPO` · `SimpleITK` · `React` · `TypeScript` · `Vite` · `Three.js / VTK.js` · `FastAPI` · `WebSockets`

These technologies describe the **overall team project** and should not be interpreted as tools I personally authored or implemented in every case.

## Team, recognition and attribution

This was a **Nile University Biomedical Informatics graduation project, 2025–2026**, developed by a five-person team under **Dr. Walid Al-Atabany**.

**Team:** Sara Abdelgaber, Nagham Samir, Malak Hatem, Mariam Elprince, Ahmed Bahaa. Team naming/spelling should be checked against the final submission.

My CV records an **A+ graduation-project grade**, **first place among Nile University graduation projects**, and **second place in the fifth Research to Impact competition**. Supporting evidence can be added here where publication is permitted.

**Original repository:** [Team source repository](https://github.com/mariamelprince14/ai_guided_ultrasound).

## Scope and responsible use

- This is research and educational work, not a product for diagnosis or patient care.
- Patient scans, datasets, weights, and derived medical images will not be published without appropriate permission and privacy review.
- No code is included until its ownership, licensing, attribution, and dependencies are checked.
- This repository does not claim that my GitHub commit history is the complete record of my work; team members handled portions of code integration and Git operations.

---

**Want the technical detail?** Start with [My Contributions](CONTRIBUTIONS.md), [Ultrasound Synthesis](docs/ultrasound-simulation.md), and [PPO Guidance](docs/rl-probe-guidance.md).
