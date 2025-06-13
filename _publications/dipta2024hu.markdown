---
layout: publication
title: 'HU At Semeval-2024 Task 8A: Can Contrastive Learning Learn Embeddings To Detect Machine-generated Text?'
authors: Shubhashis Roy Dipta, Sadat Shahriar
conference: "Arxiv"
year: 2024
bibkey: dipta2024hu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11815"}
  - {name: "Code", url: "https://github.com/dipta007/SemEval24-Task8"}
tags: ['Applications', 'Language Modeling', 'Reinforcement Learning', 'Has Code', 'Pretraining Methods']
---
This paper describes our system developed for SemEval-2024 Task 8,
``Multigenerator, Multidomain, and Multilingual Black-Box Machine-Generated
Text Detection'' Machine-generated texts have been one of the main concerns due
to the use of large language models (LLM) in fake text generation, phishing,
cheating in exams, or even plagiarizing copyright materials. A lot of systems
have been developed to detect machine-generated text. Nonetheless, the majority
of these systems rely on the text-generating model. This limitation is
impractical in real-world scenarios, as it's often impossible to know which
specific model the user has used for text generation. In this work, we propose
a \\(\textbf\{single\}\\) model based on contrastive learning, which uses
\\(\textbf\{\\)\approx\\(40% of the baseline's parameters\}\\) (149M vs. 355M) but shows
a comparable performance on the test dataset \\((\textbf\{21st out of 137
participants\})\\). Our key finding is that even without an ensemble of multiple
models, a single base model can have comparable performance with the help of
data augmentation and contrastive learning. Our code is publicly available at
https://github.com/dipta007/SemEval24-Task8.
