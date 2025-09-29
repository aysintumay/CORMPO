# CORMPO: Clinically-aware OOD-regularized Model-based Policy Optimization (CORMPO)
=======
## Overview

This repository includes an offline RL algorithm, CORMPO, and a medical environment for RL evaluation.

## Dependencies

- MuJoCo 2.0
- Gym 0.22.0
- d4rl
- PyTorch 1.8+


# Usage
## CORMPO Training

```
python mbpo_kde/mopo.py --config config/real/mbpo_kde_ws.yaml
```

## CORMPO Policy Evaluation
Evaluate a saved policy.

```
python helpers/evaluate_d4rl.py --config config/evaluate/noiseless/cormpo.yaml --policy_path "mopo_abiomed/saved_models/abiomed/mopo/seed_1_0726_022349-abiomed_mopo/policy_abiomed.pth"
```
