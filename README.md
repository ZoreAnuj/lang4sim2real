# lang4sim2real: Bridging Sim2Real with Natural Language

This project explores how natural language descriptions can improve the transfer of robotic policies from simulation to the real world. It implements data collection and training pipelines for sim+real environments, based on the RSS 2024 paper.

## Key Features
*   Automated collection of paired (simulation, real-world) image data with textual annotations.
*   Training pipelines for vision-language models tailored for robotic perception.
*   Tools for evaluating sim2real transfer performance using language as an intermediary.
*   Integration with real-world robotic data streams via APIs.

## Tech Stack
Python, PyTorch, ROS, Hugging Face Transformers, custom simulation environments.

## Getting Started
```bash
git clone https://github.com/zoreanuj/lang4sim2real.git
cd lang4sim2real
pip install -r requirements.txt
# Follow setup instructions in /config for API keys and environment paths.
```