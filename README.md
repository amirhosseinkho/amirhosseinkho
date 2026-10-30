# Amirhossein Khoshbakht

M.Sc. student in Computer Networks at Amirkabir University of Technology (Tehran Polytechnic), working on federated reinforcement learning for privacy-preserving on-device perception. I am seeking PhD positions starting in Fall 2027.

## Research Interests

- **Federated & Multi-Agent Reinforcement Learning**: collaborative policy learning across distributed agents without centralizing their data
- **Edge AI**: learning-based decision-making on resource-constrained wearable and edge devices
- **Privacy-Preserving Machine Learning**: training schemes that keep raw user data on the device
- **Machine Learning for Networking**: learning-based routing, resource allocation, and offloading at the edge
- **Continual & Self-Supervised Learning**: learning from unlabeled, temporally correlated data streams

## Current Work

My M.Sc. thesis addresses frame selection on smart glasses: an on-device reinforcement learning policy decides, for each captured frame, whether to upload it, upload a privacy-redacted (blurred) version, or discard it, trading learning value against privacy risk, battery, and bandwidth. The policy is trained with federated learning, so raw video never leaves the device. This matters because wearable cameras continuously capture both the user and bystanders.

## Selected Projects

- **[fedlab-repro](https://github.com/amirhosseinkho/fedlab-repro)**: Reproduction of FedAvg, FedProx, and SCAFFOLD under non-IID data, and a study of the trade-off between accuracy, communication (bytes), and differential privacy (Flower, Opacus, CIFAR-10, FEMNIST).
- **[stream-ssl-selection](https://github.com/amirhosseinkho/stream-ssl-selection)**: Budgeted frame selection for self-supervised learning on video streams, reproducing a replay-buffer result and comparing selection policies including a contextual bandit (SimSiam, CORe50, PyTorch).
- **[RL-SDN-Traffic-Engineering](https://github.com/amirhosseinkho/RL-SDN-Traffic-Engineering)**: Reinforcement-learning routing and traffic engineering in software-defined networks (DQN and PPO agents, Gymnasium environment, Ryu/OpenFlow, Mininet).
- **[graphRAG](https://github.com/amirhosseinkho/graphRAG)**: Knowledge-graph retrieval-augmented generation for biomedical question answering over Hetionet (graph traversal, PageRank, and community-detection retrieval; NetworkX, spaCy).
- **[iiot-fog-scheduling](https://github.com/amirhosseinkho/iiot-fog-scheduling)**: Workflow task scheduling in fog–cloud Industrial IoT, comparing an enhanced EPO-CEIS evolutionary algorithm with GA, PSO, and greedy heuristics (Java).

<!-- To add a project, copy this line above this comment:
- **[Name](https://github.com/amirhosseinkho/REPO)**: One-sentence description (methods/tools). -->

## Contact

Email: amirhossein.khoshb@gmail.com
