---
layout: publication
title: 'Mcqg-srefine: Multiple Choice Question Generation And Evaluation With Iterative Self-critique, Correction, And Comparison Feedback'
authors: Zonghai Yao, Aditya Parashar, Huixue Zhou, Won Seok Jang, Feiyun Ouyang, Zhichao Yang, Hong Yu
conference: "Arxiv"
year: 2024
bibkey: yao2024mcqg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13191"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting', 'Applications']
---
Automatic question generation (QG) is essential for AI and NLP, particularly
in intelligent tutoring, dialogue systems, and fact verification. Generating
multiple-choice questions (MCQG) for professional exams, like the United States
Medical Licensing Examination (USMLE), is particularly challenging, requiring
domain expertise and complex multi-hop reasoning for high-quality questions.
However, current large language models (LLMs) like GPT-4 struggle with
professional MCQG due to outdated knowledge, hallucination issues, and prompt
sensitivity, resulting in unsatisfactory quality and difficulty. To address
these challenges, we propose MCQG-SRefine, an LLM self-refine-based (Critique
and Correction) framework for converting medical cases into high-quality
USMLE-style questions. By integrating expert-driven prompt engineering with
iterative self-critique and self-correction feedback, MCQG-SRefine
significantly enhances human expert satisfaction regarding both the quality and
difficulty of the questions. Furthermore, we introduce an LLM-as-Judge-based
automatic metric to replace the complex and costly expert evaluation process,
ensuring reliable and expert-aligned assessments.
