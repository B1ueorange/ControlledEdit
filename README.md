# ControlledEdit Dataset Usage Guide

This repository contains two controlled image editing datasets: **ControlledEdit30K** and **ControlledEditBench**.

---

## 📁 Dataset Structure
```
.
├── ControlledEdit30K/          # ControlledEdit30K dataset directory
├── ControlledEdit30K.jsonl     # ControlledEdit30K full dataset (JSON Lines format)
├── ControlledEditBench/       # ControlledEditBench dataset directory
└── controllededitbench_data.jsonl  # ControlledEditBench full dataset (JSON Lines format)
```

---

## 📊 Dataset Location
- **ControlledEdit30K**: The complete dataset is stored in `ControlledEdit30K.jsonl` (root directory), with related files in the `ControlledEdit30K/` folder.
- **ControlledEditBench**: The complete dataset is stored in `controllededitbench_data.jsonl` (root directory), with related files in the `ControlledEditBench/` folder.

---

## 📝 JSONL Format
Both datasets follow the standard **JSON Lines (JSONL)** format, where each line is a valid JSON object representing a single data sample.

