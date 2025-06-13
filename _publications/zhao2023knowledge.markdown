---
layout: publication
title: 'Financemath: Knowledge-intensive Math Reasoning In Finance Domains'
authors: Yilun Zhao, Hongjun Liu, Yitao Long, Rui Zhang, Chen Zhao, Arman Cohan
conference: "Arxiv"
year: 2023
bibkey: zhao2023knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.09797'}
tags: ['RAG', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
We introduce FinanceMath, a novel benchmark designed to evaluate LLMs'
capabilities in solving knowledge-intensive math reasoning problems. Compared
to prior works, this study features three core advancements. First, FinanceMath
includes 1,200 problems with a hybrid of textual and tabular content. These
problems require college-level knowledge in the finance domain for effective
resolution. Second, we provide expert-annotated, detailed solution references
in Python program format, ensuring a high-quality benchmark for LLM assessment.
We also construct a finance-domain knowledge bank and investigate various
knowledge integration strategies. Finally, we evaluate a wide spectrum of 44
LLMs with both Chain-of-Thought and Program-of-Thought prompting methods. Our
experimental results reveal that the current best-performing system (i.e.,
GPT-4o) achieves only 60.9% accuracy using CoT prompting, leaving substantial
room for improvement. Moreover, while augmenting LLMs with external knowledge
can improve model performance (e.g., from 47.5% to 54.5% for Gemini-1.5-Pro),
their accuracy remains significantly lower than the estimated human expert
performance of 92%. We believe that FinanceMath can advance future research in
the area of domain-specific knowledge retrieval and integration, particularly
within the context of solving reasoning-intensive tasks.
