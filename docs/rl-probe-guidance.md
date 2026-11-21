# PPO-Based Ultrasound Probe Guidance — My Implementation

## Research question

Can a reinforcement-learning agent learn to guide a **virtual ultrasound probe** toward desired anatomical views using information from a simulated environment?

## What I contributed

I developed and trained a **Proximal Policy Optimization (PPO)** model for the project's virtual probe-guidance research. The wider project included target-organ navigation experiments for liver, kidney, and gallbladder.

## Technical implementation: fill from the real code

| Component | What to document from the source files |
|---|---|
| Environment | Exact environment class, simulator integration, observation update |
| Observation / state | Shape, values, units, preprocessing |
| Actions | Exact movement axes and discrete/continuous controls |
| Reward | Mathematical definition and success criteria |
| Episode | Start distribution, target view, termination, maximum steps |
| PPO model | Network/policy type, learning rate, gamma, rollout size and seed(s) |
| Training | Training steps, environment count, machine/compute, logged plots |
| Evaluation | Number of episodes, test cases, success criteria, seed variability |

Do **not** insert plausible parameter values unless they are visible in the actual training code or logs.

## Evidence to add

- Real training reward curve: `assets/results/ppo-training-curve.png`
- Actual example of agent motion/trajectory: `assets/demo/ppo-navigation.gif` or `assets/demo/ppo-navigation.mp4`
- If permitted, link to `code/ppo-guidance/` source and explain how to reproduce
- Exact evaluation protocol and baseline (if one was used)

## Interpreting performance

Any percentages reported for simulated navigation describe **prototype experiments** under that particular environment, and do not measure competence or safety on real patients.

See [Reported research results](results.md) for provisional team-presentation numbers pending verification.
