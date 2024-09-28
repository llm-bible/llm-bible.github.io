---
layout: publication
title: LLM-Personalize Aligning LLM Planners with Human Preferences via Reinforced Self-Training for Housekeeping Robots
authors: Han Dongge, Mcinroe Trevor, Jelley Adam, Albrecht Stefano V., Bell Peter, Storkey Amos
conference: "Arxiv"
year: 2024
bibkey: han2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14285"}
tags: ['LLM-CP', 'Applications', 'LLM', 'Arxiv']
---
Large language models (LLMs) have shown significant potential for robotics applications particularly task planning by harnessing their language comprehension and text generation capabilities. However in applications such as household robotics a critical gap remains in the personalization of these models to individual user preferences. We introduce LLM-Personalize a novel framework with an optimization pipeline designed to personalize LLM planners for household robotics. Our LLM-Personalize framework features an LLM planner that performs iterative planning in multi-room partially-observable household scenarios making use of a scene graph constructed with local observations. The generated plan consists of a sequence of high-level actions which are subsequently executed by a controller. Central to our approach is the optimization pipeline which combines imitation learning and iterative self-training to personalize the LLM planner. In particular the imitation learning phase performs initial LLM alignment from demonstrations and bootstraps the model to facilitate effective iterative self-training which further explores and aligns the model to user preferences. We evaluate LLM-Personalize on Housekeep a challenging simulated real-world 3D benchmark for household rearrangements and show that LLM-Personalize achieves more than a 30 percent increase in success rate over existing LLM planners showcasing significantly improved alignment with human preferences. Project page https://donggehan.github.io/projectllmpersonalize/.
