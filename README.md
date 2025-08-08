# 🧠 LiquidTopoNet: Neuro-Inspired Temporal Graph Learning with GCNs and LTC

A cutting-edge hybrid architecture combining **Graph Convolutional Networks (GCNs)** with **Liquid Time-Constant (LTC) Neuron Layers** — inspired by MIT’s Liquid Networks — to enable **interpretable, time-aware, and continuous-time graph learning**.

---

## 📂 Project Overview

This repository presents a rigorous benchmark between:
- ✅ **LiquidTopoNet**: A novel integration of GCN spatial reasoning with LTC’s biologically inspired temporal adaptation.
- 🤖 **Standard GCN**: A widely used graph neural network baseline without continuous-time dynamics.

The models are evaluated on a real-world **temporal epidemiological graph** — the *Chickenpox Hungarian County Dataset* — predicting weekly infection cases at the node (county) level.

---

## 🔍 Key Features

- 🔁 **Hybrid Neural Architecture**:  
  Merges graph topology learning (GCNs) with continuous-time dynamics modeling (LTC neurons).
  
- ⏳ **Continuous-Time Temporal Processing**:  
  Captures fine-grained, evolving node states through trainable decay rates.

- 📈 **Robust Evaluation**:  
  Performance measured using **Mean Squared Error (MSE)** and **R² Score**.

- 📊 **Advanced Visualizations** for Interpretability:
  - Graph topology rendering with `networkx`
  - Training loss curves
  - Prediction vs actual scatter plots
  - Temporal correlation heatmaps
  - Per-node MSE bar plots for error localization

---

## 📘 Dataset

- **Chickenpox Hungarian County Dataset** from `torch_geometric_temporal`
- Nodes = Counties in Hungary  
- Edges = Geographic/epidemiological connections  
- Features = Weekly infection case counts  
- Temporal snapshots spanning multiple weeks

---

## 🧪 Dependencies

```bash
pip install torch torchvision torch-geometric torch-geometric-temporal matplotlib seaborn networkx scikit-learn


---

## 📘 Dataset

- **Chickenpox Hungarian County Dataset** from `torch_geometric_temporal`
- Nodes = Counties in Hungary  
- Edges = Geographic/epidemiological connections  
- Features = Weekly infection case counts  
- Temporal snapshots spanning multiple weeks

---

## 🧪 Dependencies

```bash
pip install torch torchvision torch-geometric torch-geometric-temporal matplotlib seaborn networkx scikit-learn
````

---

## 📈 Sample Results

| Model         | MSE ↓ | R² ↑ |
| ------------- | ----- | ---- |
| LiquidTopoNet | 0.020 | 0.84 |
| Standard GCN  | 0.050 | 0.62 |

LiquidTopoNet achieves **\~60% lower error** and **significantly better correlation** with ground truth compared to a vanilla GCN.

---

## 💡 Applications

* **Epidemic Spread Forecasting**
* **Traffic Flow Prediction**
* **Social Network Dynamics**
* **Financial Transaction Graph Modeling**
* **Infrastructure Network Monitoring**

---

## 📚 Research Inspiration

This work builds upon:

* [MIT CSAIL’s Liquid Time-Constant Networks](https://liquid.csail.mit.edu)
* Recent advancements in **temporal graph learning** and **neuro-inspired deep learning**

---

## 👨‍💻 Author

**Abhishek Yadav**
Computer Vision & AI Researcher
📌 Focus: Graph Neural Networks, Temporal Learning, Interpretable AI
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)
