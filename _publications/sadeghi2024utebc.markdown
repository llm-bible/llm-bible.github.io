---
layout: publication
title: Utebc-nlp At Semeval-2024 Task 9: Can Llms Be Lateral Thinkers?
authors: Sadeghi Pouya, Abaskohi Amirhossein, Yaghoobzadeh Yadollah
conference: "Arxiv"
year: 2024
bibkey: sadeghi2024utebc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02474"}
tags: ['Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Inspired by human cognition Jiang et al.(2023c) create a benchmark for assessing LLMs lateral thinking-thinking outside the box. Building upon this benchmark we investigate how different prompting methods enhance LLMs performance on this task to reveal their inherent power for outside-the-box thinking ability. Through participating in SemEval-2024 task 9 Sentence Puzzle sub-task we explore prompt engineering methods chain of thoughts (CoT) and direct prompting enhancing with informative descriptions and employing contextualizing prompts using a retrieval augmented generation (RAG) pipeline. Our experiments involve three LLMs including GPT-3.5 GPT-4 and Zephyr-7B-beta. We generate a dataset of thinking paths between riddles and options using GPT-4 validated by humans for quality. Findings indicate that compressed informative prompts enhance performance. Dynamic in-context learning enhances model performance significantly. Furthermore fine-tuning Zephyr on our dataset enhances performance across other commonsense datasets underscoring the value of innovative thinking.
