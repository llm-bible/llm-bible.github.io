---
layout: publication
title: 'Fistech: Financial Style Transfer To Enhance Creativity Without Hallucinations In Llms'
authors: Sohini Roychowdhury, Marko Krema, Brian Moore, Xingjian Lai, Dike Effedua, Bharat Jethwani
conference: "IEEE Big Data 2024"
year: 2024
bibkey: roychowdhury2024financial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05365"}
tags: ['Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Recent trends in Generative AI have emerged towards fine-tuning foundational
large language models (LLMs) to create domain-specific LLMs for automation and
chatbot-like applications. Specialized applications for analytics-heavy domains
such as Financial report generation require specific writing styles that
comprise compound and creative sentences with minimized hallucinations. In this
work, we explore the self-corrective auto-regressive qualities of LLMs to learn
creativity in writing styles with minimal prompting. We propose a novel
two-stage fine-tuning (FT) strategy wherein in the first stage public domain
financial reports are used to train for writing styles while allowing the LLM
to hallucinate. In the second stage the examples of hallucinations are manually
corrected and further used to fine-tune the LLM. The finally trained LLM learns
to generate specific financial report sections using minimal instructions and
tabular data inputs while ensuring low fine-tuning costs. Our proposed
two-stage fine-tuning boosts the accuracy of financial questions answering by
two-folds while reducing hallucinations by over 50%. Also, the fine-tuned model
has lower perplexity, improved ROUGE, TER and BLEU scores, higher creativity
and knowledge density with lower uncertainty and cross entropy than base LLMs.
Thus, the proposed framework can be generalized to train creativity in LLMs by
first allowing them to hallucinate.
