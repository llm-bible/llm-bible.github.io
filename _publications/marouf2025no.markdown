---
layout: publication
title: 'No Images, No Problem: Retaining Knowledge In Continual VQA With Questions-only Memory'
authors: Imad Eddine Marouf, Enzo Tartaglione, Stephane Lathuiliere, Joost Van De Weijer
conference: "Arxiv"
year: 2025
bibkey: marouf2025no
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04469"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'ACL', 'Attention Mechanism', 'Multimodal Models', 'Distillation']
---
Continual Learning in Visual Question Answering (VQACL) requires models to
learn new visual-linguistic tasks (plasticity) while retaining knowledge from
previous tasks (stability). The multimodal nature of VQACL presents unique
challenges, requiring models to balance stability across visual and textual
domains while maintaining plasticity to adapt to novel objects and reasoning
tasks. Existing methods, predominantly designed for unimodal tasks, often
struggle to balance these demands effectively. In this work, we introduce
QUestion-only replay with Attention Distillation (QUAD), a novel approach for
VQACL that leverages only past task questions for regularisation, eliminating
the need to store visual data and addressing both memory and privacy concerns.
QUAD achieves stability by introducing a question-only replay mechanism that
selectively uses questions from previous tasks to prevent overfitting to the
current task's answer space, thereby mitigating the out-of-answer-set problem.
Complementing this, we propose attention consistency distillation, which
uniquely enforces both intra-modal and inter-modal attention consistency across
tasks, preserving essential visual-linguistic associations. Extensive
experiments on VQAv2 and NExT-QA demonstrate that QUAD significantly
outperforms state-of-the-art methods, achieving robust performance in continual
VQA.
