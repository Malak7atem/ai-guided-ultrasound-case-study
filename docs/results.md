# Results and Evidence

## Evidence standard

The figures below are **team-presentation-reported prototype metrics** from a previously saved project README draft. They are included here as **verification targets**, not as independently verified outputs from the original GitHub repository. Before making them prominent in the public README, locate the corresponding code, logged evaluation, chart, or approved final presentation.

| Experiment | Presentation-reported metric | Value | Required proof |
|---|---|---|---|
| Organ segmentation (team pipeline) | Mean Dice | 0.8984 | test set details / plot |
| Organ presence (team pipeline) | Mean cross-validation accuracy | 0.932 | fold definition / report |
| Organ presence (team pipeline) | Mean macro F1 | 0.897 | fold report |
| Quality regression (team pipeline) | R-squared | 0.958 | target definition / regression plot |
| Quality regression (team pipeline) | MAE | 0.041 | target definition |
| PPO navigation — liver | Reported success rate | 98.5% | episode count / success criterion |
| PPO navigation — kidney | Reported success rate | 85.5% | episode count / success criterion |
| PPO navigation — gallbladder | Reported success rate | 70.7% | episode count / success criterion |

**Interpretation:** Research prototype measurements. No claim of clinical validation or real patient training benefit is supported here.

## Recommended visuals

| Image to prepare | Exact filename | Source |
|---|---|---|
| Prototype screenshot | `assets/demo/platform-overview.png` | Real final application capture |
| Method output comparison | `assets/results/synthesis-comparison.png` | Actual saved experiment output |
| PPO training reward | `assets/results/ppo-training-curve.png` | Original experiment logs |
| Probe navigation demonstration | `assets/demo/ppo-navigation.gif` | Recorded simulation |

For each visual, attach a one-sentence caption describing the data, method, and whether it is from a simulation. Do not upload identified patient scans or restricted datasets.
