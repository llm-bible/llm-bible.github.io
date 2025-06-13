---
layout: publication
title: 'An Llm-assisted Easy-to-trigger Backdoor Attack On Code Completion Models: Injecting Disguised Vulnerabilities Against Strong Detection'
authors: Shenao Yan, Shen Wang, Yue Duan, Hanbin Hong, Kiho Lee, Doowon Kim, Yuan Hong
conference: "Arxiv"
year: 2024
bibkey: yan2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06822"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) have transformed code completion tasks,
providing context-based suggestions to boost developer productivity in software
engineering. As users often fine-tune these models for specific applications,
poisoning and backdoor attacks can covertly alter the model outputs. To address
this critical security challenge, we introduce CodeBreaker, a pioneering
LLM-assisted backdoor attack framework on code completion models. Unlike recent
attacks that embed malicious payloads in detectable or irrelevant sections of
the code (e.g., comments), CodeBreaker leverages LLMs (e.g., GPT-4) for
sophisticated payload transformation (without affecting functionalities),
ensuring that both the poisoned data for fine-tuning and generated code can
evade strong vulnerability detection. CodeBreaker stands out with its
comprehensive coverage of vulnerabilities, making it the first to provide such
an extensive set for evaluation. Our extensive experimental evaluations and
user studies underline the strong attack performance of CodeBreaker across
various settings, validating its superiority over existing approaches. By
integrating malicious payloads directly into the source code with minimal
transformation, CodeBreaker challenges current security measures, underscoring
the critical need for more robust defenses for code completion.
