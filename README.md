# UniMol-HEDH-Fuel
Pretrained 3D Molecular Representations Enable Data-Efficient Discovery of High-Energy-Density Fuels

## Data and Checkpoints

This repository provides the molecular subsets used in our workflow:

- `gdb13_hc_c11_c13.csv` — GDB13 hydrocarbon subset (C11–C13) for fine-tuning
- `qme14s_hc_c11_c17.csv` — QMe14S hydrocarbon subset (C11–C17) for continued fine-tuning
- `gdb17_hc_subset.csv` — GDB17 hydrocarbon subset for screening

Due to GitHub file size limits, trained checkpoints are hosted on Hugging Face:

**Hugging Face:** https://huggingface.co/zhaiwenxi/UniMol-HEDH-Fuel/

The Hugging Face repository includes the fine-tuned models and related files (e.g., `config.yaml`, `metric.result`, `target_scaler.ss`, and fold checkpoints).
