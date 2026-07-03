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

<table>
  <tr>
    <td width="50%" valign="top">
      <details>
        <summary>
          <b><a href="https://github.com/sudo-yf/lehome-challenge">ICRA 2026 LeHome Challenge</a></b><br>
          <sub>VLA policies · LeRobot data · bimanual garment manipulation</sub>
        </summary>
        <br>
        <p>VLA policy reproduction, training, evaluation, and data engineering for bimanual garment manipulation.</p>
        <ul>
          <li>Reproduced and evaluated <b>ACT, Diffusion Policy, SmolVLA, X-VLA, pi0, and KAI0</b>.</li>
          <li>Ran systematic W&B experiments on learning rates, training steps, checkpoints, pretrained weights, and image augmentation.</li>
          <li>Improved the Top-Long success rate from <b>76.67% to 86.67%</b> under a unified 60-episode evaluation.</li>
          <li>Built an end-to-end data flywheel covering rollout, trajectory filtering, LeRobot Dataset merging, and retraining.</li>
          <li>Curated <b>291 high-quality successful trajectories</b>.</li>
          <li>Fixed <code>file_index</code> misalignment and missing <code>finalize()</code> issues that caused Parquet and dataset merging failures.</li>
          <li>The team reached a final success rate of <b>59.25%</b> and ranked <b>17th globally</b> in the Simulation Track.</li>
        </ul>
      </details>
    </td>
    <td width="50%" valign="top">
      <details>
        <summary>
          <b><a href="https://github.com/sudo-yf/DeepLabV3Plus">Weak-Boundary Smoke Semantic Segmentation</a></b><br>
          <sub>Fire-safety vision · smoke datasets · DeepLabV3+</sub>
        </summary>
        <br>
        <p>Semantic segmentation for smoke with weak boundaries, smoke-cloud confusion, and complex fire-safety scenes.</p>
        <ul>
          <li>Conducted more than ten smoke-burning experiments and collected over one hundred real smoke samples.</li>
          <li>Used SAM 3 for semi-automatic annotation and supplemented the dataset with 90 generated multi-scene smoke images.</li>
          <li>Collected and standardized <b>9,124 smoke segmentation images</b>.</li>
          <li>Built a <code>train / val / test = 8000 / 833 / 291</code> split, with 291 high-quality manually annotated samples as the independent test set.</li>
          <li>Introduced CE and Focal Tversky Loss into DeepLabV3+, improving mIoU from <b>78.4% to 82.4%</b>.</li>
        </ul>
      </details>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <details>
        <summary>
          <b>Intelligent Laboratory Chemical Management System</b><br>
          <sub>Face recognition · OCR · inventory audit · <a href="https://scut.leai.me">scut.leai.me</a></sub>
        </summary>
        <br>
        <p>An edge-model-based hazardous-chemical management system for laboratory intake, checkout, return, auditing, and anomaly tracking.</p>
        <ul>
          <li>Delivered and deployed the first runnable version within two days.</li>
          <li>Integrated face recognition, chemical-label OCR, and electronic-scale serial communication.</li>
          <li>Used InsightFace to associate operators with chemical transactions and abnormal events.</li>
          <li>Used RapidOCR and PaddleOCR for chemical-label recognition.</li>
          <li>Combined name normalization and fuzzy matching with an index of <b>41,977 IECSC chemical names</b>.</li>
          <li>Deployed online at <a href="https://scut.leai.me">scut.leai.me</a>.</li>
        </ul>
      </details>
    </td>
    <td width="50%" valign="top">
      <details>
        <summary>
          <b><a href="https://github.com/Argus-Agent/argus">Argus Dual-Agent System</a></b><br>
          <sub>GUI Agent · Code Agent · computer-use automation</sub>
        </summary>
        <br>
        <p>A collaborative execution framework combining a GUI Agent and a Code Agent for computer-use tasks.</p>
        <ul>
          <li>Designed Smart Router, failure fallback, Tool Calling, and Agent Memory mechanisms.</li>
          <li>Supported screenshot understanding, window control, mouse and keyboard interaction, and code execution.</li>
          <li>Used Doubao UI-TARS 1.5 7B for graphical interface understanding.</li>
          <li>Deployed OpenCUA and conducted basic evaluations on OSWorld.</li>
          <li>Developed GUI and CLI interfaces, Docker support, automated tests, and CI workflows.</li>
          <li>Open-sourced the project and released an executable version.</li>
        </ul>
      </details>
    </td>
  </tr>
</table>

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
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=sudo-yf&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=sudo-yf&layout=compact&theme=transparent&hide_border=true&langs_count=8" alt="Top languages" />
</p>
