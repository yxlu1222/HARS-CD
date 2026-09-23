# HARS-CD

**Hard-Aware Response Supervision for Multimodal Remote Sensing Change Detection**

This is the official repository for the paper *"HARS-CD: Hard-Aware Response Supervision for Multimodal Remote Sensing Change Detection"*.

> 🚧 **Status: source code and pretrained weights are being prepared.** Release details will be announced in this repository. Please star/watch the repository for updates.

## Introduction

HARS-CD is a multimodal remote sensing change detection (RSCD) framework built on three coordinated components:

- **LHPG** — LLM-Driven Hierarchical Prompt Generation: converts CLIP-predicted image tags into grounded, image-level textual prompts instead of fixed templates.
- **SRI** — Semantic Response Interaction: replaces the direct subtraction of bi-temporal semantic responses with learnable bi-temporal relation modeling.
- **HRD** — Hard-Aware Region-Distribution loss: directly regularizes the semantic difference response by penalizing high-response unchanged regions and encouraging complete activation over changed regions.

## Results (preview)

| Method | LEVIR-CD IoU | SYSU-CD IoU | WHU-CD IoU |
|---|---|---|---|
| ChangeCLIP (ISPRS 2024) | 84.71 | 70.53 | 88.38 |
| MdaCD (TGRS 2025) | 84.24 | 70.94 | 87.14 |
| **HARS-CD (Ours)** | **85.16** | **72.44** | **89.85** |

Full per-metric tables (Pre/Rec/F1/IoU/mIoU/OA on six metrics × three datasets) are available in the paper.

## Datasets

All experiments use public benchmarks: [LEVIR-CD](https://justchenhao.github.io/LEVIR-CD/), SYSU-CD, and WHU-CD, following the partition protocols in the paper.

## License

The license will be provided with the code release.

## Citation

The citation entry will be updated after publication. For the current manuscript, please use:

```bibtex
@misc{luharscd2026,
  author  = {Lu, Yanxi and Li, Duoyang and Wu, Zhaoli and Wang, Ke},
  title   = {HARS-CD: Hard-Aware Response Supervision for Multimodal Remote Sensing Change Detection},
  year    = {2026},
  note    = {Manuscript under review}
}
```

## Contact

Corresponding author: Prof. Ke Wang (`22014@ahu.edu.cn`). For questions about the code, please open an issue.
