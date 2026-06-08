# VLA/WAM Reproduction Lab

This repository serves as an index of my reproduction and system-level analysis projects focusing on World Models (WM) and Vision-Language-Action (VLA) architectures.

## Research Interests
- **Efficient WM + VLA** in Games and Autonomous Driving (AD)
- **Multimodal Inference Efficiency** (spanning Architecture, Training, Inference, and Deployment)
- **Vertical Domain Post-Training / Agentic SFT**

## Projects

### 01. FastV + Impromptu-VLA
- **Repo:** https://github.com/Yanyeoo/Fastv_Impromptu_VLA
- **Keywords:** FastV, token pruning, KV cache, sglang, Qwen2.5-VL
- **Status:** ✅ reproduced (HF) / ❌ infeasible (sglang, analyzed)

### 02. SimLingo (CarLLava) – Vision-Language-Action Closed-Loop Driving
- **Repo:** [https://github.com/Yanyeoo/simlingo](https://github.com/Yanyeoo/simlingo)
- **Keywords:** SimLingo, CarLLava, VLA, closed-loop inference, CARLA, Vulkan rendering
- **Status:** ✅ reproduced (closed-loop inference) / ❌ training & benchmark not reproduced (out of scope, analyzed) + NOT visualization
- **Notes:**
  - Successfully ran **end-to-end closed-loop inference** with CARLA 0.9.15.
  - Enabled **GPU Vulkan rendering** via NoMachine virtual display/local display (non-headless).
  - Validated full pipeline: *vision input → language-action alignment → high-level driving actions*.
  - Focused on **system-level reproducibility and inference stability**, rather than model retraining.

### 03. AerialVLA: A Vision-Language-Action Model for UAV Navigation
- **Repo:** https://github.com/XuPeng23/AerialVLA
- **Keywords:** UAV Navigation, Multimodal Large Models, Embodied AI, VLA
- **Status:** Active Research
- **Notes:** Applying multimodal large models to unmanned aerial vehicles for robust navigation and decision-making.

### 04. Survey: Empowering Embodied AI for Autonomous Driving
- **Repo:** [PRIVATE](https://github.com/Yanyeoo/Awesome-Efficient-VLA4AD)
- **Keywords:** Systematic Survey, Autonomous Driving, Embodied AI

### 05. MiniLLM Training Pipeline
- **Repo:** https://github.com/Yanyeoo/MiniLLM-TrainingPipeline
- **Keywords:** LLM Training, Pipeline Optimization

### 06. Scene-Based Dynamic Pruning 
- **Repo:** https://github.com/Yanyeoo/RL-Drive
- **Keywords:** Token Pruning, AutoVLA, WAM migration
- **Notes:** Exploring dynamic pruners based on scene context (originally based on AutoVLA, currently migrating to WAM).

### 07. Game Packaging Testing & GUI Agents
- **Status:** In Progress
- **Notes:** Developing in-game and out-of-game GUI Agents alongside automated game packaging and testing workflows.

### 08. Efficient WAM
- **Status:** In Progress
- **Notes:** Continued research on World-Action Model lightweighting and inference acceleration.

## About Me
I am a Master’s student (Class of 2028) in Computer Technology at the Shenzhen Institute for Advanced Study, University of Electronic Science and Technology of China (UESTC). 

My research focuses on **Efficient Vision-Language-Action (VLA) models** and **inference acceleration**. I am especially interested in how large multimodal models can be made practical and deployable under real-world latency and memory constraints.

Previously, I gained professional experience as an Algorithm Intern at **iQIYI** (focusing on LLM-based user profiling) and **Lilith Games** (focusing on user growth and intelligent advertising), acquiring hands-on experience with industrial-scale data, recommendation modeling, and production system constraints. 

**Current Role:** Large Model Algorithm Research Intern at **Tencent IEG (Interactive Entertainment Group)**.

Beyond research and engineering, I enjoy dancing and believe that long-term research thrives on curiosity, persistence, and collaboration. I’m always happy to connect and exchange ideas with people who share interests in autonomous driving, UAV navigation, multimodal models, and efficient inference systems.
