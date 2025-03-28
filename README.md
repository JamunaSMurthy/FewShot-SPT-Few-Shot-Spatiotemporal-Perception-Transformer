# Towards Secure Video Surveillance: A Few-Shot Spatiotemporal Perception Transformer for Unseen Behavioral Anomalies

🚨 AVSS 2025 Submission [Under Review]  
**Real-time, Multimodal, Few-Shot Anomaly Detection** for Surveillance

---

## 🔍 Overview
FewShot-SPT detects unseen behavioral anomalies using:
- 🎯 Event-Guided Keyframe Extraction (EGKE)
- 🎛️ Adaptive Modality Gating (AMG)
- 🧠 Perceiver IO-based Attention
- 🧬 Adaptive Few-Shot Learning with Contrastive Loss

Supports **real-time inference on Jetson Orin** and **2-way 5-shot learning** on UCF-Crime, XD-Violence.

---

## 📊 Performance
| Dataset       | AUC (2-way 5-shot) | Accuracy (5-way 5-shot) |
|---------------|--------------------|--------------------------|
| UCF-Crime     | 95.1%              | 76.8%                    |
| XD-Violence   | 91.2%              | 84.5%                    |

---

## 🚀 Real-Time Deployment
- ⚡ ~14ms/frame (NVIDIA A100)
- ⚙️ Jetson Orin Ready
- 📦 Torch + Transformers + ONNX export

---

## 🧠 Explainability (XAI)
Includes attention visualizations and modality attribution for transparent anomaly detection.

---

## 📁 Coming Soon
- Pretrained models & scripts
- Real-time park surveillance demo
- Web UI dashboard

---

## 🤝 License
To be released under MIT License.
