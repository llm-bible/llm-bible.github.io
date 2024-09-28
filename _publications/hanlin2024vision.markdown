---
layout: publication
title: Vision-and-Language Navigation Generative Pretrained Transformer
authors: Hanlin Wen
conference: "Arxiv"
year: 2024
bibkey: hanlin2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16994"}
tags: ['ARXIV', 'Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
In the Vision-and-Language Navigation (VLN) field agents are tasked with navigating real-world scenes guided by linguistic instructions. Enabling the agent to adhere to instructions throughout the process of navigation represents a significant challenge within the domain of VLN. To address this challenge common approaches often rely on encoders to explicitly record past locations and actions increasing model complexity and resource consumption. Our proposal the Vision-and-Language Navigation Generative Pretrained Transformer (VLN-GPT) adopts a transformer decoder model (GPT2) to model trajectory sequence dependencies bypassing the need for historical encoding modules. This method allows for direct historical information access through trajectory sequence enhancing efficiency. Furthermore our model separates the training process into offline pre-training with imitation learning and online fine-tuning with reinforcement learning. This distinction allows for more focused training objectives and improved performance. Performance assessments on the VLN dataset reveal that VLN-GPT surpasses complex state-of-the-art encoder-based models.
