好，我直接把首页再往“正式可对外展示”的版本推进一版。下面这份是**升级后的完整 `index.md`**，在你当前版本基础上补了：

* 更完整的首页结构
* `Links` 区块（先占位，后面你补真实链接）
* `Citation` 区块
* `License` 区块
* 更清晰的项目定位和入口说明

你可以直接整体替换。

````markdown
# U6G XL-MIMO Radiomap Prediction: Multi-config Dataset & Beam Map Approach

A benchmark dataset for **multi-configuration radiomap prediction** in **U6G / XL-MIMO** systems, featuring **800 scenes**, **multi-frequency**, **multi-antenna**, and **multi-beam** settings.

[Dataset](dataset.md){ .md-button } [Quickstart](quickstart.md){ .md-button } [Benchmark](benchmark.md){ .md-button } [Pretrained](pretrained.md){ .md-button }

---

## Overview

This project provides a benchmark for studying:

- **multi-configuration radiomap prediction**
- **cross-configuration generalization**
- **cross-environment generalization**
- **beam-aware radiomap modeling**
- **sparse radiomap reconstruction**

A key feature of this dataset is the joint release of:

- **height maps**
- **configuration-only beam maps**
- **ray-tracing radiomap labels**
- **optional mesh assets for ray-tracing reproduction**
- **pretrained UNet and GAN baselines**

---

## What’s Included

- **Dataset** (`Dataset/`)
  - height maps
  - radiomaps
  - configuration-only beam maps
  - optional mesh assets
- **Baselines**
  - UNet training / evaluation scripts
  - GAN training / evaluation scripts
- **Pretrained models** (`Pretrained_Model/`)
  - GAN checkpoints for 8 benchmark tasks
  - UNet checkpoints and visualizations
- **Dataset generation pipeline**
  - OSM → Sionna meshes → height maps → ray-tracing radiomaps → beam maps

---

## Quick Facts

- Scenes: **800** (`u1..u800`)
- Frequencies: **1.8 / 2.6 / 3.5 / 4.9 / 6.7 GHz**
- TX antennas: up to **1024 TR**
- Beam counts: **1 / 8 / 16 / 64**
- Beam pattern: **3GPP TR 38.901**

---

## Recommended Entry Points

If you are new to this project, start with:

- **Dataset** — understand the folder structure and naming rules
- **Quickstart** — run pretrained evaluation
- **Benchmark** — understand the 8 benchmark task settings
- **Pretrained** — inspect available GAN / UNet checkpoints

---

## Links

- **Project Website:** this page
- **Code Repository:** *(GitHub repo link can be added here)*
- **Dataset Download:** *(to be added)*
- **Pretrained Models Download:** *(to be added)*
- **Paper / Preprint:** *(to be added)*

---

## Project Status

This website is being finalized.

The current release already includes:

- dataset structure documentation
- benchmark task definitions
- pretrained model organization
- quickstart instructions for evaluation

Future updates will include:

- detailed tensor shape / unit documentation
- exact preprocessing conventions
- refined UNet checkpoint-to-task mapping
- dataset / model download links
- paper / citation details

---

## Citation

If you use this project, please cite the corresponding paper.

```bibtex
@article{to_be_added,
  title   = {U6G XL-MIMO Radiomap Prediction: Multi-config Dataset and Beam Map Approach},
  author  = {Xiaojie Li and collaborators},
  journal = {to be added},
  year    = {2026}
}
````

> The final BibTeX entry will be updated after the paper metadata is finalized.

---

## License

* **Code:** released under the **MIT License**
* **Dataset:** license information will be specified separately

---

## Contributor

**Xiaojie Li (李宵杰)**
Email: `xiaojieli@seu.edu.cn/xiaojieli@nuaa.edu.cn`
