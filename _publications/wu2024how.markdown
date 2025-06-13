---
layout: publication
title: 'Finetunebench: How Well Do Commercial Fine-tuning Apis Infuse Knowledge Into Llms?'
authors: Eric Wu, Kevin Wu, James Zou
conference: "Arxiv"
year: 2024
bibkey: wu2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05059"}
  - {name: "Code", url: "https://github.com/kevinwu23/StanfordFineTuneBench"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Merging', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
There is great interest in fine-tuning frontier large language models (LLMs)
to inject new information and update existing knowledge. While commercial LLM
fine-tuning APIs from providers such as OpenAI and Google promise flexible
adaptation for various applications, the efficacy of fine-tuning remains
unclear. In this study, we introduce FineTuneBench, an evaluation framework and
dataset for understanding how well commercial fine-tuning APIs can successfully
learn new and updated knowledge. We analyze five frontier LLMs with
commercially available fine-tuning APIs, including GPT-4o and Gemini 1.5 Pro,
on their effectiveness in two settings: (1) ingesting novel information, such
as recent news events and new people profiles, and (2) updating existing
knowledge, such as updated medical guidelines and code frameworks. Our results
reveal substantial shortcomings in all the models' abilities to effectively
learn new information through fine-tuning, with an average generalization
accuracy of 37% across all models. When updating existing knowledge, such as
incorporating medical guideline updates, commercial fine-tuning APIs show even
more limited capability (average generalization accuracy of 19%). Overall,
fine-tuning GPT-4o mini is the most effective for infusing new knowledge and
updating knowledge, followed by GPT-3.5 Turbo and GPT-4o. The fine-tuning APIs
for Gemini 1.5 Flesh and Gemini 1.5 Pro are unable to learn new knowledge or
update existing knowledge. These findings underscore a major shortcoming in
using current commercial fine-tuning services to achieve reliable knowledge
infusion in common scenarios. We open source the FineTuneBench dataset at
https://github.com/kevinwu23/StanfordFineTuneBench.
