# HARS-CD

**Hard-Aware Response Supervision for Multimodal Remote Sensing Change Detection**

This is the official repository for the paper *"HARS-CD: Hard-Aware Response Supervision for Multimodal Remote Sensing Change Detection"*.

> 🚧 **Status: source code and pretrained weights are being prepared.** Release details will be announced in this repository. Please star/watch the repository for updates.

## Introduction

HARS-CD is a multimodal remote sensing change detection (RSCD) framework built on three coordinated components:

- **LHPG** — LLM-Driven Hierarchical Prompt Generation: converts CLIP-predicted image tags into grounded, image-level textual prompts instead of fixed templates.
- **SRI** — Semantic Response Interaction: replaces the direct subtraction of bi-temporal semantic responses with learnable bi-temporal relation modeling.
- **HRD** — Hard-Aware Region-Distribution loss: directly regularizes the semantic difference response by penalizing high-response unchanged regions and encouraging complete activation over changed regions.

## Datasets

All experiments use public benchmarks: [LEVIR-CD](https://justchenhao.github.io/LEVIR-CD/), SYSU-CD, and WHU-CD, following the partition protocols in the paper.

## License

The license will be provided with the code release.

## Contact

Corresponding author: Prof. Ke Wang (`22014@ahu.edu.cn`). For questions about the code, please open an issue.
