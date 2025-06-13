---
layout: publication
title: 'Great, Now Write An Article About That: The Crescendo Multi-turn LLM Jailbreak Attack'
authors: Mark Russinovich, Ahmed Salem, Ronen Eldan
conference: "Arxiv"
year: 2024
bibkey: russinovich2024now
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.01833'}
tags: ['Security', 'Model Architecture', 'Applications', 'GPT', 'Prompting', 'Multimodal Models', 'Ethics and Bias', 'Responsible AI']
---
Large Language Models (LLMs) have risen significantly in popularity and are
increasingly being adopted across multiple applications. These LLMs are heavily
aligned to resist engaging in illegal or unethical topics as a means to avoid
contributing to responsible AI harms. However, a recent line of attacks, known
as jailbreaks, seek to overcome this alignment. Intuitively, jailbreak attacks
aim to narrow the gap between what the model can do and what it is willing to
do. In this paper, we introduce a novel jailbreak attack called Crescendo.
Unlike existing jailbreak methods, Crescendo is a simple multi-turn jailbreak
that interacts with the model in a seemingly benign manner. It begins with a
general prompt or question about the task at hand and then gradually escalates
the dialogue by referencing the model's replies progressively leading to a
successful jailbreak. We evaluate Crescendo on various public systems,
including ChatGPT, Gemini Pro, Gemini-Ultra, LlaMA-2 70b and LlaMA-3 70b Chat,
and Anthropic Chat. Our results demonstrate the strong efficacy of Crescendo,
with it achieving high attack success rates across all evaluated models and
tasks. Furthermore, we present Crescendomation, a tool that automates the
Crescendo attack and demonstrate its efficacy against state-of-the-art models
through our evaluations. Crescendomation surpasses other state-of-the-art
jailbreaking techniques on the AdvBench subset dataset, achieving 29-61% higher
performance on GPT-4 and 49-71% on Gemini-Pro. Finally, we also demonstrate
Crescendo's ability to jailbreak multimodal models.
