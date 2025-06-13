---
layout: publication
title: 'A Comprehensive Evaluation Of Large Language Models On Mental Illnesses'
authors: Abdelrahman Hanafi, Mohammed Saad, Noureldin Zahran, Radwa J. Hanafy, Mohammed E. Fouda
conference: "Arxiv"
year: 2024
bibkey: hanafi2024comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15687"}
tags: ['GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Few-Shot', 'Prompting']
---
Large language models have shown promise in various domains, including
healthcare. In this study, we conduct a comprehensive evaluation of LLMs in the
context of mental health tasks using social media data. We explore the
zero-shot (ZS) and few-shot (FS) capabilities of various LLMs, including GPT-4,
Llama 3, Gemini, and others, on tasks such as binary disorder detection,
disorder severity evaluation, and psychiatric knowledge assessment. Our
evaluation involved 33 models testing 9 main prompt templates across the tasks.
Key findings revealed that models like GPT-4 and Llama 3 exhibited superior
performance in binary disorder detection, with accuracies reaching up to 85% on
certain datasets. Moreover, prompt engineering played a crucial role in
enhancing model performance. Notably, the Mixtral 8x22b model showed an
improvement of over 20%, while Gemma 7b experienced a similar boost in
performance. In the task of disorder severity evaluation, we observed that FS
learning significantly improved the model's accuracy, highlighting the
importance of contextual examples in complex assessments. Notably, the
Phi-3-mini model exhibited a substantial increase in performance, with balanced
accuracy improving by over 6.80% and mean average error dropping by nearly 1.3
when moving from ZS to FS learning. In the psychiatric knowledge task, recent
models generally outperformed older, larger counterparts, with the Llama 3.1
405b achieving an accuracy of 91.2%. Despite promising results, our analysis
identified several challenges, including variability in performance across
datasets and the need for careful prompt engineering. Furthermore, the ethical
guards imposed by many LLM providers hamper the ability to accurately evaluate
their performance, due to tendency to not respond to potentially sensitive
queries.
