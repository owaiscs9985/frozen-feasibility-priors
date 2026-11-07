# Frozen Feasibility Priors — Supplementary Code

## Overview
Code and data for the paper:
"Frozen Feasibility Priors: Learned Masks Provide Robustness to Constraint Shift
in Constrained Reinforcement Learning for Wireless Sensor Networks"

## Files
- `notebook.ipynb` — full pipeline: environment, PPO training, classifier training, shift evaluation, statistics
- `ppo_hard_mask.zip` — trained PPO policy (SB3 format)
- `feasibility_classifier.pt` — trained feasibility classifier (PyTorch state dict)
- `figures/` — publication figures (PDF)
- `results_data.csv` — IQM + bootstrap CI table
- `per_seed_data.csv` — per-seed success rates
- `requirements.txt` — Python dependencies

## Reproduction
1. Install dependencies: `pip install -r requirements.txt`
2. Open `notebook.ipynb` in Jupyter or Kaggle
3. Run cells top-to-bottom. The random seeds used are `[7000, 8000, 9000, 10000, 11000]`.
4. Full training + evaluation completes in ~1 hour on a CPU-only machine.

## Environment
- Python 3.13
- Kaggle notebook (CPU runtime)
- No proprietary data or hardware required

## License
Code: MIT
Data: CC-BY 4.0
