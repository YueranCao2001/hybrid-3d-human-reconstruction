# Hybrid 3D Human Reconstruction

A research project on real-time dynamic 3D human reconstruction using RGB-D cameras, graph neural networks, LSTM temporal modeling, and probabilistic motion estimation.

---

## Overview

This project proposes a hybrid framework for reconstructing human body motion and geometry from single-view RGB-D input.

The system estimates visible motion, predicts occluded body movement, and reconstructs full dynamic human motion in real time.

---

## Key Features

- Single-view RGB-D reconstruction
- Real-time dynamic human modeling
- Occluded motion prediction
- Graph Neural Networks for spatial reasoning
- LSTM for temporal motion modeling
- Confidence-aware probabilistic estimation
- Lightweight hybrid architecture

---

## Pipeline

RGB-D Input  
→ Visible Motion Estimation  
→ Temporal Encoding (LSTM)  
→ Graph Neural Network  
→ Full Motion Prediction  
→ 3D Reconstruction

---

## Technical Stack

- Python
- PyTorch
- OpenCV
- NumPy
- RGB-D Camera
- GNN
- LSTM

---

## Applications

- VR / AR Avatar Reconstruction
- Motion Capture
- Gaming
- Medical Simulation
- Human-Computer Interaction
- Virtual Fitting

---

## Research Contributions

- Combines traditional reconstruction with deep learning
- Improves occluded region motion estimation
- Reduces hardware cost using single RGB-D sensor
- Enables robust dynamic reconstruction

---

## Future Work

- Higher fidelity mesh reconstruction
- Multi-person scenes
- Faster inference
- Transformer-based motion prediction

---

## License

Academic / Portfolio Use