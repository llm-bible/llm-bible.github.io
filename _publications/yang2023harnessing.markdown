---
layout: publication
title: Harnessing the Power of Large Language Models for Natural Language to First-Order Logic Translation
authors: Yang Yuan, Xiong Siheng, Payani Ali, Shareghi Ehsan, Fekri Faramarz
conference: "Arxiv"
year: 2023
bibkey: yang2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15541"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Translating natural language sentences to first-order logic (NL-FOL translation) is a longstanding challenge in the NLP and formal logic literature. This paper introduces LogicLLaMA a LLaMA-7B model fine-tuned for NL-FOL translation using LoRA on a single GPU. LogicLLaMA is capable of directly translating natural language into FOL rules which outperforms GPT-3.5. LogicLLaMA is also equipped to correct FOL rules predicted by GPT-3.5 and can achieve similar performance as GPT-4 with a fraction of the cost. This correction ability was achieved by a novel supervised fine-tuning (SFT) + reinforcement learning with human feedback (RLHF) framework which initially trains on synthetically perturbed NL-FOL pairs to encourage chain-of-thought reasoning and then fine-tunes with RLHF on GPT-3.5 outputs using a FOL verifier as the reward model. To train LogicLLaMA we present MALLS (large language odel generted N-FO pair) a dataset of 34K high-quality and diverse sentence-level NL-FOL pairs collected from GPT-4. The dataset was created by implementing a pipeline that prompts GPT-4 for pairs and dynamically adjusts the prompts to ensure the collection of pairs with rich and diverse contexts at different levels of complexity and verifies the validity of the generated FOL rules. Codes weights and data are available at .
