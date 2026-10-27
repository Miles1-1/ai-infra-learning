# AI Infrastructure Learning Journey

This repository contains my work for the AI Infrastructure Engineer curriculum.

## Structure

- `modules/` - Notes and exercises for each module
- `projects/` - Hands-on projects
- `exercises/` - Practice exercises
- `notes/` - Personal learning notes

## Progress

- [ ] Module 01: Foundations
- [ ] Project 01: Basic Model Serving
- ...
---

## Exercise 01: Environment Verification

### Setup Notes
- **OS:** Windows 11 + WSL2 (Ubuntu 22.04)
- **Python:** 3.10.12 (managed via `venv` virtual environment)
- **Network:** Configured `.wslconfig` to use mirrored networking mode to resolve proxy issues.
- **Docker:** Docker Desktop with WSL integration enabled.
- **Editor:** VS Code with Remote - WSL extension.

### Execution Results
Here is the successful execution of the environment test script:

WARNING: All log messages before absl::InitializeLog() is called are written to STDERR
I0000 00:00:1793119834.017678     760 port.cc:153] oneDNN custom operations are on. You may see slightly different numerical results due to floating-point round-off errors from different computation orders. To turn them off, set the environment variable `TF_ENABLE_ONEDNN_OPTS=0`.
I0000 00:00:1793119834.372162     760 cpu_feature_guard.cc:227] This TensorFlow binary is optimized to use available CPU instructions in performance-critical operations.
To enable the following instructions: AVX2 AVX512F AVX512_VNNI AVX512_BF16 FMA, in other operations, rebuild TensorFlow with the appropriate compiler flags.
WARNING: All log messages before absl::InitializeLog() is called are written to STDERR
I0000 00:00:1793119836.304843     760 port.cc:153] oneDNN custom operations are on. You may see slightly different numerical results due to floating-point round-off errors from different computation orders. To turn them off, set the environment variable `TF_ENABLE_ONEDNN_OPTS=0`.
I0000 00:00:1793119836.305783     760 cudart_stub.cc:31] Could not find cuda drivers on your machine, GPU will not be used.
===Environment Verification Successful ===
PyTorch Version: 2.14.1+cu130
TensorFlow Version: 2.21.0