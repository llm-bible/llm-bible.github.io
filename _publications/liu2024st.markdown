---
layout: publication
title: ST45;LLM Large Language Models Are Effective Temporal Learners
authors: Liu Ruyang, Li Chen, Tang Haoran, Ge Yixiao, Shan Ying, Li Ge
conference: "Arxiv"
year: 2024
bibkey: liu2024st
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00308"}
  - {name: "Code", url: "https://github.com/TencentARC/ST&#45;LLM"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have showcased impressive capabilities in text comprehension and generation prompting research efforts towards video LLMs to facilitate human45;AI interaction at the video level. However how to effectively encode and understand videos in video45;based dialogue systems remains to be solved. In this paper we investigate a straightforward yet unexplored question Can we feed all spatial45;temporal tokens into the LLM thus delegating the task of video sequence modeling to the LLMs Surprisingly this simple approach yields significant improvements in video understanding. Based upon this we propose ST45;LLM an effective video45;LLM baseline with Spatial45;Temporal sequence modeling inside LLM. Furthermore to address the overhead and stability issues introduced by uncompressed video tokens within LLMs we develop a dynamic masking strategy with tailor45;made training objectives. For particularly long videos we have also designed a global45;local input module to balance efficiency and effectiveness. Consequently we harness LLM for proficient spatial45;temporal modeling while upholding efficiency and stability. Extensive experimental results attest to the effectiveness of our method. Through a more concise model and training pipeline ST45;LLM establishes a new state45;of45;the45;art result on VideoChatGPT45;Bench and MVBench. Codes have been available at https://github.com/TencentARC/ST&#45;LLM.
