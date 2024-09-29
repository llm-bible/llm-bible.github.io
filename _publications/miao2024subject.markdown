---
layout: publication
title: Subject45;driven Text45;to45;image Generation Via Preference45;based Reinforcement Learning
authors: Miao Yanting, Loh William, Kothawade Suraj, Poupart Pascal, Rashwan Abdullah, Li Yeqing
conference: "Arxiv"
year: 2024
bibkey: miao2024subject
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12164"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Text45;to45;image generative models have recently attracted considerable interest enabling the synthesis of high45;quality images from textual prompts. However these models often lack the capability to generate specific subjects from given reference images or to synthesize novel renditions under varying conditions. Methods like DreamBooth and Subject45;driven Text45;to45;Image (SuTI) have made significant progress in this area. Yet both approaches primarily focus on enhancing similarity to reference images and require expensive setups often overlooking the need for efficient training and avoiding overfitting to the reference images. In this work we present the λ45;Harmonic reward function which provides a reliable reward signal and enables early stopping for faster training and effective regularization. By combining the Bradley45;Terry preference model the λ45;Harmonic reward function also provides preference labels for subject45;driven generation tasks. We propose Reward Preference Optimization (RPO) which offers a simpler setup (requiring only 337; of the negative samples used by DreamBooth) and fewer gradient steps for fine45;tuning. Unlike most existing methods our approach does not require training a text encoder or optimizing text embeddings and achieves text45;image alignment by fine45;tuning only the U45;Net component. Empirically λ45;Harmonic proves to be a reliable approach for model selection in subject45;driven generation tasks. Based on preference labels and early stopping validation from the λ45;Harmonic reward function our algorithm achieves a state45;of45;the45;art CLIP45;I score of 0.833 and a CLIP45;T score of 0.314 on DreamBench.
