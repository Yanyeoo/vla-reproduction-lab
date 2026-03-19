# VLA Reproduction Lab

This repository serves as an index of my reproduction and system-level
analysis projects on Vision-Language-Action (VLA) models.

## Research Interests
- Autonomous Driving Vision-Language-Action (VLA) models
- Multimodal inference efficiency and lightweight deployment

## Projects

### 01. FastV + Impromptu-VLA
- Repo: https://github.com/Yanyeoo/Fastv_Impromptu_VLA
- Keywords: FastV, token pruning, KV cache, sglang, Qwen2.5-VL
- Status: ✅ reproduced (HF) / ❌ infeasible (sglang, analyzed)

### 02. SimLingo (CarLLava) – Vision-Language-Action Closed-Loop Driving

* Repo: [https://github.com/Yanyeoo/simlingo](https://github.com/Yanyeoo/simlingo)
* Keywords: SimLingo, CarLLava, VLA, closed-loop inference, CARLA, Vulkan rendering
* Status: ✅ reproduced (closed-loop inference) / ❌ training & benchmark not reproduced (out of scope, analyzed)+ NOT visualization
* Notes:

  * Successfully ran **end-to-end closed-loop inference** with CARLA 0.9.15
  * Enabled **GPU Vulkan rendering** via NoMachine virtual display/local display (non-headless)
  * Validated full pipeline: *vision input → language-action alignment → high-level driving actions*
  * Focused on **system-level reproducibility and inference stability**, not model retraining
  
### 03. Survey

* Repo: [PRIVATE]([https://github.com/Yanyeoo/simlingo](https://github.com/Yanyeoo/Awesome-Efficient-VLA4AD))

### 04. MiniLLM TrainingPipline
    
* Repo: https://github.com/Yanyeoo/MiniLLM-TrainingPipeline

### 05.NEW IDEA
  
## About Me
I am a Master’s student (Class of 2025) in Computer Technology at the University of Electronic Science and Technology of China (UESTC).

My research focuses on Efficient Vision-Language-Action (VLA) models for autonomous driving. I am especially interested in how large multimodal models can be made practical and deployable under real-world latency and memory constraints.

Previously, I worked as an Algorithm Intern at iQIYI × Lilith (Middle Platform), where I focused on user profiling and user growth modeling, gaining hands-on experience in industrial-scale data, recommendation-related modeling, and system constraints in production environments.

Beyond research and engineering, I enjoy dancing and believe that long-term research thrives on curiosity, persistence, and collaboration. I’m always happy to connect and exchange ideas with people who share interests in autonomous driving, multimodal models, and efficient inference systems.
