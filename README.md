<div align="center">

# 🧪 LabEvolver

**Training-Free Experience Evolution for Safe and Grounded Wet-Lab Agents**

[![arXiv](https://img.shields.io/badge/arXiv-2607.27690-b31b1b.svg?logo=arxiv)](https://arxiv.org/abs/2607.27690)
[![Project Page](https://img.shields.io/badge/Project-Page-blue.svg)](https://andygao6186.github.io/LabEvolver/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

*A state-grounded, training-free dual-loop framework that combines safe closed-loop embodied execution with post-trial experience evolution.*

</div>

## 📣 News
- **[Coming Soon]** 💻 The full training and evaluation code will be open-sourced soon! Please ⭐ star this repository and stay tuned for updates.
- **[2026.07]** 📄 Our paper is available on [arXiv](https://arxiv.org/abs/2607.27690)! 

---

## 📖 Overview

**LabEvolver** equips safe and grounded wet-lab agents with episodic memory from execution experience. We introduce a novel **dual-loop framework**:

1. **Inner Trial Loop 🔄**: Provides adaptive perception, online planning, and safety validation (Tri-layer Runtime Safety Gate) for robust execution.
2. **Outer Evolution Loop 🧠**: Distills completed trajectories into reusable skill-level, strategy-level, and safety-level experience via the *Strategist* module.

<p align="center">
  <!-- Place your main teaser figure here. We reference the latest paper figures directory -->
  <img src="assets/images/labevolver/figure2_framework.png" alt="LabEvolver Framework" width="90%">
</p>

---

## ✨ Key Highlights

- 📈 **ALFWorld Continual Evaluation**: Improved cumulative success rate within 20 steps from 76.2% (ReAct) to **91.4%** over 500 continual long-horizon tasks.
- 🚰 **Transferable Quantitative-Pouring**: Learns and transfers precise pouring skills across different target masses and liquids (water, sucrose, olive oil) via physical feedback.
- 🧪 **Closed-Loop pH Regulation**: Reduces pH-regulation completion time by 48.2% and safety-gate intercepts by 60.0% in real-world wet-lab environments.
- ⚗️ **Coupled pH–EC Multi-Objective Regulation**: Handles complex multi-objective interactions by reusing high-relevance joint trajectory experience.

---

## 🎥 Video Demonstration

<!-- Embed a GIF here for immediate visual impact -->
<p align="center">
  <img src="assets/images/labevolver/demo.gif" alt="LabEvolver Demo" width="80%">
</p>

> 💡 **Full Video:** The complete annotated experiment video is available in our [v1.0 GitHub Release](https://github.com/USER/LabEvolver/releases/tag/video-v1).

---

## 📂 Repository Structure

The current structure hosts our project page and assets. The codebase will be structured as follows upon release:

```text
LabEvolver/
├── index.html                   # GitHub Pages project homepage (English/Chinese w/ language switcher)
├── assets/
│   ├── images/
│   │   └── labevolver/          # Latest paper figures
│   └── ...                      # Existing historical figures
├── core/                        # [Code Coming Soon] Inner trial & outer evolution loop implementation
├── envs/                        # [Code Coming Soon] Interfaces for robotic wet-lab & ALFWorld
└── scripts/                     # [Code Coming Soon] Evaluation and execution scripts
```

---

## 📝 Citation

If you find our work helpful, please consider citing our paper:

```bibtex
@article{wang2026labevolver,
  title={LabEvolver: Training-Free Experience Evolution for Safe and Grounded Wet-Lab Agents},
  author={Wang, Jingya and Gao, Yuyang and Lv, Liuzhenghao and Tian, Yonghong and Liu, Yuyang},
  journal={arXiv preprint arXiv:2607.27690},
  year={2026}
}
```

## 🤝 Acknowledgements
This project is developed by researchers at the School of AI for Science and School of Computer Science, Peking University. 
