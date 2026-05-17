Sparse Speaker Verification with the Bregman Learning Framework

Overview

This project implements and compares three speaker verification approaches:

Baseline model
Unstructured pruning at 50%, 70%, and 90% sparsity
AdaBreg training (Bregman Learning Framework) at 50%, 70%, and 90% sparsity
The goal is to study how sparsity and Bregman-based optimization affect model performance, efficiency, and potential deployment in real-world voice authentication systems.

This work is based on my thesis and is currently being extended into a deployable voice authentication app.# sparse-speaker-verification
Sparse speaker verification project comparing baseline, unstructured pruning, and AdaBreg-trained models across multiple sparsity levels.

sparse-speaker-verification/
│
├── baseline/
│   ├── train_baseline.py
│   ├── configs/
│   │   └── baseline.yaml
│   └── results/
│
├── pruning/
│   ├── prune_50.py
│   ├── prune_70.py
│   ├── prune_90.py
│   └── results/
│
└── adabreg/
    ├── train_adabreg_50.py
    ├── train_adabreg_70.py
    ├── train_adabreg_90.py
    ├── configs/
    │   ├── adabreg_50.yaml
    │   ├── adabreg_70.yaml
    │   └── adabreg_90.yaml
    └── results/



