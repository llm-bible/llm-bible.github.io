---
layout: publication
title: Are Large Language Models Really Robust To Word-level Perturbations
authors: Wang Haoyu, Ma Guozheng, Yu Cong, Gui Ning, Zhang Linrui, Huang Zhiqi, Ma Suwei, Chang Yongzhe, Zhang Sen, Shen Li, Wang Xueqian, Zhao Peilin, Tao Dacheng
conference: "Arxiv"
year: 2023
bibkey: wang2023are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11166"}
  - {name: "Code", url: "https://github.com/Harry-mic/TREvaL"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
The swift advancement in the scales and capabilities of Large Language Models (LLMs) positions them as promising tools for a variety of downstream tasks. In addition to the pursuit of better performance and the avoidance of violent feedback on a certain prompt to ensure the responsibility of the LLM much attention is drawn to the robustness of LLMs. However existing evaluation methods mostly rely on traditional question answering datasets with predefined supervised labels which do not align with the superior generation capabilities of contemporary LLMs. To address this issue we propose a novel rational evaluation approach that leverages pre-trained reward models as diagnostic tools to evaluate the longer conversation generated from more challenging open questions by LLMs which we refer to as the Reward Model for Reasonable Robustness Evaluation (TREvaL). Longer conversations manifest the comprehensive grasp of language models in terms of their proficiency in understanding questions a capability not entirely encompassed by individual words or letters which may exhibit oversimplification and inherent biases. Our extensive empirical experiments demonstrate that TREvaL provides an innovative method for evaluating the robustness of an LLM. Furthermore our results demonstrate that LLMs frequently exhibit vulnerability to word-level perturbations that are commonplace in daily language usage. Notably we are surprised to discover that robustness tends to decrease as fine-tuning (SFT and RLHF) is conducted. The code of TREval is available in https://github.com/Harry-mic/TREvaL.
