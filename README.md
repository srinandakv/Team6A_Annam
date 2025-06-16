# Pest Classification Using Deep Learning 

This project aims to develop a deep learning-based pest classification model using real-world agricultural pest image data. Ultimately, we plan to deploy the model into an application to assist farmers and agricultural experts in identifying pests and suggesting appropriate treatments.

---

## 🔍 Problem Statement

Pest infestations are a major threat to global crop productivity, particularly in regions with limited access to timely agricultural assistance. Manual identification of pests is labor-intensive, error-prone, and often infeasible in field conditions.

This project seeks to:
- Build an **accurate computer-vision model** for **pest classification** from images.
- Leverage the **IP102 dataset**, which contains **75,000+ images across 100+ pest species**.
- Build a **user-facing application** to accept pest images, identify the pest, and suggest **treatment or prevention strategies**.

---

## 🗓️ Week 1 Progress (June 2 – June 8)

### ✅ Milestone: Finalized Problem Statement & Direction

- Defined the domain as **pest classification** following literature review.
- Selected key papers for direction:
  - *Insect-Foundation: A Foundation Model and Large-scale 1M Dataset for Visual Insects* (CVPR 2024)
  - *IP102: A Large‑Scale Benchmark Dataset for Insect Pest Recognition* (CVPR 2019)
- Finalized use of the **IP102 dataset** as our benchmark.

📈 **Progress toward goal**: ~20% completed  
📌 Strong foundation for design, dataset prep, and roadmap planning

---

## 🗓️ Week 2 Progress (June 9 – June 15)

### ✅ Milestone: Developed & Evaluated Baseline Models

- Implemented two **baseline classification models** using PyTorch:
  - **ResNet-50** (pretrained on ImageNet)
  - **InceptionResNetV2** (pretrained on ImageNet)
- Set up:
  - Data augmentation and normalization
  - Model training loop with checkpointing, learning rate scheduler
  - Top-1 and Top-5 accuracy evaluation
  - Detailed classification report and confusion matrix
- **ResNet-50 Results:**
  - 📌 **Top-1 Accuracy**: 58%
  - 📈 **Top-5 Accuracy**: 81%


