# Federated Learning IDS/IPS over SDN IoT Test Bed

> Final Year Project — Bachelor of Computer & Networking Engineering Technology, Canadian University of Dubai (2026)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Mininet](https://img.shields.io/badge/Mininet-231F20?style=flat-square)
![Ryu](https://img.shields.io/badge/Ryu%20Controller-231F20?style=flat-square)
![SDN](https://img.shields.io/badge/SDN-0B5394?style=flat-square)

A distributed **Intrusion Detection and Prevention System (IDS/IPS)** that combines **federated learning** with **Software Defined Networking (SDN)** to detect and respond to network attacks across an IoT test bed in real time — without centralising raw traffic.

## Overview

- Integrated **SDN controllers** with **machine-learning models** for real-time threat detection and automated prevention.
- Used a **federated-learning** approach so detection models train across distributed nodes while keeping local data local.
- Evaluated **performance, scalability, and detection accuracy** across multiple network environments.
- Conducted **analysis of network attacks** and the automated detection/response mechanisms triggered by the controller.

## Architecture

```
IoT / host nodes  →  Mininet emulated topology  →  Ryu SDN controller
                                                        │
                                   flow features  ──────┤
                                                        ▼
                              Federated ML models (TensorFlow / Keras)
                                                        │
                              detection result  ────────┤
                                                        ▼
                              controller installs / updates flow rules  (prevention)
```

## Tech Stack

| Area | Tools |
| --- | --- |
| SDN | Ryu Controller, OpenFlow, Mininet |
| Machine Learning | Python, TensorFlow, Keras, Federated Learning |
| Evaluation | Attack scenarios, detection-accuracy & scalability analysis |

## Status

This repository documents the project. The implementation code, evaluation results, and the final report will be added here.

## Author

**Dana Hammad** — [LinkedIn](https://www.linkedin.com/in/dana-hammad-00a277350) · Dubai, UAE
