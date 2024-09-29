---
layout: publication
title: Aligning Large Multimodal Models With Factually Augmented RLHF
authors: Zhiqing Sun, Sheng Shen, Shengcao Cao, Haotian Liu, Chunyuan Li, Yikang Shen, Chuang Gan, Liang-yan Gui, Yu-xiong Wang, Yiming Yang, Kurt Keutzer, Trevor Darrell
conference: "Arxiv"
year: 2023
bibkey: sun2023aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2309.14525v1"}
  - {name: "Code", url: "https://llava&#45;rlhf.github.io"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Large Multimodal Models (LMM) are built across modalities and the misalignment between two modalities can result in hallucination generating textual outputs that are not grounded by the multimodal information in context. To address the multimodal misalignment issue we adapt the Reinforcement Learning from Human Feedback (RLHF) from the text domain to the task of vision45;language alignment where human annotators are asked to compare two responses and pinpoint the more hallucinated one and the vision45;language model is trained to maximize the simulated human rewards. We propose a new alignment algorithm called Factually Augmented RLHF that augments the reward model with additional factual information such as image captions and ground45;truth multi45;choice options which alleviates the reward hacking phenomenon in RLHF and further improves the performance. We also enhance the GPT45;445;generated training data (for vision instruction tuning) with previously available human45;written image45;text pairs to improve the general capabilities of our model. To evaluate the proposed approach in real45;world scenarios we develop a new evaluation benchmark MMHAL45;BENCH with a special focus on penalizing hallucinations. As the first LMM trained with RLHF our approach achieves remarkable improvement on the LLaVA45;Bench dataset with the 9437; performance level of the text45;only GPT45;4 (while previous best methods can only achieve the 8737; level) and an improvement by 6037; on MMHAL45;BENCH over other baselines. We opensource our code model data at https://llava&#45;rlhf.github.io.
