---
layout: publication
title: 'Safety Alignment In NLP Tasks: Weakly Aligned Summarization As An In-context Attack'
authors: Fu Yu, Li Yufei, Xiao Wen, Liu Cong, Dong Yue
conference: "Arxiv"
year: 2023
bibkey: fu2023safety
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06924"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
Recent developments in balancing the usefulness and safety of Large Language
Models (LLMs) have raised a critical question: Are mainstream NLP tasks
adequately aligned with safety consideration? Our study, focusing on
safety-sensitive documents obtained through adversarial attacks, reveals
significant disparities in the safety alignment of various NLP tasks. For
instance, LLMs can effectively summarize malicious long documents but often
refuse to translate them. This discrepancy highlights a previously unidentified
vulnerability: attacks exploiting tasks with weaker safety alignment, like
summarization, can potentially compromise the integrity of tasks traditionally
deemed more robust, such as translation and question-answering (QA). Moreover,
the concurrent use of multiple NLP tasks with lesser safety alignment increases
the risk of LLMs inadvertently processing harmful content. We demonstrate these
vulnerabilities in various safety-aligned LLMs, particularly Llama2 models,
Gemini and GPT-4, indicating an urgent need for strengthening safety alignments
across a broad spectrum of NLP tasks.
