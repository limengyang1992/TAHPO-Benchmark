# TAHPO-Benchmark


This is the official repository for the **TAHPO-Benchmark**, a large-scale, dynamics-centric dataset for Hyperparameter Optimization (HPO), introduced in our paper:

**TAHPO-LLM: Task-Aware Hyperparameter Optimization with Large Language Models**  
*By: Mengyang Li, Pinlong Zhao, Ou Wu*

Traditional HPO benchmarks often focus on a limited set of "clean" tasks and provide only static mappings of hyperparameters to final performance. TAHPO-Benchmark is designed to bridge this gap by providing rich, dynamic training logs for thousands of diverse and systematically challenging tasks. It is created to facilitate research in next-generation HPO methods, especially those that are task-aware, feedback-driven, and leverage the power of Large Language Models.

---

## Key Features

-   **Large-Scale and Diverse**: Contains **50,000** complete HPO experiments, corresponding to 10-trial HPO trajectories for each of the **5,000** unique image classification tasks.
-   **Systematic Challenges**: Tasks are programmatically generated to include common real-world data challenges, such as:
    -   **Long-tail distributions** with varying imbalance ratios.
    -   **Symmetric and asymmetric label noise** at different corruption levels.
-   **Rich, Dynamic Logs**: Unlike traditional benchmarks, each trial includes the **full training history**, not just the final score. This includes:
    -   Static task metadata (model architecture, dataset properties, noise info).
    -   The specific hyperparameter configuration used.
    -   Per-epoch time-series data for metrics like training/validation loss and accuracy.
-   **Designed for Modern HPO Research**: The rich, structured data is ideal for developing and evaluating meta-learning, transfer learning, and LLM-based HPO agents that can reason from runtime feedback.

---

## Download the Dataset

The full TAHPO-Benchmark dataset is hosted on Baidu Netdisk.

**➡️ Download Link**: [https://pan.baidu.com/s/14vobhEeDKPUIfOpa5EKQMw?pwd=pgsv]






