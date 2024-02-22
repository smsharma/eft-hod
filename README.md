# Simulation-based priors connecting EFT and HOD models

Used in ["Full-shape analysis with simulation-based priors: constraints on single field inflation from BOSS"](https://arxiv.org/abs/2402.13310) by Ivanov, Cuesta-Lazaro, Mishra-Sharma, Obuljen, and Toomey.

## Requirements

Install from `requirements.txt` or simply do
```bash
pip install torch numpy tqdm corner matplotlib nflows scipy
```

## Usage

Train density estimators in `notebooks/01_eft_fit.py`, sampling from priors and log-density calculation in `notebooks/02_usage.py`.
