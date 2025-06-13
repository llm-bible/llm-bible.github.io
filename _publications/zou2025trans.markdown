---
layout: publication
title: 'Trans-zero: Self-play Incentivizes Large Language Models For Multilingual Translation Without Parallel Data'
authors: Wei Zou, Sen Yang, Yu Bao, Shujian Huang, Jiajun Chen, Shanbo Cheng
conference: "Arxiv"
year: 2025
bibkey: zou2025trans
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14669"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
The rise of Large Language Models (LLMs) has reshaped machine translation (MT), but multilingual MT still relies heavily on parallel data for supervised fine-tuning (SFT), facing challenges like data scarcity for low-resource languages and catastrophic forgetting. To address these issues, we propose TRANS-ZERO, a self-play framework that leverages only monolingual data and the intrinsic multilingual knowledge of LLM. TRANS-ZERO combines Genetic Monte-Carlo Tree Search (G-MCTS) with preference optimization, achieving strong translation performance that rivals supervised methods. Experiments demonstrate that this approach not only matches the performance of models trained on large-scale parallel data but also excels in non-English translation directions. Further analysis reveals that G-MCTS itself significantly enhances translation quality by exploring semantically consistent candidates through iterative translations, providing a robust foundation for the framework's succuss.
