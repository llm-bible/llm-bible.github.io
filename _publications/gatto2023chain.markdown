---
layout: publication
title: 'Chain-of-thought Embeddings For Stance Detection On Social Media'
authors: Joseph Gatto, Omar Sharif, Sarah Masud Preum
conference: "Arxiv"
year: 2023
bibkey: gatto2023chain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.19750'}
tags: ['RAG', 'Training Techniques', 'BERT', 'Model Architecture', 'Merging', 'Prompting', 'Reinforcement Learning']
---
Stance detection on social media is challenging for Large Language Models
(LLMs), as emerging slang and colloquial language in online conversations often
contain deeply implicit stance labels. Chain-of-Thought (COT) prompting has
recently been shown to improve performance on stance detection tasks --
alleviating some of these issues. However, COT prompting still struggles with
implicit stance identification. This challenge arises because many samples are
initially challenging to comprehend before a model becomes familiar with the
slang and evolving knowledge related to different topics, all of which need to
be acquired through the training data. In this study, we address this problem
by introducing COT Embeddings which improve COT performance on stance detection
tasks by embedding COT reasonings and integrating them into a traditional
RoBERTa-based stance detection pipeline. Our analysis demonstrates that 1) text
encoders can leverage COT reasonings with minor errors or hallucinations that
would otherwise distort the COT output label. 2) Text encoders can overlook
misleading COT reasoning when a sample's prediction heavily depends on
domain-specific patterns. Our model achieves SOTA performance on multiple
stance detection datasets collected from social media.
