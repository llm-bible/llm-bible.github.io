---
layout: publication
title: 'Semiollm: Evaluating Large Language Models For Diagnostic Reasoning From Unstructured Clinical Narratives In Epilepsy'
authors: Meghal Dani, Muthu Jeyanthi Prakash, Zeynep Akata, Stefanie Liebe
conference: "Arxiv"
year: 2024
bibkey: dani2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.03004'}
tags: ['Interpretability and Explainability', 'RAG', 'Model Architecture', 'GPT', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) have been shown to encode clinical knowledge.
Many evaluations, however, rely on structured question-answer benchmarks,
overlooking critical challenges of interpreting and reasoning about
unstructured clinical narratives in real-world settings. Using free-text
clinical descriptions, we present SemioLLM, an evaluation framework that
benchmarks 6 state-of-the-art models (GPT-3.5, GPT-4, Mixtral-8x7B, Qwen-72B,
LlaMa2, LlaMa3) on a core diagnostic task in epilepsy. Leveraging a database of
1,269 seizure descriptions, we show that most LLMs are able to accurately and
confidently generate probabilistic predictions of seizure onset zones in the
brain. Most models approach clinician-level performance after prompt
engineering, with expert-guided chain-of-thought reasoning leading to the most
consistent improvements. Performance was further strongly modulated by clinical
in-context impersonation, narrative length and language context (13.7%, 32.7%
and 14.2% performance variation, respectively). However, expert analysis of
reasoning outputs revealed that correct prediction can be based on hallucinated
knowledge and deficient source citation accuracy, underscoring the need to
improve interpretability of LLMs in clinical use. Overall, SemioLLM provides a
scalable, domain-adaptable framework for evaluating LLMs in clinical
disciplines where unstructured verbal descriptions encode diagnostic
information. By identifying both the strengths and limitations of
state-of-the-art models, our work supports the development of clinically robust
and globally applicable AI systems for healthcare.
