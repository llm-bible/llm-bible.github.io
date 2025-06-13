---
layout: publication
title: 'Motiongpt-2: A General-purpose Motion-language Model For Motion Generation And Understanding'
authors: Yuan Wang, Di Huang, Yaqi Zhang, Wanli Ouyang, Jile Jiao, Xuetao Feng, Yan Zhou, Pengfei Wan, Shixiang Tang, Dan Xu
conference: "Arxiv"
year: 2024
bibkey: wang2024motiongpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.21747"}
tags: ['Masked Language Model', 'Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Merging', 'GPT', 'Pretraining Methods', 'Prompting']
---
Generating lifelike human motions from descriptive texts has experienced
remarkable research focus in the recent years, propelled by the emerging
requirements of digital humans.Despite impressive advances, existing approaches
are often constrained by limited control modalities, task specificity, and
focus solely on body motion representations.In this paper, we present
MotionGPT-2, a unified Large Motion-Language Model (LMLM) that addresses these
limitations. MotionGPT-2 accommodates multiple motion-relevant tasks and
supporting multimodal control conditions through pre-trained Large Language
Models (LLMs). It quantizes multimodal inputs-such as text and single-frame
poses-into discrete, LLM-interpretable tokens, seamlessly integrating them into
the LLM's vocabulary. These tokens are then organized into unified prompts,
guiding the LLM to generate motion outputs through a
pretraining-then-finetuning paradigm. We also show that the proposed
MotionGPT-2 is highly adaptable to the challenging 3D holistic motion
generation task, enabled by the innovative motion discretization framework,
Part-Aware VQVAE, which ensures fine-grained representations of body and hand
movements. Extensive experiments and visualizations validate the effectiveness
of our method, demonstrating the adaptability of MotionGPT-2 across motion
generation, motion captioning, and generalized motion completion tasks.
