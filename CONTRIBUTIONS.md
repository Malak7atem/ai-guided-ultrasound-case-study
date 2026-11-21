# My Individual Contributions — Malak Hatem

**Role:** AI Research & Software Development — Biomedical Informatics  
**Context:** Five-person Nile University graduation project (2025–2026)  
**Original project:** https://github.com/mariamelprince14/ai_guided_ultrasound

> This page records **my personal work** within a larger collaborative research prototype. I am not claiming that I independently built the entire platform.

## 1. CT-to-ultrasound synthesis: research and implementation

I investigated methods for generating ultrasound-like 2D views from 3D CT-derived anatomical information. I contributed to developing and comparing two approaches, with particular attention to **anatomical fidelity, visual realism, and practical computational constraints**.

The wider team's research considered Field II-based physics simulation, ray-based approximations, and learned 2.5D Pix2Pix translation. **Before publishing any claim of personal ownership**, I will identify exactly which two approaches I implemented and link the relevant code or notebooks.

**Evidence to add:** named scripts/notebooks, two real example outputs, concise comparison, and technical decisions. See [the methods page](docs/ultrasound-simulation.md).

## 2. PPO probe guidance: model development and training

I developed and trained a **Proximal Policy Optimization (PPO)** model to guide a virtual ultrasound probe toward target diagnostic views. This involved studying and implementing reinforcement-learning-based navigation in a simulated environment and evaluating the resulting behavior.

The team investigated abdominal target views including liver, kidney, and gallbladder. Before publishing detailed algorithm settings, I will verify the actual **state representation, action space, reward function, training configuration, and evaluation definition** from my original files.

**Evidence to add:** PPO environment file, training script, configuration, saved learning curves, and a real example navigation trajectory. See [PPO technical notes](docs/rl-probe-guidance.md).

## 3. Literature review, experimentation, and interpretation

I researched ultrasound image formation, medical-image synthesis, and intelligent probe-acquisition methods. This informed technical choices and our team's comparison of methods. I contributed to research reasoning and explaining the work, including its limitations.

**Evidence to add:** approved presentation slides, citation list, and a small 'method selection and tradeoffs' section.

## My contribution vs. team work

| Workstream | Attribution |
|---|---|
| CT-to-ultrasound research / two generation approaches | Personal contribution, exact files to identify |
| PPO agent development and training | Personal contribution |
| Literature review / experimental interpretation | Personal contribution |
| Complete web app, segmentation, localization, view-quality system, integration | **Collaborative team outcome**; do not imply sole ownership |

## Technical reflection

The hardest research questions were not simply generating an image or training a policy. They included preserving anatomical correspondence when converting between imaging modalities; balancing appearance against fidelity and runtime; and measuring success in simulated probe navigation without overstating real-world clinical transfer.

## Proof, not just claims

I will link original code and genuine experimental artifacts where sharing is permitted. I will not invent commit history, recreate teammates' commits under my name, or publish the team's private code without authorization.
