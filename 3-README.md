# Prateek Mehra

## Checkout my live projects

[Where did I apply](https://github.com/prateek-mehra/where-did-i-apply): Chrome extension for job application tracking over different platforms.

<p align="center">
  <img src="assets/where-did-i-apply-demo.gif" width="1000"/>
</p>

[Minimal eisenhower](https://minimal-eisenhower.vercel.app/): Simple to-do list app based on the eisenhower matrix framework. 

<p align="center">
  <img src="assets/minimal-eisenhower-demo.gif" width="1000"/>
</p>

[Tree of life](https://tree-of-lifee.vercel.app/): My attempt to get an overview of my life from ground up, using first principles.

![Tree of Life Demo](assets/tree-of-life.png)

## Core Projects

### [jalLijiye](https://github.com/prateek-mehra/jalLijiye)

Context-aware hydration reminder system using real-time object detection. 

- Detects presence of person and water bottle
- Tracks interaction and inactivity windows
- Rule-based alert triggering logic
- Designed for lightweight edge deployment

## Experiments and benchmarks

### [turn-detection](https://github.com/prateek-mehra/turn-detection)
Audio-only endpoint detection (has the speaker finished their turn?). Frozen Whisper Tiny embeddings + XGBoost beat handcrafted acoustic features: ROC-AUC 0.753 to 0.848, F1 0.690 to 0.787 after threshold tuning. Ablation shows energy features carry almost all the signal of the handcrafted set.

<p align="center">
  <img src="assets/turn-detection-results.png" width="1000"/>
</p>

### [jalLijiye](https://github.com/prateek-mehra/jalLijiye)
Edge-inference optimization for the bottle detector on an Apple M1 MacBook Air. FP16 Core ML vs PyTorch on MPS over the same 132 frames: 21.5 vs 24.8 ms/frame, about 30% less memory after measurement, bottle presence agreed on 131/132 frames. Isolated inference runs, not full-app.

<p align="center">
  <img src="assets/jallijiye-benchmarks.png" width="1000"/>
</p>

## Engineering Focus

- Real-time perception systems
- Edge ML optimization
- Benchmark-driven engineering
- Production ML pipelines

---

## Stack

Python | C++ | Docker | Linux | AWS | GCP  
Experience with Kubernetes, Postgres, system-level debugging, and cloud-native ML systems.

---

## Contact

LinkedIn: https://www.linkedin.com/in/1prateekmehra1/  
Email: partumehra@gmail.com

