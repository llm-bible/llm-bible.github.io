---
layout: publication
title: 'Ask Patients With Patience: Enabling Llms For Human-centric Medical Dialogue With Grounded Reasoning'
authors: Jiayuan Zhu, Junde Wu
conference: "Arxiv"
year: 2025
bibkey: zhu2025ask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07143"}
  - {name: "Code", url: "https://github.com/SuperMedIntel/AskPatients"}
tags: ['Tools', 'Efficiency and Optimization', 'Has Code']
---
Accurate and efficient diagnosis in online medical consultations remains a
challenge for current large language models. These models often rely on
single-turn interactions and lack the ability to refine their predictions
through follow-up questions. Additionally, their responses frequently contain
complex medical terminology, making them less accessible to non-medical users
and creating barriers to effective communication. In this paper, we introduce
Ask Patients with Patience (APP), the first multi-turn dialogue that enables
LLMs to iteratively refine diagnoses based on grounded reasoning. By
integrating medical guidelines and entropy minimization, APP improves both
diagnostic accuracy and efficiency. Furthermore, it features human-centric
communication that bridges the gap between user comprehension and medical
terminology, significantly enhancing user accessibility and engagement. We
evaluated APP using a subset of the ReMeDi dataset, comparing it with
single-turn and traditional multi-turn LLM baselines. APP achieved higher
similarity scores in diagnosis predictions, demonstrating better alignment with
ground truth diagnoses. Entropy analysis showed that APP reduces diagnostic
uncertainty more rapidly across iterations, increasing confidence in its
predictions. APP also excels in user accessibility and empathy, further
bridging the gap between complex medical language and user understanding. Code
will be released at: https://github.com/SuperMedIntel/AskPatients.
