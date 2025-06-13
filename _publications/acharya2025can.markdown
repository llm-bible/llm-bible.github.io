---
layout: publication
title: 'Can We Enhance Bug Report Quality Using Llms?: An Empirical Study Of Llm-based Bug Report Generation'
authors: Jagrit Acharya, Gouri Ginde
conference: "Arxiv"
year: 2025
bibkey: acharya2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18804"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning']
---
Bug reports contain the information developers need to triage and fix
software bugs. However, unclear, incomplete, or ambiguous information may lead
to delays and excessive manual effort spent on bug triage and resolution. In
this paper, we explore whether Instruction fine-tuned Large Language Models
(LLMs) can automatically transform casual, unstructured bug reports into
high-quality, structured bug reports adhering to a standard template. We
evaluate three open-source instruction-tuned LLMs (*Qwen 2.5, Mistral, and
Llama 3.2*) against ChatGPT-4o, measuring performance on established metrics
such as CTQRS, ROUGE, METEOR, and SBERT. Our experiments show that fine-tuned
Qwen 2.5 achieves a CTQRS score of \textbf\{77%\}, outperforming both fine-tuned
Mistral (\textbf\{71%\}), Llama 3.2 (\textbf\{63%\}) and ChatGPT in 3-shot learning
(\textbf\{75%\}). Further analysis reveals that Llama 3.2 shows higher accuracy
of detecting missing fields particularly Expected Behavior and Actual Behavior,
while Qwen 2.5 demonstrates superior performance in capturing
Steps-to-Reproduce, with an F1 score of 76%. Additional testing of the models
on other popular projects (e.g., Eclipse, GCC) demonstrates that our approach
generalizes well, achieving up to \textbf\{70%\} CTQRS in unseen projects' bug
reports. These findings highlight the potential of instruction fine-tuning in
automating structured bug report generation, reducing manual effort for
developers and streamlining the software maintenance process.
