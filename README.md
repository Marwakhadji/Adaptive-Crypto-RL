# Adaptive-Crypto-RL: A Reinforcement Learning Framework for Dynamic Lightweight Cryptography Selection in MapReduce

This repository contains the implementation, experimental data, and results for the paper **"Adaptive-Crypto-RL: A Reinforcement Learning Framework for Dynamic Lightweight Cryptography Selection in MapReduce"**.

## Project Structure

- `code/`: Implementation of the Deep Q-Network (DQN) agent and the MapReduce encryption/decryption simulation scripts.
- `data/`: Sample datasets and configuration files used for experiments.
- `results/`: Visualization of training convergence, performance improvements, and resource usage (CPU/RAM).

## Abstract

Secure large-scale data processing (Big Data) in distributed environments such as Hadoop MapReduce poses a significant ongoing challenge of balancing performance and security. This framework proposes **Adaptive-Crypto-RL**, a dynamic selection system based on a Deep Q-Network (DQN) that evaluates the cluster state in real-time to select the optimal lightweight cryptographic algorithm.

## Getting Started

### Prerequisites
- Python 3.8+
- PyTorch / TensorFlow
- NumPy, Pandas, Matplotlib

### Installation
```bash
git clone https://github.com/marwakhadji/Adaptive-Crypto-RL.git
cd Adaptive-Crypto-RL
pip install -r requirements.txt
```

## Citation
If you use this work in your research, please cite our paper:
> Khadji, M., et al. (2026). Adaptive-Crypto-RL: A Reinforcement Learning Framework for Dynamic Lightweight Cryptography Selection in MapReduce.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
