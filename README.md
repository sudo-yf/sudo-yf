<h1 align="center">Hi, I'm Yifan Liu</h1>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3200&pause=800&color=6EA8FE&center=true&vCenter=true&width=760&lines=Safety+Engineering+%40+SCUT;Embodied+AI+%2F+VLA+Models+%2F+Robot+Data+Flywheel;Bimanual+and+General-Purpose+Manipulation" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://wui.me">Website</a> ·
  <a href="https://wui.me/blog">Blog</a> ·
  <a href="https://github.com/sudo-yf">GitHub</a> ·
  <a href="mailto:addshiyi@gmail.com">Email</a>
</p>

---

## About

<img align="right" width="250" src="https://chiikawa.r2.1591420.xyz/images/default/04.gif" alt="Chiikawa animation" />

I'm an undergraduate student at **South China University of Technology (SCUT)**, majoring in **Safety Engineering**.

Since October 2025, I have been working on embodied AI and Vision-Language-Action models in Associate Professor Huiping Zhuang's research group at SCUT.

My current work focuses on embodied AI, VLA policy reproduction and evaluation, robot data flywheels, bimanual manipulation, and safety-oriented computer vision.

## Research Interests

- Embodied AI and Vision-Language-Action models
- Data flywheel systems for robot learning
- Bimanual and general-purpose manipulation
- Real-robot data collection and policy deployment
- Computer vision, semantic segmentation, and safety engineering applications

## Selected Projects

### [ICRA 2026 LeHome Challenge](https://github.com/sudo-yf/lehome-challenge)

VLA policy reproduction, training, evaluation, and data engineering for bimanual garment manipulation.

- Reproduced and evaluated **ACT, Diffusion Policy, SmolVLA, X-VLA, pi0, and KAI0**.
- Ran systematic W&B experiments on learning rates, training steps, checkpoints, pretrained weights, and image augmentation.
- Improved the Top-Long success rate from **76.67% to 86.67%** under a unified 60-episode evaluation.
- Built an end-to-end data flywheel covering rollout, trajectory filtering, LeRobot Dataset merging, and retraining.
- Curated **291 high-quality successful trajectories**.
- Fixed `file_index` misalignment and missing `finalize()` issues that caused Parquet and dataset merging failures.
- The team reached a final success rate of **59.25%** and ranked **17th globally** in the Simulation Track.

### [Weak-Boundary Smoke Semantic Segmentation](https://github.com/sudo-yf/DeepLabV3Plus)

Semantic segmentation for smoke with weak boundaries, smoke-cloud confusion, and complex fire-safety scenes.

- Conducted more than ten smoke-burning experiments and collected over one hundred real smoke samples.
- Used SAM 3 for semi-automatic annotation and supplemented the dataset with 90 generated multi-scene smoke images.
- Collected and standardized **9,124 smoke segmentation images**.
- Built a `train / val / test = 8000 / 833 / 291` split, with 291 high-quality manually annotated samples as the independent test set.
- Introduced CE and Focal Tversky Loss into DeepLabV3+, improving mIoU from **78.4% to 82.4%**.

### Intelligent Laboratory Chemical Management System

An edge-model-based hazardous-chemical management system for laboratory intake, checkout, return, auditing, and anomaly tracking.

- Delivered and deployed the first runnable version within two days.
- Integrated face recognition, chemical-label OCR, and electronic-scale serial communication.
- Used InsightFace to associate operators with chemical transactions and abnormal events.
- Used RapidOCR and PaddleOCR for chemical-label recognition.
- Combined name normalization and fuzzy matching with an index of **41,977 IECSC chemical names**.
- Deployed online at [scut.leai.me](https://scut.leai.me).

### [Argus Dual-Agent System](https://github.com/Argus-Agent/argus)

A collaborative execution framework combining a GUI Agent and a Code Agent for computer-use tasks.

- Designed Smart Router, failure fallback, Tool Calling, and Agent Memory mechanisms.
- Supported screenshot understanding, window control, mouse and keyboard interaction, and code execution.
- Used Doubao UI-TARS 1.5 7B for graphical interface understanding.
- Deployed OpenCUA and conducted basic evaluations on OSWorld.
- Developed GUI and CLI interfaces, Docker support, automated tests, and CI workflows.
- Open-sourced the project and released an executable version.

## Technical Skills

```text
Programming      Python · PyTorch · Linux · Git
Robot Learning   LeRobot · Isaac Lab · Isaac Sim · real-robot data collection
VLA Policies     ACT · Diffusion Policy · SmolVLA · X-VLA · pi0 · KAI0
Vision / OCR     Semantic segmentation · InsightFace · RapidOCR · PaddleOCR
Agentic Coding   Claude Code · Codex · Cursor
```

## Open Source

- Submitted a merged pull request to the **2k+ star** open-source project [CodeIsland](https://github.com/wxtsky/CodeIsland).
- Fixed crashes in Chinese multi-select interactions and incorrect handling of empty responses in `AskUserQuestion`.

## Education

**South China University of Technology**<br>
B.Eng. Candidate in Safety Engineering<br>
September 2024 - June 2028

Relevant coursework: Linear Algebra, Calculus, Python Programming, Introduction to Artificial Intelligence.

## Additional Experience

- Participant in **two national-level undergraduate innovation projects**.
- Recipient of **two provincial-level mathematical modeling awards**.

## Current Focus

- VLA policy reproduction, training, and evaluation
- Data flywheel workflows for robot learning
- Real-robot data collection and policy deployment
- Bimanual and general-purpose manipulation

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sudo-yf&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sudo-yf&layout=compact&theme=transparent&hide_border=true&langs_count=8" alt="Top languages" />
</p>
