# QRBT Results (Reproducible Skeleton)

This repository provides a minimal, reproducible skeleton for the **QRBT: Quantum-Driven Reinforcement Learning for Scalable Blockchain Transaction Processing** experiments.

## Quick start

```bash
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt

python -m qrbt.training.train_qrbt
python scripts/generate_results_tables.py
