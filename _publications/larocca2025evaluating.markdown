---
layout: publication
title: 'Evaluating AI Capabilities In Detecting Conspiracy Theories On Youtube'
authors: Leonardo La Rocca, Francesco Corso, Francesco Pierri
conference: "Arxiv"
year: 2025
bibkey: larocca2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23570"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'BERT']
---
As a leading online platform with a vast global audience, YouTube's extensive reach also makes it susceptible to hosting harmful content, including disinformation and conspiracy theories. This study explores the use of open-weight Large Language Models (LLMs), both text-only and multimodal, for identifying conspiracy theory videos shared on YouTube. Leveraging a labeled dataset of thousands of videos, we evaluate a variety of LLMs in a zero-shot setting and compare their performance to a fine-tuned RoBERTa baseline. Results show that text-based LLMs achieve high recall but lower precision, leading to increased false positives. Multimodal models lag behind their text-only counterparts, indicating limited benefits from visual data integration. To assess real-world applicability, we evaluate the most accurate models on an unlabeled dataset, finding that RoBERTa achieves performance close to LLMs with a larger number of parameters. Our work highlights the strengths and limitations of current LLM-based approaches for online harmful content detection, emphasizing the need for more precise and robust systems.
