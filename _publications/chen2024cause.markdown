---
layout: publication
title: 'Cause-aware Empathetic Response Generation Via Chain-of-thought Fine-tuning'
authors: Xinhao Chen, Chong Yang, Man Lan, Li Cai, Yang Chen, Tu Hu, Xinlin Zhuang, Aimin Zhou
conference: "Arxiv"
year: 2024
bibkey: chen2024cause
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.11599'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Empathetic response generation endows agents with the capability to
comprehend dialogue contexts and react to expressed emotions. Previous works
predominantly focus on leveraging the speaker's emotional labels, but ignore
the importance of emotion cause reasoning in empathetic response generation,
which hinders the model's capacity for further affective understanding and
cognitive inference. In this paper, we propose a cause-aware empathetic
generation approach by integrating emotions and causes through a well-designed
Chain-of-Thought (CoT) prompt on Large Language Models (LLMs). Our approach can
greatly promote LLMs' performance of empathy by instruction tuning and
enhancing the role awareness of an empathetic listener in the prompt.
Additionally, we propose to incorporate cause-oriented external knowledge from
COMET into the prompt, which improves the diversity of generation and
alleviates conflicts between internal and external knowledge at the same time.
Experimental results on the benchmark dataset demonstrate that our approach on
LLaMA-7b achieves state-of-the-art performance in both automatic and human
evaluations.
