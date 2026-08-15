# Adaptive-Crypto-RL: A Reinforcement Learning Framework for Dynamic Lightweight Cryptography Selection in MapReduce

## 📌 Overview
Adaptive-Crypto-RL is an AI-driven extension for the MR-LWT (MapReduce LightWeight Cryptography) architecture. It replaces static cryptographic algorithm selection with an intelligent agent based on a **Deep Q-Network (DQN)**. The system evaluates cluster metrics (CPU, RAM, network load) and data sensitivity in real-time to select the optimal algorithm from a pool (Chacha20, Rabbit, NOEKEON, AES-CTR).

## 🚀 Key Features
- **Dynamic Selection:** Automates the choice of cryptographic primitives based on real-time cluster states.
- **Resource-Aware:** Optimizes the trade-off between execution speed, security level, and resource consumption.
- **Enterprise Security:** Integrated support for Hadoop KMS and Kerberos authentication.
- **Compatibility:** Fully backward compatible with existing HDFS/MapReduce pipelines.

## 📊 Experimental Results
Our experiments demonstrate:
- Up to **75% performance improvement** compared to standard AES(CBC).
- Over **50% gain** compared to HC-128 for large-scale datasets (1GB+).
- Negligible AI inference overhead (2-4 seconds).

## 📁 Repository Structure
- `/code`: DQN Agent implementation (`dqn_agent.py`) and simulation scripts.
- `/results`: Visualization of training convergence and performance heatmaps.
- `/data`: Sample configuration and metadata splits used for evaluation.

## 🛠 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Adaptive-Crypto-RL.git
