---
layout: publication
title: 'Direct Language Model Alignment From Online AI Feedback'
authors: Guo Shangmin, Zhang Biao, Liu Tianlin, Liu Tianqi, Khalman Misha, Llinares Felipe, Rame Alexandre, Mesnard Thomas, Zhao Yao, Piot Bilal, Ferret Johan, Blondel Mathieu
conference: "Arxiv"
year: 2024
bibkey: guo2024direct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04792"}
tags: ['Agentic', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
"Direct alignment from preferences (DAP) methods, such as DPO, have recently emerged as efficient alternatives to reinforcement learning from human feedback (RLHF), that do not require a separate reward model. However, the preference datasets used in DAP methods are usually collected ahead of training and never updated, thus the feedback is purely offline. Moreover, responses in these datasets are often sampled from a language model distinct from the one being aligned, and since the model evolves over training, the alignment phase is inevitably off-policy. In this study, we posit that online feedback is key and improves DAP methods. Our method, online AI feedback (OAIF), uses an LLM as annotator: on each training iteration, we sample two responses from the current model and prompt the LLM annotator to choose which one is preferred, thus providing online feedback. Despite its simplicity, we demonstrate via human evaluation in several tasks that OAIF outperforms both offline DAP and RLHF methods. We further show that the feedback leveraged in OAIF is easily controllable, via instruction prompts to the LLM annotator."
