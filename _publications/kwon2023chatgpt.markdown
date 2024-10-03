---
layout: publication
title: 'Chatgpt For Arabic Grammatical Error Correction'
authors: Kwon Sang Yun, Bhatia Gagan, Nagoud El Moatez Billah, Abdul-mageed Muhammad
conference: "Arxiv"
year: 2023
bibkey: kwon2023chatgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04492"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Recently, large language models (LLMs) fine-tuned to follow human instruction have exhibited significant capabilities in various English NLP tasks. However, their performance in grammatical error correction (GEC) tasks, particularly in non-English languages, remains significantly unexplored. In this paper, we delve into abilities of instruction fine-tuned LLMs in Arabic GEC, a task made complex due to Arabic's rich morphology. Our findings suggest that various prompting methods, coupled with (in-context) few-shot learning, demonstrate considerable effectiveness, with GPT-4 achieving up to \(65.49\) F\textsubscript\{1\} score under expert prompting (approximately \(5\) points higher than our established baseline). This highlights the potential of LLMs in low-resource settings, offering a viable approach for generating useful synthetic data for model training. Despite these positive results, we find that instruction fine-tuned models, regardless of their size, significantly underperform compared to fully fine-tuned models of significantly smaller sizes. This disparity highlights a substantial room for improvements for LLMs. Inspired by methods from low-resource machine translation, we also develop a method exploiting synthetic data that significantly outperforms previous models on two standard Arabic benchmarks. Our work sets new SoTA for Arabic GEC, with \(72.19\%\) and \(73.26\) F\(_{1}\) on the 2014 and 2015 QALB datasets, respectively.
