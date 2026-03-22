# Lang4Sim2Real: Natural Language for Sim-to-Real Transfer

This project explores how natural language descriptions can bridge the gap between simulation and real-world robotics. It provides tools for collecting and training on paired data (simulation states + language) to improve policy transfer, based on the original RSS 2024 research.

## Key Features
*   Data collection pipeline for generating language-annotated trajectories in simulation.
*   Training framework for incorporating language cues into reinforcement learning policies.
*   Utilities for evaluating policy adaptation in both simulated and real environments.
*   Modular design for extending to new tasks and robotic platforms.

## Tech Stack
Python, PyTorch, ROS, OpenAI Gym, MuJoCo

## Getting Started
```bash
git clone https://github.com/zoreanuj/lang4sim2real.git
cd lang4sim2real
pip install -r requirements.txt
python scripts/collect_data.py --config configs/default.yaml
```