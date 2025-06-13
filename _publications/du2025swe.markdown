---
layout: publication
title: 'Swe-dev: Evaluating And Training Autonomous Feature-driven Software Development'
authors: Yaxin Du, Yuzhu Cai, Yifan Zhou, Cheng Wang, Yu Qian, Xianghe Pang, Qian Liu, Yue Hu, Siheng Chen
conference: "Arxiv"
year: 2025
bibkey: du2025swe
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16975'}
  - {name: "Code", url: 'https://github.com/justLittleWhite/SWE-Dev}{https://github.com/justLittleWhite/SWE-Dev'}
tags: ['Agentic', 'Has Code', 'Agent', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have shown strong capability in diverse software engineering tasks, e.g. code completion, bug fixing, and document generation. However, feature-driven development (FDD), a highly prevalent real-world task that involves developing new functionalities for large, existing codebases, remains underexplored. We therefore introduce SWE-Dev, the first large-scale dataset (with 14,000 training and 500 test samples) designed to evaluate and train autonomous coding systems on real-world feature development tasks. To ensure verifiable and diverse training, SWE-Dev uniquely provides all instances with a runnable environment and its developer-authored executable unit tests. This collection not only provides high-quality data for Supervised Fine-Tuning (SFT), but also enables Reinforcement Learning (RL) by delivering accurate reward signals from executable unit tests. Our extensive evaluations on SWE-Dev, covering 17 chatbot LLMs, 10 reasoning models, and 10 Multi-Agent Systems (MAS), reveal that FDD is a profoundly challenging frontier for current AI (e.g., Claude-3.7-Sonnet achieves only 22.45% Pass@3 on the hard test split). Crucially, we demonstrate that SWE-Dev serves as an effective platform for model improvement: fine-tuning on training set enabled a 7B model comparable to GPT-4o on \textit\{hard\} split, underscoring the value of its high-quality training data. Code is available here \href\{https://github.com/justLittleWhite/SWE-Dev\}\{https://github.com/justLittleWhite/SWE-Dev\}.
