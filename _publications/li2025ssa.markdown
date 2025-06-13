---
layout: publication
title: 'SSA-COMET: Do Llms Outperform Learned Metrics In Evaluating MT For Under-resourced African Languages?'
authors: Senyu Li, Jiayi Wang, Felermino D. M. A. Ali, Colin Cherry, Daniel Deutsch, Eleftheria Briakou, Rui Sousa-silva, Henrique Lopes Cardoso, Pontus Stenetorp, David Ifeoluwa Adelani
conference: "Arxiv"
year: 2025
bibkey: li2025ssa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04557"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting', 'Applications']
---
Evaluating machine translation (MT) quality for under-resourced African languages remains a significant challenge, as existing metrics often suffer from limited language coverage and poor performance in low-resource settings. While recent efforts, such as AfriCOMET, have addressed some of the issues, they are still constrained by small evaluation sets, a lack of publicly available training data tailored to African languages, and inconsistent performance in extremely low-resource scenarios. In this work, we introduce SSA-MTE, a large-scale human-annotated MT evaluation (MTE) dataset covering 13 African language pairs from the News domain, with over 63,000 sentence-level annotations from a diverse set of MT systems. Based on this data, we develop SSA-COMET and SSA-COMET-QE, improved reference-based and reference-free evaluation metrics. We also benchmark prompting-based approaches using state-of-the-art LLMs like GPT-4o and Claude. Our experimental results show that SSA-COMET models significantly outperform AfriCOMET and are competitive with the strongest LLM (Gemini 2.5 Pro) evaluated in our study, particularly on low-resource languages such as Twi, Luo, and Yoruba. All resources are released under open licenses to support future research.
