---
layout: publication
title: 'Efficient Model-agnostic Alignment Via Bayesian Persuasion'
authors: Bai Fengshuo, Wang Mingzhi, Zhang Zhaowei, Chen Boyuan, Xu Yinda, Wen Ying, Yang Yaodong
conference: "Arxiv"
year: 2024
bibkey: bai2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18718"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
"With recent advancements in large language models (LLMs), alignment has emerged as an effective technique for keeping LLMs consensus with human intent. Current methods primarily involve direct training through Supervised Fine-tuning (SFT) or Reinforcement Learning from Human Feedback (RLHF), both of which require substantial computational resources and extensive ground truth data. This paper explores an efficient method for aligning black-box large models using smaller models, introducing a model-agnostic and lightweight Bayesian Persuasion Alignment framework. We formalize this problem as an optimization of the signaling strategy from the small model's perspective. In the persuasion process, the small model (Advisor) observes the information item (i.e., state) and persuades large models (Receiver) to elicit improved responses. The Receiver then generates a response based on the input, the signal from the Advisor, and its updated belief about the information item. Through training using our framework, we demonstrate that the Advisor can significantly enhance the performance of various Receivers across a range of tasks. We theoretically analyze our persuasion framework and provide an upper bound on the Advisor's regret, confirming its effectiveness in learning the optimal signaling strategy. Our Empirical results demonstrates that GPT-2 can significantly improve the performance of various models, achieving an average enhancement of 16.1&#37; in mathematical reasoning ability and 13.7&#37; in code generation. We hope our work can provide an initial step toward rethinking the alignment framework from the Bayesian Persuasion perspective."
