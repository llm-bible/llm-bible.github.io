---
layout: publication
title: 'Fine-tuning Large Language Models For Adaptive Machine Translation'
authors: Moslem Yasmin, Haque Rejwanul, Way Andy
conference: "Arxiv"
year: 2023
bibkey: moslem2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12740"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
This paper presents the outcomes of fine-tuning Mistral 7B, a general-purpose large language model (LLM), for adaptive machine translation (MT). The fine-tuning process involves utilising a combination of zero-shot and one-shot translation prompts within the medical domain. The primary objective is to enhance real-time adaptive MT capabilities of Mistral 7B, enabling it to adapt translations to the required domain at inference time. The results, particularly for Spanish-to-English MT, showcase the efficacy of the fine-tuned model, demonstrating quality improvements in both zero-shot and one-shot translation scenarios, surpassing Mistral 7B's baseline performance. Notably, the fine-tuned Mistral outperforms ChatGPT gpt-3.5-turbo in zero-shot translation while achieving comparable one-shot translation quality. Moreover, the zero-shot translation of the fine-tuned Mistral matches NLLB 3.3B's performance, and its one-shot translation quality surpasses that of NLLB 3.3B. These findings emphasise the significance of fine-tuning efficient LLMs like Mistral 7B to yield high-quality zero-shot translations comparable to task-oriented models like NLLB 3.3B. Additionally, the adaptive gains achieved in one-shot translation are comparable to those of commercial LLMs such as ChatGPT. Our experiments demonstrate that, with a relatively small dataset of 20,000 segments that incorporate a mix of zero-shot and one-shot prompts, fine-tuning significantly enhances Mistral's in-context learning ability, especially for real-time adaptive MT.
